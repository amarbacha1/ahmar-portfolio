<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Syed Amar Portfolio</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial;
}

body{
background:#0f172a;
color:white;
}

header{
background:#020617;
padding:20px;
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
flex-wrap:wrap;
}

.logo{
color:#38bdf8;
font-size:22px;
font-weight:bold;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:15px;
}

nav ul li a{
color:white;
text-decoration:none;
font-size:14px;
}

.hero{
text-align:center;
padding:100px 20px;
}

.profile{
width:130px;
height:130px;
border-radius:50%;
object-fit:cover;
border:4px solid #38bdf8;
margin-bottom:20px;
}

.hero h1{
font-size:32px;
}

.hero span{
color:#38bdf8;
}

.hero p{
margin-top:10px;
font-size:16px;
}

.skills{
padding:60px 20px;
text-align:center;
}

.skills h2{
margin-bottom:30px;
}

.skills-container{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
gap:15px;
}

.card{
background:#1e293b;
padding:15px;
border-radius:8px;
}

.contact{
padding:60px 20px;
text-align:center;
}

.btn{
display:inline-block;
margin:10px;
padding:10px 20px;
background:#38bdf8;
color:black;
text-decoration:none;
border-radius:6px;
font-weight:bold;
}

.phone{
margin-top:15px;
}

footer{
text-align:center;
padding:20px;
background:#020617;
margin-top:40px;
}

</style>

</head>

<body>

<header>

<nav>

<div class="logo">Syed Amar</div>

<ul>
<li><a href="#">Home</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>

</header>

<section class="hero">

<img src="c:\Users\AMAR BACHA\Desktop\profile.jpg.jpeg" class="profile">

<h1>Hello I'm <span>Syed Amar</span></h1>

<p>Social Media Marketer | Front-End Web Developer | Graphic Designer</p>

</section>

<section id="skills" class="skills">

<h2>My Skills</h2>

<div class="skills-container">

<div class="card">Social Media Marketing</div>
<div class="card">Facebook Pages Creation</div>
<div class="card">MS Office</div>
<div class="card">CV Creation</div>
<div class="card">PowerPoint Slides</div>
<div class="card">Front End Web Development</div>
<div class="card">Graphic Design</div>
<div class="card">Video Editing</div>
<div class="card">Wedding Card Design</div>
<div class="card">CV Design</div>
<div class="card">Data Entry</div>
<div class="card">MS Word to PDF</div>

</div>

</section>

<section id="contact" class="contact">

<h2>Contact Me</h2>

<a class="btn" href="https://wa.me/923155176620">WhatsApp</a>

<a class="btn" href="mailto:amarbacha208@gmail.com">Send Email</a>

<p class="phone">Phone: 0315-5176620</p>

</section>

<footer>

<p>© 2026 Syed Amar Portfolio</p>

</footer>

</body>
</html>
