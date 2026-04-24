# Ex01 Portfolio
## Date: 24-04-2026

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
index.html
```
<!DOCTYPE html>
<html>
<head>
<title>Home | Adarsh</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<nav>
    <h2>Adarsh Chowdary R</h2>
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="projects.html">Projects</a></li>
        <li><a href="contact.html">Contact</a></li>
    </ul>
</nav>
</header>

<div class="container">

<section class="hero">

    <img src="adarsh.jpeg" alt="Profile" class="profile-img">

    <h1>Java Full Stack Developer</h1>
    <p>Building scalable and efficient web applications using Java technologies</p>

    <a href="projects.html" class="btn">View My Work</a>
</section>

<section>
    <h2>Welcome</h2>
    <p>
        I am a passionate Java Full Stack Developer with strong backend skills and experience 
        in building responsive web applications using Java technologies.
    </p>
</section>

</div>

<footer>
    <p>© 2026 Adarsh. All rights reserved.</p>
</footer>

</body>
</html>
```
about.html
```
<!DOCTYPE html>
<html>
<head>
<title>About | Adarsh</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<nav>
    <h2>Adarsh Chowdary R</h2>

    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li> <!-- added -->
        <li><a href="projects.html">Projects</a></li>
        <li><a href="contact.html">Contact</a></li>
    </ul>
</nav>
</header>

<div class="container">

<section>
    <h2>About Me</h2>
    <p>
        I am a passionate Java Full Stack Developer with strong backend skills and experience 
        in building responsive web applications using Java technologies. I enjoy working on 
        challenging projects and continuously improving my skills to create efficient and 
        user-friendly applications.
    </p>


    <p>
        I am highly interested in developing real-world applications, learning new technologies, 
        and enhancing my problem-solving abilities. I am always eager to collaborate, take on new 
        challenges, and grow as a professional full stack developer.
    </p>
</section>

<section>
    <h2>Skills</h2>
    <div class="skills">
        <span>Java</span>
        <span>Spring Boot</span>
        <span>JDBC</span>
        <span>Servlets</span>
        <span>JSP</span>
        <span>SQL</span>
        <span>HTML</span>
        <span>CSS</span>
        <span>JavaScript</span>
    </div>
</section>

</div>

<footer>
    <p>© 2026 Adarsh. All rights reserved.</p>
</footer>

</body>
</html>
```

projects.html
```
<!DOCTYPE html>
<html>
<head>
<title>Projects | Adarsh</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<nav>
    <h2>Adarsh Chowdary R</h2>
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
    </ul>
</nav>
</header>

<div class="container">

<section>
    <h2>Projects</h2>

    <p><b>Java E-Commerce Web Application:</b></p>
    <p>
        Developed a full stack e-commerce application using Spring Boot and SQL. 
        The system includes user authentication, product listing, and order management.
    </p>
    <ul>
        <li>User login and registration</li>
        <li>Product catalog and cart system</li>
        <li>Order processing with database integration</li>
    </ul>
    <p><b>Technologies:</b> Java, Spring Boot, JDBC, SQL, HTML, CSS</p>

    <br>

    <p><b>Student Management System:</b></p>
    <p>
        Built a web-based system using JSP and Servlets to manage student records efficiently.
    </p>
    <ul>
        <li>Add, update, delete, and view student details</li>
        <li>Database integration using JDBC</li>
        <li>Simple and user-friendly interface</li>
    </ul>
    <p><b>Technologies:</b> Java, JSP, Servlets, JDBC, MySQL, HTML, CSS</p>

</section>

</div>

<footer>
    <p>© 2026 Adarsh. All rights reserved.</p>
</footer>

</body>
</html>
```

contact.html
```
<!DOCTYPE html>
<html>
<head>
<title>Contact | Adarsh</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<nav>
    <h2>Adarsh Chowdary R</h2>
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="projects.html">Projects</a></li>
    </ul>
</nav>
</header>

<div class="container">

<section>
    <h2>Contact</h2>

    <p>Email: reddineniadarsh7781@gmail.com</p>
    <p>Phone: 9381230271</p>

    <p>
        GitHub: <a href="https://github.com/Adarsh-2656" target="_blank">github.com</a><br>
        LinkedIn: <a href="https://www.linkedin.com/in/adarsh-reddineni/" target="_blank">linkedin.com</a>
    </p>

    <!-- Highlighted Section -->
    <div class="highlight-box">
        <p>
            I am open to internships, entry-level opportunities, and collaborations in the field of 
            Java Full Stack Development. Feel free to reach out if you have any opportunities or projects 
            where I can contribute and grow as a developer.
        </p>

        <p>
            I look forward to connecting and working on exciting and meaningful projects.
        </p>
    </div>

</section>

</div>

<footer>
    <p>© 2026 Adarsh. All rights reserved.</p>
</footer>

</body>
</html>
```

style.css
```
body{
    font-family: Arial;
    margin:0;
    background: linear-gradient(120deg,#0f2027,#203a43,#2c5364);
    color:#333;

    display:flex;
    flex-direction:column;
    min-height:100vh;
}

header{
    background: linear-gradient(135deg,#a8ff78,#78ffd6);
    padding:20px;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

nav ul{
    display:flex;
    list-style:none;
    gap:20px;
}

nav a{
    color:black;
    text-decoration:none;
    font-weight:bold;
}

.container{
    width:80%;
    margin:auto;
    flex:1;
}

section{
    background:white;
    margin:20px 0;
    padding:20px;
    border-radius:10px;
}

h1, h2, h3{
    color:black;
    font-weight:bold;
}

.hero{
    text-align:center;
    color:white;
    background: linear-gradient(135deg,#667eea,#764ba2);
    padding:60px 20px;
    border-radius:10px;
}

.hero h1{
    font-size:2.5rem;
    margin-bottom:10px;
}

.hero p{
    font-size:1.2rem;
    margin-bottom:20px;
}

.btn{
    display:inline-block;
    background:white;
    color:#667eea;
    padding:10px 20px;
    border-radius:5px;
    text-decoration:none;
    font-weight:bold;
}

.profile-img{
    width:150px;
    height:150px;
    border-radius:50%;
    object-fit:cover;
    display:block;
    margin:0 auto 20px;
    border:4px solid white;
}

.skills span{
    display:inline-block;
    background:#11998e;
    color:white;
    padding:6px 12px;
    margin:5px;
    border-radius:15px;
}

.highlight-box{
    background:#e6fffa;
    border-left:5px solid #11998e;
    padding:15px;
    margin-top:20px;
    border-radius:8px;
}

footer{
    background:#111;
    color:white;
    text-align:center;
    padding:15px;
}
```
## OUTPUT
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d8b0ad9e-7f3c-4c47-a56d-0570cae2a5f0" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c5496310-6b11-4539-956e-e4fbd0ec350e" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/884b3cd6-4b48-416a-bd9a-46cb0fbd6664" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4ea749fe-3109-4d8e-9c52-c007e872d4e0" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
