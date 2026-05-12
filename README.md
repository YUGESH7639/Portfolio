# Ex01 Portfolio
## Date: 12.05.2026
## NAME : YUGESH M
## REG.NO:212224040376

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM

```


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Personal Portfolio</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#0f172a;
    color:white;
}

/* HEADER */
header{
    background:#1e293b;
    padding:20px 50px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

header h1{
    color:#38bdf8;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
    transition:0.3s;
}

nav a:hover{
    color:#38bdf8;
}

/* HERO */
.hero{
    display:flex;
    justify-content:space-around;
    align-items:center;
    padding:80px 50px;
}

.hero-text h2{
    font-size:45px;
}

.hero-text span{
    color:#38bdf8;
}

.hero-text p{
    margin:20px 0;
    max-width:500px;
    line-height:1.6;
}

.btn{
    padding:12px 25px;
    border:none;
    background:#38bdf8;
    color:black;
    border-radius:30px;
    cursor:pointer;
    font-weight:bold;
}

.hero img{
    width:250px;
    height:250px;
    border-radius:20px;
    object-fit:cover;
    box-shadow:0 0 25px #38bdf8;
}

/* SECTION */
section{
    padding:60px 50px;
}

h2{
    text-align:center;
    margin-bottom:40px;
    color:#38bdf8;
}

/* SKILLS */
.skills{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
    gap:20px;
}

.skill-box{
    background:#1e293b;
    padding:20px;
    text-align:center;
    border-radius:15px;
    transition:0.3s;
}

.skill-box:hover{
    transform:scale(1.05);
    background:#38bdf8;
    color:black;
}

/* PROJECTS */
.projects{
    display:flex;
    gap:20px;
    flex-wrap:wrap;
}

.project{
    flex:1;
    min-width:250px;
    background:#1e293b;
    padding:20px;
    border-radius:15px;
    transition:0.3s;
}

.project:hover{
    transform:translateY(-10px);
}

/* CONTACT */
.contact-form{
    max-width:600px;
    margin:auto;
}

.contact-form input,
.contact-form textarea{
    width:100%;
    padding:12px;
    margin:10px 0;
    border:none;
    border-radius:10px;
}

.contact-form button{
    width:100%;
    padding:12px;
    background:#38bdf8;
    border:none;
    border-radius:10px;
    font-weight:bold;
    cursor:pointer;
}

/* FOOTER */
footer{
    text-align:center;
    padding:20px;
    background:#1e293b;
}
</style>
</head>
<body>

<header>
    <h1>My Portfolio</h1>
    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<!-- HERO -->
<div class="hero">
    <div class="hero-text">
        <h2>Hello, I'm <span>Yugesh M</span></h2>
        <p>
            A passionate developer who loves creating responsive websites
            and learning modern technologies.
        </p>
        <button class="btn">Hire Me</button>
    </div>
    <img src="212224040376.png" alt="Profile">
</div>

<!-- ABOUT -->
<section id="about">
    <h2>About Me</h2>
    <p style="text-align:center; max-width:800px; margin:auto;">
        I am a creative web developer with knowledge in HTML, CSS,
        Java, and C programming. I enjoy building clean and interactive
        websites with modern design.
    </p>
</section>

<!-- SKILLS -->
<section id="skills">
    <h2>My Skills</h2>
    <div class="skills">
        <div class="skill-box">HTML</div>
        <div class="skill-box">CSS</div>
        <div class="skill-box">Java</div>
        <div class="skill-box">C</div>
        <div class="skill-box">JavaScript</div>
        <div class="skill-box">UI/UX</div>
    </div>
</section>

<!-- PROJECTS -->
<section id="projects">
    <h2>Projects</h2>
    <div class="projects">
        <div class="project">
            <h3>Online Quiz App</h3>
            <p>Interactive quiz platform using HTML/CSS/JS.</p>
        </div>

        <div class="project">
            <h3>Library Management</h3>
            <p>System to manage books and student records.</p>
        </div>

        <div class="project">
            <h3>E-Commerce Website</h3>
            <p>Responsive shopping website with stylish design.</p>
        </div>
    </div>
</section>

<!-- CONTACT -->
<section id="contact">
    <h2>Contact Me</h2>
    <div class="contact-form">
        <input type="text" placeholder="Enter Name">
        <input type="email" placeholder="Enter Email">
        <textarea rows="5" placeholder="Your Message"></textarea>
        <button>Send Message</button>
    </div>
</section>

<footer>
    <p>© 2026 Yugesh | All Rights Reserved</p>
</footer>

</body>
</html>



```

## OUTPUT
<img width="1920" height="1200" alt="Screenshot (145)" src="https://github.com/user-attachments/assets/6fa0e498-aaec-49bc-84bc-06f17ebfc421" />

<img width="1920" height="1200" alt="Screenshot (146)" src="https://github.com/user-attachments/assets/41b6e193-561d-4044-b1f6-76f01a5b2a0d" />

<img width="1920" height="1200" alt="Screenshot (147)" src="https://github.com/user-attachments/assets/818181f1-1041-4048-ba48-4dfce9dc83c2" />



## RESULT

The program for creating Portfolio using HTML and CSS is executed successfully.
