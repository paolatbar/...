<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MI MUNDO WEB</title>
  <style>
    body {
      margin: 0;
    }

    .header {
      padding: 5,0px;
      background-color: #f1f1f1;
      text-align: center;
    }

    /* estilo parar la base del menu */
    .topnav {
      overflow: hidden;
      background-color: #333;
    }

    /* Enlaces del menu */
    .topnav a {
      float: left;
      display: block;
      color: #F2F2F2;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
    }

    /* Animacion para el menu */
    .topnav a:hover {
      background-color: #ddd;
      color: black
    }

    /* Estilo para columnas */
    .row__column {
      float: left;
      padding: 15px;
    }

    .row__column.side {
      width: 15%;
    }

    .row__column.middle {
      width: 60%;
    }

    /* Contenido deje de ser flotante */
    .row::after {
      content: "";
      display: table;
      clear: both;
    }

    /* Plantilla responsiva */
    @media screen and (max-width: 600px) {
      .row__column {
        width: 100%;
      }
    }

    /* Pie de pagina */
    .footer {
      background-color: #f1f1f1;
      padding: 10px;
      text-align: center;

    }

	<link rel="stylesheet" type="text/css" href="css/estilo.css" />

  </style>
</head>

<body>
  <!-- Definimos el area del encabezado -->
  <div class="header">
      <h1>COMEDOR EL ATARDECER <3 </h1>
  </div>

  <!-- Crear el menu -->
  <div class="topnav">
    <a href="https://www.mined.gob.sv/" >INICIO</a>
	        <!--p align="rigth">MINED -->
    <a href="#">MISION</a>
    <a href="#">VISION</a>
	<a href="https://www.nintendo.com/us/">TecPAOLA </a>
    <a href=""></a>
  </div>
  <!-- cuerpo de la pagina -->
  <div class="row">`
    <div class="row__column side">
      <h2>OFRECIENDOTE UNA GRAN VARIEDAD DE COMIDA </h2>
      <p> COMO: SOPA DE GALLINA, CARNE AZADA Y MUCHO MAS .</p>
    </div>
    <div class="row__column middle">
      <h2>PRECIOS MUY COMODOS </h2>
      <p>!!! VARIANDO DESDE LOS $5 HASTA LOAS $60 DOLARES!!!!!!!   </p>
    </div>
    <div class="row__column side">
      <h2>CON UNA EXCELENTE VISTA HACIA EL ATARDECER</h2>
      <p>Y TAMBIEN HACIA EL VOLCAN </p>
    </div>
  </div>
  <!-- inicio del piede de pagina -->
  <div class="footer">
    <p> <h3>ABRIMOS DESDE LAS 5:00PM HASTA LAS 10:00 PM </h3> </p>
  </div>



   <img src="paola.png" width="400" height="200"/>
    <img src="paola1.png" width="400" height="200"/>

     <video width="400" height="200" controls>
    <source src="paola.mp4" type="video/mp4">
       </video>

	<a href="Base Access China.html"> Registros  </a> <br>

	<A HREF="index.html">  A hoja 2  </A> <br>
    <A HREF="iindex.html"> A hoja 3 </A>

