<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arfath Ali's GitHub Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom right, #0f2027, #203a43, #2c5364);
            color: #f0f0f0;
        }

        .container {
            max-width: 1000px;
            margin: 2rem auto;
            padding: 2rem;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.5);
        }

        .hero {
            text-align: center;
            margin-bottom: 2rem;
        }

        .hero img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
        }

        .hero h1 {
            color: #ffdd57;
            font-size: 2.5rem;
            margin: 1rem 0 0.5rem;
        }

        .hero p {
            font-size: 1.2rem;
            line-height: 1.8;
        }

        .section {
            margin-top: 3rem;
        }

        .section h2 {
            color: #ffdd57;
            margin-bottom: 1rem;
            text-align: center;
        }

        .projects,
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 1.5rem;
            justify-content: center;
        }

        .project-card,
        .skill-card {
            flex: 1 1 calc(45% - 1rem);
            background: rgba(255, 255, 255, 0.2);
            padding: 1.5rem;
            border-radius: 10px;
            box-shadow: 0 3px 8px rgba(0, 0, 0, 0.3);
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .project-card:hover,
        .skill-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.5);
        }

        .project-card h3 {
            margin-top: 0;
            font-size: 1.5rem;
            color: #fff;
        }

        .project-card p {
            font-size: 1rem;
            margin-bottom: 1rem;
        }

        .project-card a {
            color: #ffdd57;
            text-decoration: none;
            font-weight: bold;
        }

        .project-card a:hover {
            text-decoration: underline;
        }

        .skill-card img {
            width: 60px;
            height: 60px;
            margin: 1rem auto;
        }

        .skill-card p {
            font-size: 1rem;
            font-weight: bold;
        }

        .contact {
            text-align: center;
            margin-top: 3rem;
        }

        .contact a {
            display: inline-block;
            margin: 0.5rem;
            color: #ffdd57;
            text-decoration: none;
            font-size: 1.2rem;
            font-weight: bold;
        }

        .contact a img {
            width: 30px;
            vertical-align: middle;
            margin-right: 0.5rem;
        }

        .contact a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Hero Section -->
        <div class="hero">
            <img src="https://avatars.githubusercontent.com/u/your-github-id" alt="Profile Image">
            <h1>Welcome to Arfath Ali's GitHub Profile</h1>
            <p>
                Hi, I'm Arfath Ali, a DevOps Engineer with expertise in cloud computing, automation,
                and cutting-edge DevOps tools. I love building scalable and efficient solutions that
                make a difference.
            </p>
        </div>

        <!-- Projects Section -->
        <div class="section projects">
            <h2>My Projects</h2>

            <div class="project-card">
                <h3>3-Tier EKS Web Application</h3>
                <p>
                    Deployed a scalable 3-tier app using Amazon EKS, Dockerized components, and CI/CD pipelines.
                </p>
                <a href="https://github.com/arfath29/Ekart-project" target="_blank">View Project</a>
            </div>

            <div class="project-card">
                <h3>React Todo App Automation</h3>
                <p>
                    Automated deployment of a React app on AWS EC2 with Nginx reverse proxy and Jenkins CI/CD pipelines.
                </p>
                <a href="#" target="_blank">View Project</a>
            </div>

            <div class="project-card">
                <h3>Ultimate CI/CD Pipeline</h3>
                <p>
                    Designed a CI/CD pipeline integrating Jenkins, SonarQube, Trivy, and Kubernetes deployments.
                </p>
                <a href="#" target="_blank">View Project</a>
            </div>
        </div>

        <!-- Skills Section -->
        <div class="section skills">
            <h2>Skills</h2>
            <!-- Add your skills as shown in the earlier code -->
        </div>

        <!-- Contact Section -->
        <div class="contact">
            <h2>Contact Me</h2>
            <a href="https://www.linkedin.com/in/mohammed-arfath-ali-1572b12aa" target="_blank">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" alt="LinkedIn"> LinkedIn
            </a>
            <a href="https://github.com/arfath29" target="_blank">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub"> GitHub
            </a>
            <a href="mailto:your-email@example.com">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" alt="Email"> Email Me
            </a>
        </div>
    </div>
</body>
</html>
