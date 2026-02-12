<!DOCTYPE html>
<html>
<head>
<title>Sedhuraman R - Portfolio</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body{
    margin:0;
    font-family: 'Segoe UI', sans-serif;
    background:#f4f6f8;
}

.container{
    display:flex;
    min-height:100vh;
}

.sidebar{
    width:230px;
    background:#2c3e50;
    color:#fff;
    padding:25px 15px;
}

.sidebar h2{
    text-align:center;
    margin-bottom:25px;
    font-size:20px;
}

.sidebar a{
    display:block;
    color:#ecf0f1;
    text-decoration:none;
    padding:8px 10px;
    margin:8px 0;
    border-radius:4px;
    font-size:14px;
}

.sidebar a:hover{
    background:#1abc9c;
}

.content{
    flex:1;
    padding:40px;
    max-width:900px;
    margin:auto;
}

.section{
    background:#fff;
    padding:25px;
    margin-bottom:25px;
    border-radius:8px;
    box-shadow:0 3px 8px rgba(0,0,0,0.08);
}

h1{
    margin-top:0;
    color:#2c3e50;
}

h2{
    color:#1abc9c;
    margin-bottom:12px;
}

ul{
    padding-left:20px;
}

p{
    line-height:1.6;
}

@media(max-width:768px){
    .container{flex-direction:column;}
    .sidebar{width:100%; text-align:center;}
    .content{padding:20px;}
}
</style>
</head>

<body>

<div class="container">

<div class="sidebar">
<h2>Sedhuraman R</h2>
<a href="#intro">Introduction</a>
<a href="#about">About Me</a>
<a href="#skills">Skills</a>
<a href="#project">Project</a>
<a href="#contact">Contact</a>
</div>

<div class="content">

<div id="intro" class="section">
<h1>Introduction</h1>
<p>I am Sedhuraman R, a first-year B.E. Computer Science Engineering student at Bannari Amman Institute of Technology.</p>
</div>

<div id="about" class="section">
<h2>About Me</h2>
<p>I am a Computer Science student with a strong interest in programming and technology. I am eager to learn new concepts and continuously improve my technical skills through practical learning.</p>
</div>

<div id="skills" class="section">
<h2>Skills</h2>
<ul>
<li>C Programming</li>
<li>HTML</li>
<li>CSS</li>
</ul>
</div>

<div id="project" class="section">
<h2>Project</h2>
<p><strong>Student Portfolio Website</strong><br>
Designed and developed a personal portfolio using HTML and CSS to showcase my profile and skills.</p>
</div>

<div id="contact" class="section">
<h2>Contact</h2>
<p>Email: sedhuramanr.cs25@bitsathy.ac.in</p>
<p>Phone: +91-9360193695</p>
</div>

</div>
</div>

</body>
</html>
