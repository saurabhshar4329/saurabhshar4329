<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Saurabh Sharma | Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:#0f172a;
    color:white;
    line-height:1.6;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
}

header{
    background:#1e293b;
    padding:20px 0;
    position:sticky;
    top:0;
    z-index:1000;
}

header .container{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    color:#38bdf8;
    font-size:28px;
}

nav ul{
    display:flex;
    list-style:none;
    gap:25px;
}

nav ul li a{
    color:white;
    text-decoration:none;
    transition:.3s;
}

nav ul li a:hover{
    color:#38bdf8;
}

.hero{
    height:90vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
}

.hero h1{
    font-size:3.5rem;
}

.hero span{
    color:#38bdf8;
}

.hero p{
    margin:15px 0;
    color:#cbd5e1;
    font-size:1.1rem;
}

.btn{
    display:inline-block;
    background:#38bdf8;
    color:#000;
    padding:12px 28px;
    text-decoration:none;
    border-radius:8px;
    font-weight:600;
    margin-top:10px;
}

.btn:hover{
    transform:scale(1.05);
}

section{
    padding:80px 0;
}

.section-title{
    text-align:center;
    font-size:2.3rem;
    color:#38bdf8;
    margin-bottom:40px;
}

.about{
    text-align:center;
    max-width:800px;
    margin:auto;
}

.about p{
    color:#cbd5e1;
    margin-bottom:20px;
}

.skills-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}

.skill-card{
    background:#1e293b;
    padding:25px;
    border-radius:12px;
    text-align:center;
    transition:.3s;
}

.skill-card:hover{
    transform:translateY(-8px);
}

.skill-card h3{
    color:#38bdf8;
    margin-bottom:10px;
}

.projects{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:20px;
}

.project-card{
    background:#1e293b;
    padding:25px;
    border-radius:12px;
    transition:.3s;
}

.project-card:hover{
    transform:translateY(-8px);
}

.project-card h3{
    color:#38bdf8;
    margin-bottom:10px;
}

.contact{
    text-align:center;
}

.contact p{
    margin:15px 0;
}

.contact a{
    color:#38bdf8;
    text-decoration:none;
}

footer{
    background:#1e293b;
    text-align:center;
    padding:20px;
    margin-top:40px;
}

@media(max-width:768px){

header .container{
    flex-direction:column;
}

nav ul{
    margin-top:15px;
    flex-wrap:wrap;
    justify-content:center;
}

.hero h1{
    font-size:2.2rem;
}

}

</style>
</head>

<body>

<header>
    <div class="container">
        <h2 class="logo">Saurabh Sharma</h2>

        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </div>
</header>

<section class="hero">
    <div>
        <h1>Hello, I'm <span>Saurabh Sharma</span></h1>

        <p>
            B.Tech Computer Science Student <br>
            Aspiring Software Engineer
        </p>

        <a href="#contact" class="btn">Connect With Me</a>
    </div>
</section>

<section id="about">
    <div class="container">
        <h2 class="section-title">About Me</h2>

        <div class="about">
            <p>
                I am a Third-Year B.Tech Computer Science student at
                Galgotias University with a strong interest in Software
                Development and Problem Solving.
            </p>

            <p>
                Currently learning Java, DSA, SQL, HTML, CSS and building
                real-world projects to strengthen my development skills.
            </p>
        </div>
    </div>
</section>

<section id="skills">
    <div class="container">
        <h2 class="section-title">Technical Skills</h2>

        <div class="skills-grid">

            <div class="skill-card">
                <h3>Java</h3>
                <p>OOP, Collections, JDBC</p>
            </div>

            <div class="skill-card">
                <h3>HTML & CSS</h3>
                <p>Responsive Web Design</p>
            </div>

            <div class="skill-card">
                <h3>SQL</h3>
                <p>Database Management</p>
            </div>

            <div class="skill-card">
                <h3>DSA</h3>
                <p>Problem Solving & Algorithms</p>
            </div>

            <div class="skill-card">
                <h3>Git & GitHub</h3>
                <p>Version Control</p>
            </div>

            <div class="skill-card">
                <h3>VS Code</h3>
                <p>Development Environment</p>
            </div>

        </div>
    </div>
</section>

<section id="projects">
    <div class="container">

        <h2 class="section-title">Projects</h2>

        <div class="projects">

            <div class="project-card">
                <h3>Expense Tracker</h3>
                <p>
                    Manage and monitor daily expenses using a
                    user-friendly interface.
                </p>
            </div>

            <div class="project-card">
                <h3>Weather Dashboard</h3>
                <p>
                    Displays live weather information using APIs.
                </p>
            </div>

            <div class="project-card">
                <h3>URL Shortener</h3>
                <p>
                    Java-based web application for shortening long URLs.
                </p>
            </div>

        </div>

    </div>
</section>

<section id="contact">
    <div class="container">

        <h2 class="section-title">Contact Me</h2>

        <div class="contact">

            <p>📧 Email: sharmasaurabh4169@gmail.com</p>

            <p>
                💼 LinkedIn:
                <a href="https://linkedin.com" target="https://l1nk.dev/8l7wq4c">
                    View Profile
                </a>
            </p>

            <p>
                🐱 GitHub:
                <a href="https://github.com/saurabhshar4329" target="_blank">
                    github.com/saurabhshar4329
                </a>
            </p>

            <p>
                📸 Instagram:
                <a href="https://instagram.com" target="https://l1nk.dev/it6cajo">
                    @saurabh_shamra_oo52
                </a>
            </p>

        </div>

    </div>
</section>

<footer>
    <p>© 2026 Saurabh Sharma | All Rights Reserved</p>
</footer>

</body>
</html>
