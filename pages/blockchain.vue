

<template>


  <header class="header">
          <div class="menu container"> <a href="#" class="logo">logo</a>
              <input type="checkbox" id="menu">
              <label for="menu"><img src="C:\Users\CARMEN VARGAS\Desktop\jeje\reda2\img\imagen\menu.png" width="4%" alt=""></label>
      <nav class="navbar">
          <ul>
          <li><a href="/">Historia </a></li>
          <li><a href="/blockchain">Clubes</a></li>
          <li><a href="/ai">Retirados</a></li>
  
  
      </ul>
      </nav>
  </div>
  <div class="header-content container">
      <div class="header-txt">
          <h1>Fútbol</h1>
          <p> 
              "Si no puedes volar, corre; si no puedes correr, camina; si no puedes caminar, gatea, pero sigue avanzando hacia tu meta". Martin Luther King.
          </p>
          <a href="https://books.google.es/books?hl=es&lr=&id=RH7ewye6IcEC&oi=fnd&pg=PT2&dq=futbol&ots=VzGzIY16J7&sig=G9JPSFkqm6yerGVmUdNcglEwrzc#v=onepage&q=futbol&f=false" class="btn-1">Información</a>
      </div>
      
  </div>
      </header>
      <section class="main">
        <section class="articles">
  <br>
  <br>
            
            <article>
      <h1>Clubes</h1>
      <p>
        Te explicamos todo sobre la historia del fútbol, sus orígenes y variantes en diversas culturas. Además, los mejores jugadores de la historia.
      </p>
  
      <h1></h1>
      <p>
        FC Barcelona (España): Conocido por su estilo de juego basado en la posesión (tiki-taka) y su famosa cantera, La Masia.
      </p>
  <img src="public/fc.jpg" alt="" width="80%">
      <p>
        Real Madrid (España): El club con más títulos de la Champions League, famoso por su "Galácticos".
      </p>
  <img src="public/relc.webp" alt="" width="80%">
    </article>
    <article>
    <p>
      Manchester United (Inglaterra): Uno de los clubes más grandes de la Premier League y con gran historia europea.
    </p>
    <img src="public/manch.webp" alt="" width="80%">
    <p>
      AC Milan (Italia): Famoso por su éxito en Europa, con numerosas Copas de Europa/Champions League.
    </p>
    <img src="public/fcm.jpg" alt="" width="80%">
  <p>
    Bayern Múnich (Alemania): Dominante en la Bundesliga y exitoso en Europa.
  </p>
  <img src="public/bay.jpg" alt="" width="80%">
  <p>Liverpool FC (Inglaterra): Con una rica historia europea, destaca por su éxito en la Champions League.
  </p>
  <img src="public/liver.webp" alt="" width="60%">
  <p>
    Juventus (Italia): El club más exitoso de Italia, con numerosos títulos de liga.
  </p>
  <img src="public/juven.jpg" alt="" width="50%">
  <p>
    Ajax (Países Bajos): Famoso por su cantera y su estilo de juego total (fútbol total).
  </p>
  <img src="public/aja.avif" alt="" width="80%">
  <p>
    Boca Juniors (Argentina): Uno de los clubes más grandes de América del Sur, con gran éxito en la Copa Libertadores.
  </p>
  <img src="public/boca.jpg" alt="" width="90%">
  <p>
    Santos FC (Brasil): El club donde Pelé brilló y que ha sido un histórico del fútbol brasileño.
  </p>
  <img src="public/sfc.jpeg" alt="" width="70%">
  
  
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
  
  
  ul {text-align: left;}
  p {text-align: left;}
  
    h1 {
      color: #3498db;
  
    }
  
  .logo{
    color:#3498db
  }
  
    
    </style>
    