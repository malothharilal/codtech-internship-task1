# codtech-internship-task1
Name: MALOTH HARILAL
Company:CODETECH
Id :CT08DS495
Domain: FULLSTACK WEB DEVELOPMENT
Duration:dec 12th 2024 to jan 12th 2025

OVERVIEW OF THE PROJECT:
PROJECT:personal portfolio website

OBJECTIVE:

A personal portfolio is a collection of works or projects that showcase an individual's skills, experiences, achievements, and competencies, often used by professionals in fields like software development, design, writing, or other creative and technical professions. It serves as both a tool for self-promotion and a method of tracking personal development over time.


KEY Activities:

1. Initial Planning and Design

Decide on KeYS:
.Home Page: Introduction, tagline, and navigation.
.About Me: Personal information, experience, and goals.
.Projects or Work: Showcase of work with descriptions and links to live demos or code repositories.
.Blog or Articles: Optional section for content if you're sharing insights or tutorials.
.Contact: A form or details for getting in touch.

2. SETTING UP THE DEVELOPMENT ENVIRONMENT:
 
.Version Control: Initialize a Git repository for tracking changes. Create a GitHub repository to host the code.
.CSS Frameworks: Consider frameworks like Bootstrap or Tailwind CSS for faster styling.

TECHNOLOGIES USED:

HTML:HTML is the standard markup language used to create and design web pages.
CSS:Css used to control the presentation, layout, and design of HTML content.




<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-compatible" content="Ie=edge">
        <meta name="viewport" content="width=device-width,
        initial-scale=1.0">
        <title>personal portfolio website using html&css | codehal</title>
        <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
        <link rel="stylesheet" href="style.css">
    </head>
    
    <body>
        <nav class="navbar">
            <a href="#" class="logo">PORTFOLIO</a>
            <ul>
                <li><a href="active">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Portfolio</a></li>
                <li><a href="#">Service</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
        <section class="Home">
            <div class="Home-info">
                <h1>MALOTH HARILAL</h1>
                <h2> I'm a fullstack web developer</h2>
                <p> with a strong foundation in both front-end and back-end development.I am skilled in technologies such as HTML, CSS, JavaScript, React, Node.js, and various database like MySQL.I enjoy building responsive, user-friendly applications and solving complex problems across the development stack.With a focus on writing clean, efficient code,I aim to create seamless web experiences that meet user needs and business goals.I'm always eager to learn new technologies and improve my skills as I work on a variety of projects.</p>
                 <div class="btn-sci">
                    <a href="#" class="btn">Download cv</a>
                    <div class="sci">
                       <a href="#"><i class='bx bxl-github'></i></a>
                       <a href="#"><i class='bx bxl-linkedin'></i></a>
                       <a href="#"><i class='bx bxl-twitter'></i></a>
                       <a href="#"><i class='bx bxl-youtube'></i></a>
                       
                    </div>
                 </div>    

            </div>
            <div class="home-img">
              <div class="img-box">
                 <div class="img-item">
                  <img src="home.jpg" alt=">
                  
                </div>
             </div>
         </div>

        </section>

    </body>
</html>
