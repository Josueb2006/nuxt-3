

<template>


<header class="header">
        <div class="menu container"> <a href="#" class="logo">logo</a>
            <input type="checkbox" id="menu">
            <label for="menu"><img src="C:\Users\CARMEN VARGAS\Desktop\jeje\reda2\img\imagen\menu.png" width="4%" alt=""></label>
    <nav class="navbar">
        <ul>
        <li><a href="ai.vue">Inicio </a></li>
        <li><a href="contenido.html">Contenido</a></li>
        <li><a href="actividades.html">Actividades</a></li>
        <li><a href="evaluacion.html">Evaluacion</a></li>
        <li><a href="Materialcomplementario.html">Materialcomplementario</a></li>
        <li><a href="Creditos.html">Creditos</a></li>

    </ul>
    </nav>
</div>
<div class="header-content container">
    <div class="header-txt">
        <h1>Futbol</h1>
        <p> 
            "Si no puedes volar, corre; si no puedes correr, camina; si no puedes caminar, gatea, pero sigue avanzando hacia tu meta". Martin Luther King.
        </p>
        <a href="#" class="btn-1">Información</a>
    </div>
    
</div>
    </header>
    <section class="main">
      <section class="articles">
          <article>

    <div>
      <h1>Inteligencia Artificial (IA)</h1>
      <p>
        La Inteligencia Artificial es la simulación de procesos de inteligencia humana por parte de sistemas informáticos. 
        Las aplicaciones incluyen aprendizaje automático, procesamiento del lenguaje natural, y mucho más.
      </p>
      <nuxt-link to="http://localhost:3000/">Volver a la página principal</nuxt-link>
    </div>
          </article>
          <article>
    <h1>Historia del Fútbol</h1>
    <p>
      Te explicamos todo sobre la historia del fútbol, sus orígenes y variantes en diversas culturas. Además, los mejores jugadores de la historia.
    </p>

    <h1>¿Cómo es la historia del fútbol?</h1>
    <p>
      El fútbol es uno de los deportes más populares del mundo. Es practicado en prácticamente todos los países del mundo, los cuales se dan cita cada cuatro años para disputarse la copa mundial, y mantienen a lo largo del año sus distintas ligas regulares.
    </p>

    <p>
      Se estima que el fútbol tiene alrededor de 250 millones de jugadores en todo el mundo, y que moviliza alrededor de 1.800 millones de interesados y fanáticos en el globo entero. Es uno de los deportes olímpicos, y su jefatura internacional la ejerce la Federación Internacional de Asociaciones de Fútbol (o FIFA, por sus siglas en francés).
    </p>

  </article>
  <article>
  <p>
    Los orígenes antiguos de este deporte son inciertos, pero en el siglo III a. C. en China se practicaba un deporte similar. En este remoto antecedente del fútbol, los soldados de la Dinastía Han practicaban un ejercicio llamado ts’uh Kúh (también llamado luju o tsu chu), que consistía en arrojar una bola con los pies hacia una pequeña red. En algunas variantes, el jugador debía hacerlo mientras se defendía del ataque físico de sus rivales.
  </p>
  <p>
    Siglos después hubo prácticas más semejantes al fútbol moderno, como el kemari japonés, de tipo más ceremonial, en el que una pelota debía ser mantenida en el aire el mayor tiempo posible, pasándosela entre jugadores sin usar las manos.
  </p>
<p>
  También hubo variantes occidentales, como el episkyros griego y el haspastrum romano, de los cuales se tiene muy poca información. También se sabe hoy que los antiguos pueblos mesoamericanos practicaban algo similar llamado pok ta pok, hace unos 3.000 años, y que otro tanto hacían los aborígenes norteamericanos, aunque lo llamaban pasuckuakohowog.
</p>
<p>Sin embargo, es poco probable que estos deportes ancestrales tuviera influencia directa en el fútbol moderno. Lo más próximo en la historia europea son los “juegos de pelota” practicados por jóvenes británicos y franceses (estos últimos bajo el nombre de soule). En los carnavales era común su práctica en las islas británicas, ocasiones en las que podía participar un pueblo entero.

</p>
<p>
  Los italianos tuvieron el antecedente más claro de todos, el calcio florentino, menos violento que sus variantes británicas y más organizado que las francesas, consistente en dos equipos de 27 jugadores cada uno. Se practicó a partir del siglo XVI, y en 1580 Giovanni Bardi presentó el primer conjunto formal de reglas.
</p>
<p>
  Propiamente dicha, la historia moderna del fútbol comienza en Gran Bretaña en el siglo XIX, cuando surgieron las primeras reglas unificadoras del fútbol de carnaval, comenzando a practicarse en asociaciones colegiales fuera de la época de festividades. De hecho, en 1863 las reglas de juego de la colegiatura de Cambridge fueron la base del código de reglas actual, tomando también normas del modo de juego de Sheffield.
</p>
<p>
  Así, con un reglamento de 13 normas apenas, el fútbol moderno fue promovido por la recién creada Football Association (FA). De allí también provino, aunque algunos años después, el término soccer, derivado de “association” y el sufijo –er, y surgió también la primera competición de ligas de la historia, la Football League en 1888. Su fin era recaudar los fondos suficientes para poder profesionalizar a los jugadores de la FA.
</p>
<p>
  Hacia finales del siglo XIX y principios del XX, el fútbol a la inglesa se había extendido por toda Europa y luego a otros continentes, en parte gracias al sistema colonial europeo, y al intercambio comercial con las recientes repúblicas americanas.
</p>
<p>
  La primera liga de fútbol americana fue la argentina, fundada en 1891, y el primer partido internacional por fuera de Europa se disputó entre Argentina y Uruguay en 1901. En cambio, las condiciones económicas en Asia le impidieron al fútbol abandonar el ámbito meramente universitario hasta entrados los años 80 del siglo XX.
</p>

</article>
  </section>
    </section>
  </template>
  
  <script setup>
  </script>
  
  <style scoped>

.container{max-width: 1200px;
margin: 0 auto;}


.section{text-align: justify;}
  .main .articles {
       width: 68.5%;
       margin-right:1.5%;
       float: left;
       
      
   }
   ul {text-align: left;}
   p {text-align: left;}
  .main .articles article {
      float: right;
      width: 90%;
  padding: 20px;
  background: #ffffff;
  margin-bottom: 20px;
  border-radius: 15px;
  background-image: linear-gradient(to right, rgb(223, 243, 111),white);
  box-shadow: 5px 5px 5px gray;
  font-size: 18px;}
.header{
background-image: url("/public/2.jpeg");
background-position: center bottom;
background-repeat: no-repeat;
background-size: cover;
min-height: 70vh;
align-items: center;
display: flex;
align-items: center;}

.menu{
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    display: flex;
    align-items: center;
    justify-content: space-between;
    z-index: 1000;
}

.logo{color: white;
font-size: 25px;
font-weight: 800;}

.menu .navbar ul li {position: relative;
    float: left;
}
.menu .navbar ul li a {
    font-size: 18px;
    padding: 20px;
    color: white;
    display: block;
}
.menu .navbar ul li a:hover{font-size: 18px;
padding: 10px;
color: black;
display: block;
background-color: white;}
#menu{display: none;}
.menu-icono {width: 25px;}

.menu label {cursor: pointer;
display: none;}
.header-txt {text-align: center;}

.header-txt h1 { font-size: 85px;
color: white;
text-transform: uppercase;
margin-bottom: 20px;}

.header-txt p {color: white;
font-size: 16px;
padding: 0 250px;
margin-bottom: 45px;}
.btn-1 {display: inline-block;
padding: 12px 45px;
border: 1px solid blue;
color: yellow;
font-size: 16px;
text-transform: uppercase;
font-weight: 600;}
.btn-1:hover {color: black;
background-color: white;}
h2 {font-size: 70px;
text-transform: uppercase;
color: #1B293A;}


aside {
    width: 30%;
    float: left;
    padding: 327px  20px;
    background: url(img/imagen/TeoremaPitagoras.jpg);
    background-size: cover;
    background-position: center;
    border-radius: 15px;
    box-shadow: 5px 5px 5px gray;
    margin-bottom: 20px;
}

.derecha {
    width: 30%;
background: rgba(107, 111, 28, 0.912);
    float: left;
    padding: 300px  20px;
background: url(img/imagen/TeoremaPitagoras.jpg);
background-size: cover;
background-position: center;
border-radius: 15px;
box-shadow: 5px 5px 5px gray;
}


ul {text-align: left;}
p {text-align: left;}




  h1 {
    color: #3498db;

  }

.logo{
  color:#3498db
}

  
  </style>
  