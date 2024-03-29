<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portfolio</title>
<style>
  /* Navbar styling */
  .navbar {
    background-color: #ffffff;
    overflow: hidden;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 50px;
  }

  .navbar-brand {
    font-size: 30px;
    color: #000000;
    text-decoration: none;
    text-align: center;
    display: flex;
    align-items: center;
  }

  .navbar-brand img {
    height: 80px;
    width: 80px;
    margin-right: 10px;
  }

  .navbar-menu {
    display: flex;
    justify-content: flex-end;
  }

  .navbar-menu a {
    color: #110202;
    text-align: center;
    padding: 20px 30px;
    text-decoration: none;
  }

  .navbar-menu a:hover {
    background-color: #e051d4;
  }

  .content-wrapper {
    display: flex;
    justify-content: space-between;
    padding: 20px;
    padding-top: 50px; 
    padding-bottom: 50px;
    background-color: #518fe0;
  }
   
  .content-left h1 {
    animation: slideIn 2s; 
  }

  @keyframes slideIn {
    from {
      transform: translateX(-100%);
      opacity: 0;
    }
    to {
      transform: translateX(0%);
      opacity: 1;
    }
  }
  .content-left {
    width: 60%;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .content-right {
    width: 35%;
  }

  .content-right img {
    width: 100%;
    height: auto;
    display: block;
  }

  .projects-wrapper {
    padding: 20px;
    background-color: #f4f4f4;
    margin-top: 20px;
    padding-top: 100px;
    padding-bottom: 100px;
  }

  .project {
    margin-bottom: 20px;
  }

  .project-title {
    font-weight: bold;
  }

  .project-description {
    color: #666;
  }

  
  .contact-info {
    padding: 20px;
    background-color: #518fe0;
    color: #fff;
    text-align: center;
  }

  .contact-info a {
    color: #fff;
    text-decoration: none;
    margin: 0 10px;
  }

  .contact-info img {
    height: 30px;
    width: 30px;
    margin-right: 10px;
  }

  .footer {
    background-color: #dd46b7;
    color: #fff;
    text-align: center;
    padding: 20px 0;
  }
</style>
</head>
<body>

<nav class="navbar">
  <a href="#" class="navbar-brand">
    <img src="logo.png" alt="Logo">Kashaf Irfan 
  </a>
  <div class="navbar-menu">
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<div id="about" class="content-wrapper">
  <div class="content-left">
    <h1>I'm Kashaf Irfan</h1>
    <p>I,a computer scientist, is a scholar who specializes in the academic study of computer science.
     I typically work on the theoretical side of computation. Although I can also focus my work and research on specific
     areas (such as algorithm and data structure development and design, software engineering, information theory,
      database theory, theoretical computer science, numerical analysis, programming language theory, compiler,
       computer graphics, computer vision, robotics, computer architecture, operating system), their foundation 
       is the theoretical study of computing from which these other fields derive. </p>
  </div>
  <div class="content-right">
    <img src="pic.jpeg" alt="Profile Picture">
  </div>
</div>

<div id="projects" class="projects-wrapper">
    <h1>My Projects</h1>
    <div class="project">
      <div class="project-title">An Event Management System</div>
      <div class="project-description">Utilizing relational database principles, our system ensures 
        streamlined data storage, retrieval, and manipulation, enhancing the efficiency and effectiveness 
        of event management processes.</div>
    </div>
    <div class="project">
      <div class="project-title">Potion Explosion Game</div>
      <div class="project-description">Implementing efficient memory allocation and 
        process synchronization, our project enhances the gaming experience by minimizing latency and maximizing
         system performance.</div>
    </div>
    <div class="project">
        <div class="project-title">Text-Editor</div>
        <div class="project-description">Implementing advanced data structures like linked lists and trees, our 
            project ensures fast and reliable text processing, enabling seamless editing experiences.</div>
      </div>
  </div>

  <div id="contact" class="contact-info">
    <a href=""><img src="insta.png" alt="Instagram Logo">@kashaf</a>
    <a href=""><img src="in.jpg" alt="LinkedIn Logo">abc_xyz</a>
    <span><img src="phone.png" alt="Phone Logo">Phone: +11111111111</span>
</div>

<div class="footer">
  Designed by Kashaf Irfan
</div>

</body>
</html>
