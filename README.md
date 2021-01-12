# index.html

`<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="GEMD.css.css">
    <link rel="stylesheet" media="(max-width: 800px)" href="GEMD.css.css" />
   
    <title>GEMD</title>
   
 
</head>

<body>
<style>
  @media (max-width: 600px) {
  }
@media (min-width: 700px) and (orientation: landscape) { 
}



body{
 background-color: white;
box-sizing: content-box;
margin: 1%;
padding: 2%;
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;

}

h1{
  color:rgb(39, 39, 39);
  background-color: transparent;
  font-size: 40px;
  padding: 4%;
  margin-bottom: 4%;
}

hr{ 
  margin-bottom: 4%;
}
.container{
  background-color:white;
  width: 80%;
  height: 450px;
  padding: 4% ;
  margin-bottom: 4%;
  border-radius: 20%;
  border-style: solid;

}

.papi-image{
  background-image: url(image20.png);
  border-radius: 100%;
  background-attachment: contain;
  width: 70px;
  height: 70px;
  margin: 2% 2% 2%;



}

.mifoto{
  background-position: relative;
  border-radius: 100%;
  width:100px ;
  height:100px ;
  display: inline;

}


.delis{
  background-position: relative;
  border-radius: 100%;
  width:100px ;
  height:100px ;
  display: inline;

}

.padre{
  background-color:transparent;
  width: 100%;
  height: 100px;
  padding: 4%;
  margin-bottom:8%;
}


h2{
  color:rgb(39, 39, 39);
  margin-bottom: 4%;
}

p{
  color: #2f3640;
  font-size: 17x;

}






a{
  color: rgb(145, 193, 255);
  background-color: black;
  background-position: center;
  position: relative;
  text-decoration: none;
  font-family: sans-serif, Bold;
  font-weight: 2%;
  font-size: 16px;
  border: 1px;

  padding: 2px;
  width: 50px;
  height:  50px;
  padding: 4%;
  margin: 4% 4% 4% 4%;
  border-radius: 12%;
  


}



h3{
  color: #2f3640;
font-family:  sans-serif,bold;
}

h4{
  color:white;
  font-family:  sans-serif,bold;
  
 
 
  } 
 /*estadisticas*/

  .visitas{
    background-position: relative;
    background-color:transparent;
    border-style:solid;
    width: 90%;
    height: 400px;
    padding: 4%;
    border-radius:12%;

  }

  .helper-blue{
    background-position: relative;
background-color: rgb(65, 65, 255);
width: 15%;
height:15px;
  }

  .helper-yellow{
    background-position: relative;
background-color: rgb(247, 210, 0);
width: 30%;
height:15px;
  
}

.helper-green{
  background-position: relative;
background-color: rgb(0, 247, 12);
width: 30%;
height:15px;

}
  
 /*contador animado*/
  .count::after {
    font: 800 50px system-ui;
    content: counter(count);
    animation: counter 30s linear infinite alternate;
    counter-reset: count 0;
    animation-delay: 1s;
    color:rgb(68, 187, 223);

    font-size: 15px;
  
    
  }

  
  /*stats*/
  .column {
    float: left;
    width: 100%;
    padding: 0px;
    text-align: left;
    font-size: 25px;
    cursor: pointer;
    color:black;
  }
  
  .containerTab {
    padding: 0px;
    color: white;
    width: 100%;
  }
  
  /* Clear floats after the columns */
  .row:after {
    content: "";
    display: table;
    clear: both;
  }
  
  /* Closable button inside the image */
  .closebtn {
    float: right;
    color: white;
    font-size: 35px;
    cursor: pointer;
  }
/*Obtener nombre*/
 
p {
  margin: 24px 0;
  line-height: 2;
}

.wrapper {
  padding: 32px;
}

.cookie-container {
  position: fixed;
  bottom: -100%;
  left: 0;
  right: 0;
  background: #2f3640;
  color: #f5f6fa;
  padding: 0 32px;
  box-shadow: 0 -2px 16px rgba(47, 54, 64, 0.39);

  transition: 400ms;
}

.cookie-container.active {
  bottom: 0;
}

.cookie-container a {
  color: #f5f6fa;
}

.cookie-btn {
  background: black;
  border: 0;
  color: rgb(68, 187, 223);
  padding: 12px 48px;
  font-size: 18px;
  margin-bottom: 16px;
  border-radius: 8px;
  cursor: pointer;
}



</style>
  <header>
    <div class="box-content">
         <h1><strong> GEMD.com</strong>
        
         </h1>
         
         <nav>
          <a href="gemd.html.html"><strong>Inicio</strong></a>
          <a href="Contacto.html "><strong>contacto</strong></a>
        
        </nav>
        <br><br><br>
    </div>
    <hr>
<p>GEMD es el asistente medico en lineal para la búsqueda concreta del profesional medico,
   en ella puedes buscar tu profesional y contactarla al numero correspondiente en la casilla correspondiente<br>El directorio medico Funciona para encontrar a tu personal medico y rápidamente llamar tu comunicarte con el profesional asignado.</p>
    
    </header>
    <br><br>
   
<!--Cirugia general-->
<hr>
<h2>Cirugia General</h2>
<div class="container">
<div class="papi">
<img class="papi-image" src="image20.png">
<strong>Dr. Armando Polanco</strong>
<hr>
<p>Cirujano General!...</p>
<p> Local.loc::INEMED </p>
<p>San Fco. Macoris</p>
<p>Consultorio::809-2443-586</p>
<p>Dirección: Calle Rivas, Esq, Calle Colón #57, San Francisco de Macorís 31000</p>

</div>
</div>
<hr>

<h2>Cirugia Pediatrica</h2>
<div class="container">
  <div class="papi">
  <img src="natasha.jpg"class="papi-image" >
  <strong>Dra.Natasha Ferreiras </strong>
  <hr>
  <p>Cirujano Pediatra!...</p>
  <p> Local.loc::INEMED </p>
  <p>San Fco. Macoris</p>
  <p>Consultorio::(809) 449-3535</p>
  <p>Dirección: Calle Rivas, Esq, Calle Colón #57, San Francisco de Macorís 31000</p>
  
  </div>
  </div>

  <h2>//:Equipo.team::</h2>
<div class="padre">
  <img src="Mifoto..jpg" class="mifoto" >
    
    <img src="zelenhia.jpg" class="delis" >
    
</div>
<hr>

<h2>//:Tablero-GEMD::</h2>

</div>





<!--Chart-->

<div class="visitas">
<h2>Visitas (0)</h2>
<div class="helper-blue">0</div>
<h2>Clicks(30%)</h2>
<div class="helper-yellow">0</div>
<h2>Interaccion(30%)</h2>
<div class="helper-green">0</div>
</div>












    <div class="cookie-container">
      <p>
        Esta web contiene políticas de cookies para un mejor funcionamiento.
        <a href="#">privacy policy</a> and <a href="#">cookie policy</a>.
      </p>

      <button class="cookie-btn">
        Okay
      </button>
    </div>
  </div><!-- JavaScript Bundle with Popper -->
 
<script src="https://cdn.jsdelivr.net/npm/sweetalert2@10"></script>
<script src="Gemd.js"></script>

</html>`
