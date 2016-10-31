# PRACTICA-GP-1.3
Practica de desarrollo web gp 1.3
****************************************************************************************
practica.html
****************************************************************************************
<!DOCTYPE htmal>
<html lang="es">
<head> 
	<title>PRACTICA</title>
	<meta metacharset="utf-8">
	<link rel="stylesheet" type="text/css" href="css/estilos.css">
	<link rel="shourcut icon" type="image/x-icon" href="image/utpl.ico">
</head>
<body>
	<header>
    <h1>LOGO</h1>
		<aside id="buscador">
		<input type="text">
		</aside>
		</header>
	<nav>
		<a href="">INICIO</a>
		<a href="">SERVICIO</a>
		<a href="">CLIENTES</a>
		<a href="">CONTACTO</a>
	</nav>
	<main>
		<section id="contenedor">
			<h2>CONTENIDO</h2>
		</section>
		<aside id="modulos">
			<h3>MODULOS</h3>
		</aside>
	</main>
	<aside id="logos">
		<section id="logo1"></section>
		<section id="logo2"></section>
		<section id="logo3"></section>
		<section id="logo4"></section>
		<section id="logo5"></section>
	</aside>
	<footer>
		<h6>Derecho Reservados UTPL, by <a href="">@cavargas10</a></h6>
	</footer>
</body>
</html>

**********************************************************************
estilos.css
**********************************************************************
*{
	padding: 0;
	margin: 0;
}
body{
	background: #051B38;
	font-family: arial;
	color: #512A00;
}
header{
	width: 90%;
	margin: 0 auto;
	background: #143054;
	color: #7986CB;
}
header h1{
	display: inline-block;
	width: 30%;
	padding: 1em 1em;
	text-shadow: 3px 3px 5px #000;
}
header aside#buscador{
	display: inline-block;
	width: 60%;
	text-align: right;
}
nav{
	width:90%;
	margin: 0 auto;
	background: #4C688B;
	color: #373021;
	padding: 0.6em 0em;
	text-align: center;
}
nav a{
	text-decoration: none;
	padding: 0.6em 0.8em;
}
nav a:hover{
	background: #748BA7;
	color: #000;
}
main{
	width:90%;
	margin: 0 auto;
	background: #2B4970;
	color: #000;
	text-align: center;
}
main section#contenedor{
	display: inline-block;
	width: 70%;
	padding: 0.7em 0.8em;
	text-shadow: 4px 3px 5px #000;
	background: #516B82;
}
main aside#modulos{
	display: inline-block;
	width: 25%;
	padding: 0.95em 1.59em 0.85em 1.59em;
	text-shadow: 3px 3px 5px #000;
	background: #516B82;
}
aside#logos{
	width:90%;
	margin: 0 auto;
	background: #4C688B;
	padding: 0.6em 0em;
	color: #fff;
}
aside section#logo1 {
	display: inline-block;
	width: 16.5%;
	padding: 1em 1.68em 1em 1.7em;
	text-shadow: 3px 3px 5px #000;
	background: #818C96;
}
aside section#logo2 {
	display: inline-block;
	width: 16.5%;
	padding: 1em 1.68em 1em 1.7em;
	text-shadow: 3px 3px 5px #000;
	background: #818C96;
}
aside section#logo3 {
	display: inline-block;
	width: 16.5%;
	padding: 1em 1.68em 1em 1.7em;
	text-shadow: 3px 3px 5px #000;
	background: #818C96;
}
aside section#logo4 {
	display: inline-block;
	width: 16.5%;
	padding: 1em 1.68em 1em 1.7em;
	text-shadow: 3px 3px 5px #000;
	background: #818C96;
}
aside section#logo5 {
	display: inline-block;
	width: 16.5%;
	padding: 1em 1.68em 1em 1.7em;
	text-shadow: 3px 3px 5px #000;
	background: #818C96;
}

footer{
	width:90%;
	margin: 0 auto;
	background: #867461;
	color: #373021;
	padding: 0.6em 0em;
	text-align: center;
}
