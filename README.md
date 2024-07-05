<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio | Data Science & DevOps Expert</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#data-science">Data Science</a></li>
                <li><a href="#devops">DevOps</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-text">
            <h1>Welcome to my Portfolio</h1>
            <p>Explore my expertise in Data Science and DevOps</p>
            <button class="scroll-down">Scroll Down</button>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>I'm a highly skilled Data Science and DevOps professional with a passion for leveraging technology to drive business growth.</p>
        <img src="profile-pic.jpg" alt="Profile Picture">
    </section>

    <!-- Data Science Section -->
    <section id="data-science">
        <h2>Data Science Expertise</h2>
        <ul>
            <li>Machine Learning</li>
            <li>Deep Learning</li>
            <li>Natural Language Processing</li>
            <li>Data Visualization</li>
        </ul>
        <div class="project-grid">
            <div class="project">
                <img src="project1.jpg" alt="Project 1">
                <h3>Project 1: Sentiment Analysis</h3>
                <p>Developed a sentiment analysis model using TensorFlow and Keras to analyze customer reviews.</p>
            </div>
            <div class="project">
                <img src="project2.jpg" alt="Project 2">
                <h3>Project 2: Recommendation System</h3>
                <p>Designed a recommendation system using collaborative filtering and matrix factorization to suggest products to customers.</p>
            </div>
            <!-- Add more projects here -->
        </div>
    </section>

    <!-- DevOps Section -->
    <section id="devops">
        <h2>DevOps Expertise</h2>
        <ul>
            <li>Containerization (Docker)</li>
            <li>Orchestration (Kubernetes)</li>
            <li>Continuous Integration (CI)</li>
            <li>Continuous Deployment (CD)</li>
        </ul>
        <div class="project-grid">
            <div class="project">
                <img src="project3.jpg" alt="Project 3">
                <h3>Project 3: CI/CD Pipeline</h3>
                <p>Implemented a CI/CD pipeline using Jenkins and Docker to automate testing and deployment of a web application.</p>
            </div>
            <div class="project">
                <img src="project4.jpg" alt="Project 4">
                <h3>Project 4: Kubernetes Deployment</h3>
                <p>Deployed a scalable web application using Kubernetes and Docker to ensure high availability and fault tolerance.</p>
            </div>
            <!-- Add more projects here -->
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Get in Touch</h2>
        <p>Feel free to reach out to me for any questions or opportunities.</p>
        <ul>
            <li><a href="mailto:your-email@example.com">your-email@example.com</a></li>
            <li><a href="https://www.linkedin.com/in/your-linkedin-profile/">LinkedIn</a></li>
            <li><a href="https://github.com/your-github-username">GitHub</a></li>
        </ul>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2023 Your Name. All rights reserved.</p>
    </footer>

    <!-- JavaScript files -->
    <script src="script.js">
    <head>
    <link rel="stylesheet" href="styles.css">
    // script.js
import styled from 'styled-components';

const Hero = styled.section`
  background-color: #f0f0f0;
  padding: 20px;
  text-align: center;
`;

const HeroText = styled.div`
  font-size: 24px;
  font-weight: bold;
  margin-bottom: 10px;
`;

const ScrollDownButton = styled.button`
  background-color: #4CAF50;
  color: #ffffff;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
`;

// Use the styled components in your JavaScript code
const heroSection = document.createElement('section');
heroSection.className = Hero;

const heroText = document.createElement('div');
heroText.className = HeroText;
heroText.textContent = 'Welcome to my Portfolio';

const scrollDownButton = document.createElement('button');
scrollDownButton.className = ScrollDownButton;
scrollDownButton.textContent = 'Scroll Down';

heroSection.appendChild(heroText);
heroSection.appendChild(scrollDownButton);

document.body.appendChild(heroSection);
</head>

  </script>
</body>
</html>


