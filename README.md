<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Muhammed Shabeeeh PK | Portfolio</title>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#0f172a;
    color:white;
    line-height:1.6;
}

header{
    background:linear-gradient(135deg,#06b6d4,#2563eb);
    padding:60px 20px;
    text-align:center;
}

header h1{
    font-size:42px;
}

header h2{
    color:#e0f2fe;
    margin:10px 0;
    font-size:26px;
}

header p{
    font-size:18px;
}

nav{
    background:#111827;
    padding:15px;
    text-align:center;
    position:sticky;
    top:0;
    z-index:1000;
}

nav a{
    color:white;
    margin:0 15px;
    text-decoration:none;
    font-weight:bold;
    transition:0.3s;
}

nav a:hover{
    color:#38bdf8;
}

section{
    padding:60px 10%;
}

.section-title{
    font-size:32px;
    color:#38bdf8;
    margin-bottom:25px;
    text-transform:uppercase;
    letter-spacing:2px;
    border-left:6px solid #22d3ee;
    padding-left:15px;
}

.card{
    background:#1e293b;
    padding:25px;
    border-radius:14px;
    margin-top:20px;
    box-shadow:0 0 15px rgba(0,0,0,0.4);
}

.skills{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}

.skills ul{
    list-style:none;
}

.skills li{
    padding:8px 0;
}

.project{
    margin-bottom:25px;
}

.project h3{
    color:#22d3ee;
    margin-bottom:12px;
}

footer{
    text-align:center;
    padding:25px;
    background:#111827;
    margin-top:40px;
}

.icon{
    color:#38bdf8;
    margin-right:8px;
}
</style>
</head>

<body>

<header>
<h1><i class="fa-solid fa-chart-line"></i> Muhammed Shabeeeh PK</h1>
<h2>Data Analyst Student</h2>
<p>Turning data into insights and learning ML every day</p>
</header>

<nav>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</nav>

<section id="about">
<h2 class="section-title">About Me</h2>

<div class="card">
<p>
I started my journey with a strong interest in technology and problem-solving.
Over time, I became interested in working with data and understanding how information can be used to make better decisions.
This motivated me to begin learning tools like Python, Excel, SQL, and Power BI.
As a Data Analyst student, I continuously improve my skills through projects and practical learning.
</p>

<br>

<p>
I chose Data Science because it combines technology, mathematics, and business problem-solving.
It allows me to turn raw data into useful insights that help organizations make smart decisions.
I enjoy finding patterns in data, creating reports, and solving real-world problems.
</p>

<br>

<p>
Currently learning Data Analysis, Data Visualization, Machine Learning basics, and database management.
Improving my skills in Pandas, NumPy, Matplotlib, SQL, and Power BI.
</p>
</div>
</section>

<section id="skills">
<h2 class="section-title">My Skills</h2>

<div class="skills">

<div class="card">
<h3><i class="fa-solid fa-code icon"></i>Programming</h3>
<ul>
<li>Python</li>
<li>SQL</li>
<li>Java</li>
<li>HTML/CSS</li>
</ul>
</div>

<div class="card">
<h3><i class="fa-solid fa-chart-column icon"></i>Data Analysis</h3>
<ul>
<li>Data Cleaning</li>
<li>EDA</li>
<li>Visualization</li>
<li>Statistics</li>
<li>Dashboard Creation</li>
</ul>
</div>

<div class="card">
<h3><i class="fa-solid fa-laptop-code icon"></i>Tools</h3>
<ul>
<li>Excel</li>
<li>Power BI</li>
<li>Google Colab</li>
<li>MySQL</li>
<li>GitHub</li>
</ul>
</div>

<div class="card">
<h3><i class="fa-solid fa-robot icon"></i>Machine Learning</h3>
<ul>
<li>Regression</li>
<li>Classification</li>
<li>Scikit-learn</li>
</ul>
</div>

</div>
</section>

<section id="projects">
<h2 class="section-title">My Projects</h2>

<div class="card project">
<h3><i class="fa-solid fa-user-graduate icon"></i> Student Performance Prediction</h3>

<p><b>Problem:</b> Predict pass or fail using attendance, study hours, and scores.</p>

<p><b>Dataset:</b> Student Performance Dataset</p>

<p><b>Approach:</b></p>
<ul>
<li>Handled missing values</li>
<li>Encoded categories</li>
<li>Performed EDA</li>
<li>Train/Test Split</li>
</ul>

<p><b>Model:</b> Logistic Regression / Random Forest</p>

<p><b>Result:</b> Good prediction accuracy.</p>

<p><b>Learning:</b> Classification, feature selection, evaluation metrics.</p>

<p><b>GitHub:</b> Add Link</p>
</div>

</section>

<section id="contact">
<h2 class="section-title">Contact Me</h2>

<div class="card">
<p><i class="fa-solid fa-envelope icon"></i> muhammedshabeehgafoor@gmail.com</p>
<p><i class="fa-brands fa-github icon"></i> github.com/yourusername</p>
<p><i class="fa-brands fa-linkedin icon"></i> linkedin.com/in/yourprofile</p>
<p><i class="fa-solid fa-location-dot icon"></i> Kerala, India</p>
</div>

</section>

<footer>
© 2026 Muhammed Shabeeeh PK | Portfolio
</footer>

</body>
</html>
