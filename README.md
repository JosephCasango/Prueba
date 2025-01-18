
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
  height: 100%;
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
#otro {background-color: black;}
#About {background-color: black;}
#Especial {background-color: black;}













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












/* From Uiverse.io by Z4drus */ 
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




















/* From Uiverse.io by adamgiebl */ 
.Img {
  font-family: inherit;
  font-size: 20px;
  background: royalblue;
  color: white;
  padding: 0.7em 1em;
  padding-left: 0.9em;
  display: flex;
  align-items: center;
  border: none;
  border-radius: 16px;
  overflow: hidden;
  transition: all 0.2s;
  cursor: pointer;
}

.Img span {
  display: block;
  margin-left: 0.3em;
  transition: all 0.3s ease-in-out;
}

.Img svg {
  display: block;
  transform-origin: center center;
  transition: transform 0.3s ease-in-out;
}

.Img:hover .svg-wrapper {
  animation: fly-1 0.6s ease-in-out infinite alternate;
}

.Img:hover svg {
  transform: translateX(1.2em) rotate(45deg) scale(1.1);
}

.Img:hover span {
  transform: translateX(5em);
}

.Img:active {
  transform: scale(0.95);
}

@keyframes fly-1 {
  from {
    transform: translateY(0.1em);
  }

  to {
    transform: translateY(-0.1em);
  }
}












body {
  font-family: Verdana, sans-serif;
  margin: 0;
}

* {
  box-sizing: border-box;
}

.row > .column {
  padding: 0 8px;
}

.row:after {
  content: "";
  display: table;
  clear: both;
}

.column {
  float: left;
  width: 25%;
}

/* The Modal (background) */
.modal {
  display: none;
  position: fixed;
  z-index: 1;
  padding-top: 100px;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  overflow: auto;
  background-color: black;
}

/* Modal Content */
.modal-content {
  position: relative;
  background-color: #fefefe;
  margin: auto;
  padding: 0;
  width: 90%;
  max-width: 1200px;
}

/* The Close Button */
.close {
  color: white;
  position: absolute;
  top: 10px;
  right: 25px;
  font-size: 35px;
  font-weight: bold;
}

.close:hover,
.close:focus {
  color: #999;
  text-decoration: none;
  cursor: pointer;
}

.mySlides {
  display: none;
}

.cursor {
  cursor: pointer;
}

/* Next & previous buttons */
.prev,
.next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -50px;
  color: white;
  font-weight: bold;
  font-size: 20px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
  -webkit-user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover,
.next:hover {
  background-color: rgba(0, 0, 0, 0.8);
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

img {
  margin-bottom: -4px;
}

.caption-container {
  text-align: center;
  background-color: black;
  padding: 2px 16px;
  color: white;
}

.demo {
  opacity: 0.6;
}

.active,
.demo:hover {
  opacity: 1;
}

img.hover-shadow {
  transition: 0.3s;
}

.hover-shadow:hover {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}



</style>
</head>
<body>





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
  <div class="imagene"><img src="https://i.pinimg.com/736x/86/d6/5c/86d65c162a1de465fbb1ae388182a9fd.jpg" alt="Gi" width="300" height="128"></div>
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
    <div class="col-sm-4">

<div class="Analisis">
  <div class="imagene"><img src="https://i.pinimg.com/736x/31/70/9d/31709d6b373cf4ef9d53a6461b4152be.jpg" alt="Gi" width="300" height="128"></div>
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


  <div class="col-sm-4">
<div class="Analisis">
  <div class="imagene"><img src="https://i.pinimg.com/736x/9b/e5/65/9be565cb56b49790d256d28d98140818.jpg" alt="Gi" width="300" height="128"></div>
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


 


<div class="container mt-5">
  <div class="row"> 
    <div class="col-sm-4">

<div class="Analisis">
  <div class="imagene"><img src="https://i.pinimg.com/originals/07/85/e7/0785e7dae354aba21aff4c3752166011.gif" alt="Gi" width="300" height="128"></div>
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






   <div class="col-sm-4">

<div class="Analisis">
  <div class="imagene"><img src="https://i.pinimg.com/736x/16/d7/74/16d774f401e0aa9d589831764b3be204.jpg" alt="Gi" width="300" height="128"></div>
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








 <div class="col-sm-4">

<div class="Analisis">
  <div class="imagene"><img src="https://i.pinimg.com/736x/ab/e1/f3/abe1f3b238cb9f68017105f2b4a50bba.jpg" alt="Gi" width="300" height="128"></div>
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
  <button class="button-3d" onclick="openPage('otro', this,)">
    <div class="button-top">
      <span class="material-icons">❯</span>
    </div>
    <div class="button-bottom"></div>
    <div class="button-base"></div>
  </button>
</div>




</div>
</div>



</div>






<div id="otro" class="contenido">







<div class="container-fluid p-5 bg-danger text-white text-center">
  <h1>Elementos del PFEMDA</h1>
   
</div>
  
<div class="container mt-5">
  <div class="row">
    <div class="col-sm-4">
      <h3>Proceso</h3>


   <p>Se examina el sistema o proceso completo, identificando las partes críticas y cómo estas interactúan entre sí. El objetivo es entender dónde podrían surgir problemas.
</p>

  







   </div>
    <div class="col-sm-4">
      <h3>Fallas</h3>
      <p>Se identifican los errores o problemas potenciales que podrían aparecer en el sistema o proceso. Esto incluye cualquier punto débil que podría generar un fallo.
</p>
    







   </div>
    <div class="col-sm-4">
      <h3>Efectos</h3>        
      <p>Se analizan las consecuencias de las fallas, tanto en el sistema como en los usuarios, clientes o procesos relacionados. ¿Qué impacto tendría la falla si ocurre?</p>













   </div>
<div class="col-sm-4">
      <h3>Modo</h3>
      <p>Se describen las maneras específicas en que las fallas podrían manifestarse. Esto responde a la pregunta: ¿cómo podría fallar?
</p>
      
   </div>
<div class="col-sm-4">
      <h3>Diagnostico</h3>
      <p>A diferencia del AMEF, el PFEMDA pone énfasis en las estrategias para detectar y diagnosticar fallas rápidamente. Esto incluye herramientas, métodos y procedimientos para minimizar el impacto de los problemas.

</p>
      
  </div>
    <div class="col-sm-4">
      <h3>Analisis</h3>
      <p>Al igual que en el AMEF, las fallas se priorizan con base en su gravedad, frecuencia y facilidad de detección. Esto permite decidir qué problemas deben abordarse primero, ya sea mediante medidas preventivas o correctivas.
El PFEMDA combina la prevención de fallas con un enfoque práctico en el diagnóstico y resolución. Esto mejora no solo la confiabilidad de los sistemas, sino también la capacidad de respuesta ante problemas cuando ocurren, reduciendo así el impacto en los procesos y usuarios.

</p>
      
   </div>



  </div>
</div>










<div class="button-containering">
  <button class="button-3d" onclick="openPage('News', this,)" id="defaultOpen">
    <div class="button-top">
      <span class="material-icons">❮</span>
    </div>
    <div class="button-bottom"></div>
    <div class="button-base"></div>
  </button>
  <button class="button-3d" onclick="openPage('About', this,)">
    <div class="button-top">
      <span class="material-icons">❯</span>
    </div>
    <div class="button-bottom"></div>
    <div class="button-base"></div>
  </button>
</div>



</div>




<div id="About" class="contenido">

<div class="container-fluid p-5 bg-info text-white text-center">
  <h1>Control Estadistico De Proceso</h1>
</div>
  
<div class="container mt-5">
  <div class="row">
    <div class="col-sm-4">
      <h3>CEP</h3>
      <p>El Control Estadístico de Procesos (CEP), conocido en inglés como Statistical Process Control (SPC), es una técnica que utiliza herramientas estadísticas para supervisar, medir y mejorar la calidad de los procesos productivos. Su propósito principal es garantizar que los productos o servicios cumplan con los estándares establecidos, identificando y gestionando la variabilidad en los procesos.El Control Estadístico de Procesos (CEP), conocido en inglés como Statistical Process Control (SPC), es una técnica que utiliza herramientas estadísticas para supervisar, medir y mejorar la calidad de los procesos productivos. Su propósito principal es garantizar que los productos o servicios cumplan con los estándares establecidos, identificando y gestionando la variabilidad en los procesos.
</p>
    
   </div>
  <div class="col-sm-4">
      <h3>Comceptos y Claves</h3>
      <p>Variabilidad en los procesos:
Todos los procesos tienen algún nivel de variación, que puede clasificarse en dos tipos:
Variabilidad común: Surge de factores naturales inherentes al proceso.
Variabilidad especial: Resulta de problemas específicos o anomalías.
El CEP ayuda a diferenciar entre estas dos para enfocar los esfuerzos de mejora.
Herramientas estadísticas:
Se utilizan gráficos y análisis de datos para monitorear los procesos, como:
Gráficos de control: Detectan desviaciones respecto a los límites establecidos.
Histogramas: Muestran la distribución de los datos.
</p>
    
  </div>
    <div class="col-sm-4">
      <h3>CEP Prevencion</h3>        
      <p>El CEP se enfoca en identificar posibles problemas antes de que afecten la calidad del producto o servicio, reduciendo desperdicios y evitando fallas en etapas avanzadas.
El CEP no solo mejora la calidad, sino que también aumenta la eficiencia del proceso al anticipar y corregir problemas antes de que se vuelvan significativos. Es una metodología proactiva que asegura productos consistentes y procesos estables.</p>

   </div>
  </div>
</div>




<br>













<div class="row">
  <div class="column">
    <img src="https://i.pinimg.com/736x/f8/b9/cb/f8b9cb5d84807ef441428ccf4debc76d.jpg" style="width:100%" onclick="openModal();currentSlide(1)" class="hover-shadow cursor">
  </div>
  <div class="column">
    <img src="https://i.pinimg.com/736x/b3/cc/9e/b3cc9ed4b8da50151c4763649394fa4d.jpg" style="width:100%" onclick="openModal();currentSlide(2)" class="hover-shadow cursor">
  </div>
  <div class="column">
    <img src="https://i.pinimg.com/736x/6a/0b/cb/6a0bcb5dc34645ad15efd6e0d45ce736.jpg" style="width:100%" onclick="openModal();currentSlide(3)" class="hover-shadow cursor">
  </div>
  <div class="column">
    <img src="https://i.pinimg.com/736x/43/a7/6d/43a76da7b731ad302a35f09717306067.jpg" style="width:100%" onclick="openModal();currentSlide(4)" class="hover-shadow cursor">
  </div>
</div>

<div id="myModal" class="modal">
  <span class="close cursor" onclick="closeModal()">&times;</span>
  <div class="modal-content">

   <div class="mySlides">
      <div class="numbertext">1 / 4</div>
      <img src="https://i.pinimg.com/736x/f8/b9/cb/f8b9cb5d84807ef441428ccf4debc76d.jpg" style="width:100%">
    </div>

  <div class="mySlides">
      <div class="numbertext">2 / 4</div>
      <img src="https://i.pinimg.com/736x/b3/cc/9e/b3cc9ed4b8da50151c4763649394fa4d.jpg" style="width:100%">
    </div>

  <div class="mySlides">
      <div class="numbertext">3 / 4</div>
      <img src="https://i.pinimg.com/736x/6a/0b/cb/6a0bcb5dc34645ad15efd6e0d45ce736.jpg" style="width:100%">
    </div>
    
   <div class="mySlides">
      <div class="numbertext">4 / 4</div>
      <img src="https://i.pinimg.com/736x/43/a7/6d/43a76da7b731ad302a35f09717306067.jpg" style="width:100%">
    </div> 
   <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
   <a class="next" onclick="plusSlides(1)">&#10095;</a>

   <div class="caption-container">
      <p id="caption"></p>
    </div>


 <div class="column">
      <img class="demo cursor" src="https://i.pinimg.com/736x/f8/b9/cb/f8b9cb5d84807ef441428ccf4debc76d.jpg" style="width:100%" onclick="currentSlide(1)" alt="Nature and sunrise">
    </div>
    <div class="column">
      <img class="demo cursor" src="https://i.pinimg.com/736x/b3/cc/9e/b3cc9ed4b8da50151c4763649394fa4d.jpg" style="width:100%" onclick="currentSlide(2)" alt="Snow">
    </div>
    <div class="column">
      <img class="demo cursor" src="https://i.pinimg.com/736x/6a/0b/cb/6a0bcb5dc34645ad15efd6e0d45ce736.jpg" style="width:100%" onclick="currentSlide(3)" alt="Mountains and fjords">
    </div>
    <div class="column">
      <img class="demo cursor" src="https://i.pinimg.com/736x/43/a7/6d/43a76da7b731ad302a35f09717306067.jpg" style="width:100%" onclick="currentSlide(4)" alt="Northern Lights">
    </div>
  </div>
</div>










<br>
<div class="button-containering">
  <button class="button-3d" onclick="openPage('otro', this,)" id="defaultOpen">
    <div class="button-top">
      <span class="material-icons">❮</span>
    </div>
    <div class="button-bottom"></div>
    <div class="button-base"></div>
  </button>
  <button class="button-3d" onclick="openPage('Especial', this,)">
    <div class="button-top">
      <span class="material-icons">❯</span>
    </div>
    <div class="button-bottom"></div>
    <div class="button-base"></div>
  </button>
</div>



</div>


















<div id="Especial" class="contenido">
<div class="container-fluid p-5 bg-warning text-white text-center">
  <h1>PPAP</h1>
</div>
  
<div class="container mt-5">
  <div class="row">
    <div class="col-sm-4">
      
   <p>
        El PPAP (Proceso de Aprobación de Partes de Producción) es un procedimiento estándar, especialmente en la industria automotriz, diseñado para garantizar que los proveedores puedan fabricar piezas o componentes que cumplan con las especificaciones y requisitos del cliente antes de comenzar la producción en masa.
Objetivo del PPAP:
El propósito principal es demostrar que los procesos de fabricación del proveedor son consistentes y que los productos cumplen con los estándares técnicos y de calidad del cliente.
Elementos clave del PPAP:
Diseño registrado por el cliente:
Se incluyen copias del diseño aprobado, como planos técnicos o especificaciones detalladas.

</p>
    
  </div>
    <div class="col-sm-4">
      

<img src="https://i.pinimg.com/736x/2e/bd/62/2ebd62360a8b64cacfc4a66e6db72696.jpg" alt="Girl in a jacket" width="400" height="300">
    
   </div>
    <div class="col-sm-4">
           
   <p>Registro de pruebas:
Evidencia de que las piezas cumplen con los requisitos de pruebas físicas, químicas y de rendimiento.
Informe dimensional:
Resultados detallados de las mediciones de las piezas comparadas con el diseño aprobado.
AMEF del diseño y proceso:
Evaluaciones de riesgos para identificar posibles fallas en el diseño y el proceso de fabricación.
Evidencia de cumplimiento:
Certificados o registros que demuestran que los materiales y procesos cumplen con las especificaciones requeridas.
Aprobación del cliente:
Validación final por parte del cliente mediante firma o aceptación oficial.</p>

   </div>
  </div>
</div>











<br>
<div class="button-containering">
  <button class="button-3d" onclick="openPage('About', this,)" id="defaultOpen">
    <div class="button-top">
      <span class="material-icons">❮</span>
    </div>
    <div class="button-bottom"></div>
    <div class="button-base"></div>
  </button>
</div>







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

















function openModal() {
  document.getElementById("myModal").style.display = "block";
}

function closeModal() {
  document.getElementById("myModal").style.display = "none";
}

var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("demo");
  var captionText = document.getElementById("caption");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " active";
  captionText.innerHTML = dots[slideIndex-1].alt;
}



</script>
   
</body>
</html> 

