# WEB HACKATHON - 1
Welcome to the Portfolio Website Hackathon! We are excited to have you join us in creating amazing portfolio websites. Below are the guidelines to ensure a smooth and productive hackathon experience.

## Introduction
The goal of this hackathon is to build a one page portfolio website that showcases your skills, projects, and professional experience. This is an excellent opportunity to create or enhance your personal brand and demonstrate your abilities to potential employers or clients.

## Project Requirements
### Personal Information: 
Include sections for your name, a brief bio, contact information, and links to your social media profiles (e.g., LinkedIn, GitHub).

### Portfolio: 
Showcase your projects with descriptions, images, and links to live demos or repositories.

### Skills: 
List your technical and non-technical skills.

### Experience: 
Detail your professional experience, including job titles, companies, and descriptions of your roles.

### Education: 
Include your educational background.

## Submission Guidelines
Repository Setup: Fork this repository and create a new branch for your project.
Commit Messages: Use clear and descriptive commit messages to document your progress.
Pull Request: Submit a pull request to the main branch once you have completed your project. Include a brief description of your website and any additional notes.
Deadline: All submissions must be made by monday 1st July 12pm EAT

## Judging Criteria
Submissions will be judged based on the following criteria:

Design: Visual appeal, creativity, and user interface design.
Functionality: Responsiveness, performance, and interactivity.
Content: Clarity, completeness, and presentation of information.
Originality: Unique features, innovative approaches, and personal touches.
Code Quality: Cleanliness, organization, and use of best practices.

Happy hacking and we look forward to seeing your amazing portfolio websites!

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mercy Muthoni - Portfolio</title>
    <link rel="stylesheet" href="port.css">
  <style>
    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5em;
}

header p {
    margin: 10px 0;
    font-size: 1.2em;
}

.contact-info a {
    color: #fff;
    text-decoration: none;
    margin: 0 10px;
    font-size: 25px;
}

.contact-info a:hover {
    text-decoration: underline;
}

section {
    padding: 20px;
    margin: 0 auto;
    max-width: 800px;
}

h2 {
    color: #333;
    border-bottom: 2px solid #333;
    padding-bottom: 10px;
    font-size: 2em;
}

.project, .job, .degree {
    background-color: #fff;
    margin: 20px 0;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

.project h3, .job h3, .degree h3 {
    margin-top: 0;
}

.project p, .job p, .degree p {
    margin: 10px 0;
}

.project img {
    max-width: 100%;
    height: auto;
    border: 1px solid #ddd;
    border-radius: 5px;
    margin-top: 10px;
}

.links a {
    color: #007BFF;
    text-decoration: none;
    margin-right: 10px;
}

.links a:hover {
    text-decoration: underline;
}

ul {
    list-style-type: none;
    padding: 0;
}

ul li {
    background: #fff;
    margin: 5px 0;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}

  </style>
</head>
<body>
    <header>
        <h1>MERCY WANJIRU MUTHONI</h1>
        <p>BIO: A passionate developer with experience in web development and software engineering.</p>
        <div class="contact-info">
            <a href="mailto:muthoniw058@gmail.com">My email</a> |
            <a href="https://www.linkedin.com/in/muthoni-wanjiru-271407252?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B32UVBjtGRS%2B4q6QqMjROcg%3D%3D">LinkedIn</a> |
            <a href="https://www.github.com/in/sonnie18">GitHub</a>
        </div>
    </header>
    
  <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="project">
            <h3>Project 1: WEEK-1-HTML SETUP</h3>
            <p>Project for setting up a basic HTML template for the Expense Tracker Application interface. Aim was understanding of web development fundamentals. This served as a foundational step in the development process and will provide you with hands-on experience in building web interfaces for real-world applications.</p>
            <img src="C:\Users\Mercy Wanjiru\Pictures\Screenshots\Screenshot (89).png" >
            <div class="links"> |
                <a href="https://github.com/Sonnie18/week-1-html-setup-Sonnie18.git">GitHub Repository</a>
            </div>
        </div>
        <div class="project">
            <h3>Project 2: MAY WEEK 2 SEMANTIC ELEMENTS</h3>
            <p>understanding how to use semanting elements and an introduction of css for web page creation.</p>
            <img src="C:\Users\Mercy Wanjiru\Pictures\Screenshots\Screenshot (90).png">
            <div class="links">
                <a href="https://github.com/Sonnie18/may-week-2-html-semantic-elements.git">GitHub Repository</a>
            </div>
        </div>
    </section>
    <section id="skills">
        <h2>Skills</h2>
        <h3>Technical Skills</h3>
        <ul>
            <li>Python</li>
            <li>JavaScript</li>
            <li>HTML & CSS</li>
            <li>Java</li>
        </ul>
        <h3>Non-Technical Skills</h3>
        <ul>
            <li>Communication</li>
            <li>Team Collaboration</li>
            <li>Project Management</li>
        </ul>
    </section>
    
 <section id="experience">
        <h2>Experience</h2>
        <div class="job">
            <h3>Teaching</h3>
            <p>Ruai Junior Center Academy | September 2023 - January 2024</p>
            <p>I took playgruop class along side another teacher. We managed to make almost half of the class achieve to make </p>
        </div>
        </section>
    
  <section id="education">
        <h2>Education</h2>
        <div class="degree">
            <h3>Bachelor of Science in Information Technology</h3>
            <p>Kabarak University | 2022 - present</p>
            <p>At Kabarak university I am a member of the St John's Ambulance club where i learnt first aid and participated in a cmpetion which took us to nationals. I am also a member a the google developers club. Where I have learnt some coding skills i lnaguages such as java,javacript and python. I am currentyl participating in the ICP hackathon progrom where we learn creating a html website using Motoko.</p>
        </div>
    </section>
    
   <footer>
        <p>&copy; 2024 MERCY WANJIRU MUTHONI. All rights reserved.</p>
    </footer>
</body>
</html>

