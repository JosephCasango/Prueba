
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">









  <title>Bootstrap 5 Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>





<style>



* {box-sizing: border-box}

body, html {
  height: 200%;
 margin: 0;
  font-family: Arial;

}

.tabla {
  background-color: #555;
  color: white;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 0.1px 0.1px;
  font-size: 20px;
  width: 25%;
}

.tabla:hover {
  background-color: #777;
}

.contenido {
  color: white;
  display: none;
  padding: 1px 1px;
  height: 105%;
}


#Inicio {background-color: black;}
#News {background-color: black;}
#Contact {background-color: red;}
#About {background-color: white;}














.bg-image {
  /* Full height */
  height: 100%; 
  
  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/* Images used */
.img1 { background-image: url("https://i.pinimg.com/736x/fe/b8/2d/feb82d3d0dccb51e13414c539652f282.jpg"); }
.img2 { background-image: url("https://i.pinimg.com/736x/58/34/a8/5834a8af5844d0c6075f0aff65959d56.jpg"); }
.img3 { background-image: url("https://i.pinimg.com/736x/90/5c/f8/905cf8adc890477aea2447bef5168f1e.jpg"); }
.img4 { background-image: url("https://i.pinimg.com/736x/88/4d/25/884d25218b66bf5756f408aa3103202c.jpg"); }
.img5 { background-image: url("https://i.pinimg.com/736x/eb/15/db/eb15db04a5343837dca538694f4df136.jpg"); }
.img6 { background-image: url("https://i.pinimg.com/736x/6e/db/4a/6edb4a1d2354b50cb9789c824ce82be0.jpg"); }

/* Position text in the middle of the page/image */
.bg-text {
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0, 0.4); /* Black w/opacity/see-through */
  color: white;
  font-weight: bold;
  font-size: 80px;
  border: 10px solid #f1f1f1;
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 1;
  width: 400px;
  padding: 10px;
  text-align: center;
}


.imgine{
   height: 100%; 
     width: 100%;

}












/* From Uiverse.io by JaydipPrajapati1910 */ 
.Comenzar {
  width: 180px;
  height: 50px;
  border-radius: 5px;
  border: none;
  transition: all 0.5s ease-in-out;
  font-size: 20px;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  font-weight: 600;
  display: flex;
  align-items: center;
  background: #040f16;
  color: #f5f5f5;
}

.Comenzar:hover {
  box-shadow: 0 0 20px 0px #2e2e2e3a;
}

.Comenzar .iconico {
  position: absolute;
  height: 40px;
  width: 70px;
  display: flex;
  justify-content: center;
  align-items: center;
  transition: all 0.5s;
}

.Comenzar .textCo {
  transform: translateX(55px);
}

.Comenzar:hover .iconico {
  width: 175px;
}

.Comenzar:hover .textCo {
  transition: all 0.5s;
  opacity: 0;
}

.Comenzar:focus {
  outline: none;
}

.Comenzar:active .iconico {
  transform: scale(0.85);
}











.button-containering {
  display: flex;
  justify-content: center;
  margin: 20px;
}

.button-3d {
  -webkit-appearance: none;
  appearance: none;
  position: relative;
  border-width: 0;
  padding: 0 8px;
  min-width: 4em;
  min-height: 4em;
  box-sizing: border-box;
  background: transparent;
  font: inherit;
  cursor: pointer;
  margin: 10px;
  border-radius: 20px;
}

.button-top {
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  z-index: 2;
  padding: 8px 16px;
  transform: translateY(0);
  color: #fff;
  background-image: linear-gradient(145deg, #6a11cb, #2575fc);
  text-shadow: 0 -1px rgba(0, 0, 0, 0.25);
  border-radius: 20px;
  transition: transform 0.3s, border-radius 0.3s, background 10s;
}

.button-3d:active .button-top {
  border-radius: 10px 10px 8px 8px / 8px;
  transform: translateY(2px);
  background-image: linear-gradient(145deg, #2575fc, #6a11cb);
}

.button-bottom {
  position: absolute;
  z-index: 1;
  bottom: 4px;
  left: 4px;
  border-radius: 20px;
  padding-top: 6px;
  width: calc(100% - 8px);
  height: calc(100% - 10px);
  background-image: linear-gradient(145deg, #2575fc, #6a11cb);
  box-shadow: 0px 2px 3px 0px rgba(0, 0, 0, 0.5);
  transition: border-radius 0.2s, padding-top 0.2s;
}

.button-base {
  position: absolute;
  z-index: 0;
  top: 4px;
  left: 0;
  border-radius: 20px;
  width: 100%;
  height: calc(100% - 4px);
  background-color: rgba(0, 0, 0, 0.15);
  box-shadow: 0 1px 1px 0 rgba(255, 255, 255, 0.75),
    inset 0 2px 2px rgba(0, 0, 0, 0.25);
  transition: border-radius 0.2s, padding-top 0.2s;
}

.button-3d:active .button-bottom {
  border-radius: 10px 10px 8px 8px / 8px;
  padding-top: 0;
}

.button-3d:active .button-base {
  border-radius: 10px 10px 8px 8px / 8px;
}

















.Analisis {
  overflow: hidden;
  border-radius: 0.5rem;
  max-width: 300px;
  background-color: #fff;
  color: #212121;
}

.imagene {
  height: 8rem;
  width: 100%;
  object-fit: cover;
  background-color: rgb(204, 0, 255);
  background-image: linear-gradient(to right, rgb(255, 174, 0), rgb(204, 0, 255));
}

.info {
  padding: 1rem;
  text-align: center;
}

.text-1 {
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 600;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

.text-2 {
  margin-top: 1rem;
  font-weight: 900;
  text-transform: uppercase;
}

.text-2 span:first-child {
  font-size: 2.25rem;
  line-height: 2.5rem;
  font-weight: 900;
}

.text-2 span:last-child {
  margin-top: 0.5rem;
  display: block;
  font-size: 0.875rem;
  line-height: 1.25rem;
}

.action {
  margin-top: 1rem;
  display: inline-block;
  width: 100%;
  background-color: rgb(0, 0, 0);
  padding-top: 1rem;
  padding-bottom: 1rem;
  border-radius: 4px;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 1);
  text-decoration: none;
}

.sin {
  margin-top: 1rem;
  font-size: 0.75rem;
  line-height: 1rem;
  font-weight: 500;
  text-transform: uppercase;
  color: rgba(156, 163, 175, 1);
}

</style>
</head>
<body>




<button class="tabla" onclick="openPage('Contact', this,)"></button>
<button class="tabla" onclick="openPage('About', this,)"></button>













<div id="Inicio" class="contenido">


<div><img class="imgine" src="https://i.pinimg.com/736x/fe/b8/2d/feb82d3d0dccb51e13414c539652f282.jpg"></div>
<div><img class="imgine" src="https://i.pinimg.com/736x/58/34/a8/5834a8af5844d0c6075f0aff65959d56.jpg"></div>
<div><img class="imgine" src="https://i.pinimg.com/736x/90/5c/f8/905cf8adc890477aea2447bef5168f1e.jpg"></div>
<div><img class="imgine" src="https://i.pinimg.com/736x/88/4d/25/884d25218b66bf5756f408aa3103202c.jpg"></div>
<div><img class="imgine" src="https://i.pinimg.com/736x/eb/15/db/eb15db04a5343837dca538694f4df136.jpg"></div>
<div><img class="imgine" src="https://i.pinimg.com/736x/6e/db/4a/6edb4a1d2354b50cb9789c824ce82be0.jpg"></div>
<div class="bg-text">

 Equipo 1

<br>





<center>
<button class="Comenzar" onclick="openPage('News', this,)">
    <span class="iconico">
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="24" fill="currentColor" class="bi bi-airplane-fill" viewBox="0 0 16 16">
  <path d="M6.428 1.151C6.708.591 7.213 0 8 0s1.292.592 1.572 1.151C9.861 1.73 10 2.431 10 3v3.691l5.17 2.585a1.5 1.5 0 0 1 .83 1.342V12a.5.5 0 0 1-.582.493l-5.507-.918-.375 2.253 1.318 1.318A.5.5 0 0 1 10.5 16h-5a.5.5 0 0 1-.354-.854l1.319-1.318-.376-2.253-5.507.918A.5.5 0 0 1 0 12v-1.382a1.5 1.5 0 0 1 .83-1.342L6 6.691V3c0-.568.14-1.271.428-1.849Z"></path>
</svg>
    </span>
    <span class="textCo">Comenzar</span>
</button></center>
</div>

  
</div>







<div id="News" class="contenido">









<div class="container-fluid p-5 bg-primary text-white text-center">
  <h1>ANÁLISIS DE MODOS Y EFECTOS DE FALLAS</h1>
 
</div>
  
<div class="container mt-5">
  <div class="row">
    <div class="col-sm-4">
 
<div class="Analisis">
  <div class="imagene"></div>
  <div class="info">
    <p class="text-1">
      Analisis
    </p>

   <div class="text-2">

   <span>El análisis de modos y efectos de fallas (FMEA, por sus siglas en inglés) es una herramienta estructurada que permite identificar, analizar y priorizar posibles problemas en un sistema, proceso, diseño, producto o servicio. Su principal objetivo es anticipar fallas antes de que ocurran, mejorando así la confiabilidad, seguridad y calidad</span>
    </div>
    
   <p class="sin">
      Offer valid until 29th April, 2023 *
    </p>
  </div>
</div>

</div>
</div>
   </div>
   <div class="container mt-5">
  <div class="row">
    <div class="col-sm-4">

<div class="Analisis">
  <div class="imagene"></div>
  <div class="info">
    <p class="text-1">
      Modo de Fallas
    </p>

  <div class="text-2">

  <span>Esto se refiere a las maneras específicas en que un sistema o componente podría fallar. En otras palabras, ¿qué podría salir mal?
</span>
    </div>
    
  <p class="sin">
      Offer valid until 29th April, 2023 *
    </p>
  </div>
</div>
    </div>

</div>
</div>

<div class="container mt-5">
  <div class="row">
  <div class="col-sm-4">
<div class="Analisis">
  <div class="imagene"></div>
  <div class="info">
    <p class="text-1">
      Efectos de la falla
    </p>

  <div class="text-2">

  <span>Aquí se describe el impacto que tendría la falla si llegara a ocurrir. ¿Qué consecuencias habría?

</span>
    </div>
    
<p class="sin">
      Offer valid until 29th April, 2023 *
    </p>
  </div>
</div>
    </div>


</div>
</div>


 


<div class="container mt-5">
  <div class="row"> 
    <div class="col-sm-4">

<div class="Analisis">
  <div class="imagene"></div>
  <div class="info">
    <p class="text-1">
      Causa de Falla
    </p>

  <div class="text-2">

   <span>Se identifican las razones o condiciones que podrían provocar la falla. ¿Por qué sucedería?

</span>
    </div>
    
   <p class="sin">
      Offer valid until 29th April, 2023 *
    </p>
  </div>
</div>
    </div>
<br>
<div></div>




<div class="container mt-5">
  <div class="row">
  <div class="col-sm-4">

<div class="Analisis">
  <div class="imagene"></div>
  <div class="info">
    <p class="text-1">
      Severidad (S)
    </p>

  <div class="text-2">

  <span> Evalúa qué tan grave sería el efecto de la falla en caso de que ocurra. Se usa una escala, generalmente de 1 (efecto menor) a 10 (efecto crítico).


</span>
    </div>
    
   <p class="sin">
      Offer valid until 29th April, 2023 *
    </p>
  </div>
</div>
    </div>
</div>
</div>






<div class="container mt-5">
  <div class="row">
 <div class="col-sm-4">

<div class="Analisis">
  <div class="imagene"></div>
  <div class="info">
    <p class="text-1">
      Ocurrencia (O)
    </p>

   <div class="text-2">
   <span> Estima con qué frecuencia podría suceder la falla. También se utiliza una escala de 1 (muy improbable) a 10 (muy probable).



</span>
    </div>
    
  <p class="sin">
    Offer valid until 29th April, 2023 *
    </p>
  </div>
</div>
    </div>





</div>
</div>






<div class="button-containering">
  <button class="button-3d" onclick="openPage('Inicio', this,)" id="defaultOpen">
    <div class="button-top">
      <span class="material-icons">❮</span>
    </div>
    <div class="button-bottom"></div>
    <div class="button-base"></div>
  </button>
  <button class="button-3d" onclick="openPage('Contact', this,)">
    <div class="button-top">
      <span class="material-icons">❯</span>
    </div>
    <div class="button-bottom"></div>
    <div class="button-base"></div>
  </button>
</div>







</div>






<div id="Contact" class="contenido">
<h1>Titulo</h1>
</div>




<div id="About" class="contenido">
<h1>Titulo</h1>  
</div>





<script>
function openPage(pageName,elmnt,color) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("contenido");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tabla");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].style.backgroundColor = "";
  }
  document.getElementById(pageName).style.display = "block";
  elmnt.style.backgroundColor = color;
}


document.getElementById("defaultOpen").click();
</script>
   
</body>
</html> 

