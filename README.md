<!DOCTYPE html>
<html>
<head>
  <title>Portfolio</title>
  <style>
    body {
      font-family: Roboto;
      margin: 0;
      padding: 0;
      background-color: #f3f4f5;
    }
    header {
      
    background-color: #002244; /* Darker blue */
    color: white;
    text-align: center;
    padding: 1.5rem;
    box-shadow: 0 4px 6px rgba(0,0,0,0.2);


    }
    section {
      margin: 20px;
    }
footer {
      background-color: #002244; /* Darker blue */
    color: white;
    text-align: center;
    padding: 1.5rem;
    box-shadow: 0 4px 6px rgba(0,0,0,0.2);

    }
form {
    max-width: 400px;
    margin: 1%;
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

input, textarea {
    width: 95%;
    padding: 10px;
    margin: 5px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
}

input[type="submit"] {
    background-color: #255;
    color: white;
    border: none;
    cursor: pointer;
}



</style>
</head>
<body>

<header>
<h1>Welcome to the my Portfolio</h1>
</header>

<h3>About Me</h3>
<p>I'm Kratika.Kamble.I'm passionate in web designing and currently I'm learning HTML,CSS,Javascript.I'm interested in creating the website's.</p>

<h3>Additional Skills</h3>
<ul>
<li>Good at Communication</li>
<li>Strong at Basic Coding using C programing language</li>
<li>Strong at Basic Coding using JAVA programing language</li>
<li>HTML</li>
<li>CSS</li>
<li>Teamwork Ability</li>
<li>Leadership Quality</li>
</ul>

<h3>Project's</h3>
<ul>
<li><a href="https://github.com/KratikaKamble/resume_html/blob/main/resume.html" target="_blank">Resume Project</a></li>
<li><a href="https://github.com/KratikaKamble/register_html/blob/main/register.html" target="_blank">Registration Project</a></li>
</ul>

<h3>LinkedIn Profile</h3>
<ul>
<li><a href="https://www.linkedin.com/in/kratitanu-kamble-12264632a/" target="_blank">LinkedIn Profile</a></li>
</ul>

<h3>Contact Me</h3>
<form action="#" method="POST">
    <label for="name">Name:</label><br>
    <input type="text" id="name" name="name" placeholder="Enter Name"required><br><br>
    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" placeholder="Example@gmail.com" required><br><br>
    <label for="message">Message:</label><br>
    <textarea id="message" name="message" rows="4" placeholder="Enter message"required></textarea><br><br>
    <input type="submit" value="Send Message"><br><br>
  </form>

<footer>
<h4>Thank You for visiting website#2025</h4>
</footer>

</body>
</html>
