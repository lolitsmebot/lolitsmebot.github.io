<!DOCTYPE html>
<html lang="fr">

<head>

<meta charset="UTF-8">

<!-- ✅ RESPONSIVE MOBILE IMPORTANT -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Haguenau Sharks</title>

<style>

body{
margin:0;
font-family:Arial, Helvetica, sans-serif;
background:#000;
color:white;
overflow-x:hidden;
}

/* CONTAINER CENTRAL */
.container{
max-width:1200px;
margin:auto;
padding:20px;
}

/* HEADER */
header{
display:flex;
justify-content:space-between;
align-items:center;
flex-wrap:wrap;
padding:15px 0;
border-bottom:2px solid red;
}

.logo{
height:70px;
}

nav{
display:flex;
gap:20px;
flex-wrap:wrap;
}

nav a{
color:white;
text-decoration:none;
font-weight:bold;
}

/* HERO */
.hero{
text-align:center;
padding:80px 0;
}

.hero h1{
font-size:clamp(40px,8vw,90px);
color:red;
margin:0;
}

/* SECTION JOUEURS */
.players{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:20px;
}

.player{
background:#111;
border-radius:12px;
padding:20px;
text-align:center;
transition:0.3s;
}

.player:hover{
transform:translateY(-6px);
background:#181818;
}

/* MOBILE */
@media(max-width:700px){

header{
justify-content:center;
text-align:center;
}

nav{
justify-content:center;
margin-top:10px;
}

.hero{
padding:40px 0;
}

}

</style>

</head>

<body>

<div class="container">

<header>

<img src="LOGO SHARKS.png" class="logo">

<nav>
<a href="#">Accueil</a>
<a href="#">Joueurs</a>
<a href="#">Classement</a>
<a href="#">News</a>
</nav>

</header>

</div>

<section class="hero container">

<h1>HAGUENAU SHARKS</h1>

</section>

<section class="container">

<div class="players">

<div class="player">Alexandre Texier</div>
<div class="player">Alex Barré-Boulet</div>
<div class="player">Ty Ronning</div>
<div class="player">Daniel Carr</div>
<div class="player">Pierre-Édouard Bellemare</div>
<div class="player">Evan Barratt</div>
<div class="player">Alexandre Grenier</div>
<div class="player">Philippe Maillet</div>
<div class="player">Sacha Treille</div>
<div class="player">Tim Bozon</div>
<div class="player">Louis Boudon</div>
<div class="player">Justin Addamo</div>

</div>

</section>

</body>
</html>
