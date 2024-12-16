<!DOCTYPE html> 
<html lang="en"> 
<head> 
<meta charset="UTF-8"> 
<meta name="viewport" content="width=device-width, initial-scale=1.0"> 
<title>Personal Portfolio</title> 
<link rel="stylesheet" href="style.css"> 
  <style>body { 
    margin: 0; 
    font-family: Arial, sans-serif; 
    line-height: 1.6; 
    color: #333; 
} 
body{ 
    background: #e0f04d; 
} 
 
a { 
    text-decoration: none; 
    color: #007BFF; 
} 
 
.container { 
    width: 90%; 
    max-width: 1200px; 
    margin: 0 auto; 
} 
 
header { 
    background: #333; 
    color: #fff; 
    padding: 1rem 0; 
} 
 
header h1 { 
    margin: 0; 
    text-align: center; 
} 
 
.nav-links { 
    display: flex; 
    justify-content: center; 
    list-style: none; 
    padding: 0; 
} 
 
.nav-links li { 
    margin: 0 15px; 
} 
 
.nav-links a { 
    color: #fff; 
    font-weight: bold; 
} 
 
/* Hero Section */ 
#hero { 
    background: url('hero-image.jpg') no-repeat center center/cover; 
    color: #e40a0a; 
    text-align: center; 
    padding: 5rem 1rem; 
} 
 
#hero h2 { 
    font-size: 2.5rem; 
    margin: 0 0 1rem; 
} 
 
.btn { 
    display: inline-block; 
    padding: 10px 20px; 
    background: #007BFF; 
    color: #fff; 
    border-radius: 5px; 
    margin-top: 10px; 
} 
 
.btn:hover { 
    background: #0056b3; 
} 
 
/* Section Styles */ 
.section { 
    padding: 3rem 1rem; 
    text-align: center; 
} 
 
.portfolio-grid { 
    display: grid; 
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); 
    gap: 20px; 
} 
 
.portfolio-item { 
    border: 1px solid #ddd; 
    border-radius: 5px; 
    overflow: hidden; 
    background: #fff; 
} 
 
.portfolio-item img { 
    max-width: 100%; 
} 
 
.portfolio-item h3 { 
    margin: 1rem 0 0.5rem; 
} 
 
form { 
    display: flex; 
    flex-direction: column; 
    gap: 10px; 
    max-width: 600px; 
    margin: 0 auto; 
} 
 
form input, form textarea, form button { 
    width: 100%; 
    padding: 10px; 
    font-size: 1rem; 
} 
 
form button { 
    background: #007BFF; 
    color: #fff; 
    border: none; 
    border-radius: 5px; 
    cursor: pointer; 
} 
 
form button:hover { 
    background: #0056b3; 
} 
 
/* Footer */ 
footer { 
    background: #333; 
    color: #fff; 
    text-align: center; 
padding: 1rem 0; 
}</style>
</head> 
<body> 
<header> 
        <div class="container"> 
            <h1>Ankush</h1> 
            <nav> 
                <ul class="nav-links"> 
                    <li><a href="#about">About</a></li> 
                    <li><a href="#portfolio">Portfolio</a></li> 
                    <li><a href="#contact">Contact</a></li> 
                </ul> 
            </nav> 
        </div> 
    </header> 
 
    <section id="hero"> 
        <div class="hero-content"> 
            <h2>Welcome to My Portfolio</h2> 
            <p>I'm a web developer passionate about creating beautiful and functional 
websites.</p> 
            <a href="#portfolio" class="btn">View My Work</a> 
        </div> 
    </section> 
 
    <section id="about" class="section"> 
        <div class="container"> 
            <h2><u>About Me</u></h2> 
            <p>Hello! I'm Ankush, a self-taught developer with a love for crafting seamless user 
experiences.</p> 
        </div> 
    </section> 
 
    <section id="portfolio" class="section"> 
        <div class="container"> 
            <h2><u>Portfolio</u></h2> 
            <div class="portfolio-grid"> 
                <div class="portfolio-item"> 
                    <img src="project1.jpg" alt="Project 1"> 
                    <h3>Project One</h3> 
                    <p>A description of the project.</p> 
                </div> 
                <div class="portfolio-item"> 
                    <img src="project2.jpg" alt="Project 2"> 
                    <h3>Project Two</h3> 
                    <p>A description of the project.</p> 
                </div> 
                <!-- Add more portfolio items as needed --> 
            </div> 
        </div> 
    </section> 
 
    <section id="contact" class="section"> 
        <div class="container"> 
            <h2><u>Contact Me</u></h2> 
            <form> 
                <input type="text" placeholder="Your Name" required> 
                <input type="email" placeholder="Your Email" required> 
                <textarea placeholder="Your Message" required></textarea> 
                <button type="submit">Send Message</button> 
            </form> 
        </div> 
    </section> 
 
    <footer> 
        <div class="container"> 
            <p>&copy; 2024 Ankush.  All Rights Reserved.</p> 
        </div> 
    </footer> 
</body> 
</html>
