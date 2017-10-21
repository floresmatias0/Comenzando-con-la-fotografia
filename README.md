<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, user-scalable=no">
    <meta charset="utf-8">
    <link rel="stylesheet" href="css/estilos.css">
    <link href="https://fonts.googleapis.com/css?family=Dancing+Script" rel="stylesheet">
  </head>
  <body>
    <style>
      *{
margin:0;
}
body{
background: #02010a;
color: white;
font-size: 16px;
font-family: 'Dancing Script';
font-size: 14pt;
}
#contenido{
width: 900px;
margin: 0 auto;
min-height: 200px;
}
header{
background: #5b7989;
border-radius: 10px 10px 0 0;
text-shadow: 2px 2px #02010a;
padding: 15px 0;
display: flex;
display: -webkit-flex;
flex-flow: row nowrap;
-webkit-flex-flow: row wrap;
animation: mianimacion 1s;
}
@-webkit-keyframes mianimacion{
  0%{
    margin-top: 150%;
  }
  60%{
    margin-top: 75%;
  }
  100%{
    margin-top: -5%;
  }
}
#tituloCabecera{
width: 70%;
text-indent: 15px;
}
#menuCabecera{
width: 30%;
font-size: 18pt;
}
#menuCabecera a, #menuCabecera a:hover{
color: #fff;
padding: 5px 10px;
}
#menuCabecera a + a::before {
color: #fff;
text-decoration: none;
}
#menuCabecera .actual{
text-decoration: none;
}
@media all and (min-width:900px) {
 .imgs{
   width: 33.33%;
 }
}
@media (max-width: 900px){
#contenido{
    width: 100%;
    margin: 0 auto;
  }
  #tituloCabecera{
    width: 100%;
    text-align: center;
  }
  #menuCabecera{
    display: flex;
    flex-direction: row;
    width: 100%;
    margin-left: 19%;
  }
  .Central{
    width: 100%;
    display: flex;
  }
.Secundarias{
  width: 100%;
  display: flex;
  flex-flow: column wrap;
}
  #Galeria{
    width: 100%;
    display: flex;
    flex-direction: column;
    }
    .imgs {
      width: 100%;
    }
footer{
  width: 100%;
  display: flex;
  flex-direction: column;
}
}
#Galeria{
  display: flex;
  display: -webkit-flex;
  flex-flow: row wrap;
  -webkit-flex-flow: row wrap;
  background: #d5c75f;
  min-height: 100px;
  padding: 20px 0;
}
.imgs{
  text-align: center;
  box-sizing: border-box;
  padding: 10px;
}
img{
  width: 100%;
}
.img1{
  filter: blur(10px);
}
.img5{
}
.img2, .img4, .img6{
  filter: grayscale(100%);
}
.img3{
  filter: sepia(90%);
}
.Central{
  background-color: #82c3a6;
  border: 1px;
  width: 100%;
  text-align: center;
}
.Central img{
  width: 80%;
  margin-top: 3%;
  margin-bottom: 3%;
  box-shadow: 2px 2px #02010a;
}
.Secundarias{
  display: flex;
  background-color: #d5c75f;
  border: 1px;
  text-align: center;
  color: #02010a;
  text-decoration: underline;
}
.Paisajes img, .Retratos img{
  width: 80%;
  height: 85%;
  box-shadow: 2px 2px #02010a;
}
.Paisajes, .Retratos{
  width: 100%;
  margin-top: 2%;
}
.Paisajes img:hover{
  transform: rotate(10deg);
}
.Retratos img:hover{
 transform: translate(5px,-20px);
}
footer{
  display: flex;
  flex-grow: row wrap;
  border-radius: 0 0 10px 10px;
  background-color: #C6d5c5;
  text-align: left;
  text-indent: 15px;
  color: #02010a;
}
.footer1{
  margin-top: 2%;
  margin-bottom: 2%;
  padding: 2%;
}
footer h1{
  font-weight: bold;
  font-size: 23px;
}
footer p{
  font-size: 16px;
}
    </style>
   <div id="contenido">
     <header>
      <div id="tituloCabecera">
       <h1>Comenzando con la fotografía</h1>
      </div>
      <div id="menuCabecera">
       <a href="index.html" class="actual">Inicio</a>
       <a href="Paisajes.html">Paisajes</a>
       <a href="Retratos.html">Retratos</a>
      </div>
     </header>
     <div class="Central">
       <figure>
         <img src="imagenes/IMG_1531.JPG" alt="Imagen Central">
       </figure>
     </div>
     <div class="Secundarias">
       <div class="Paisajes">
         <figure>
           <a href="Paisajes.html"><img src="imagenes/IMG_2132.JPG" alt="Imagen secundaria"></a>
         </figure>
         <figcaption>Paisajes</figcaption>
       </div>
       <div class="Retratos">
         <figure>
           <a href="Retratos.html"><img src="imagenes/IMG_1475.JPG" alt="Imagen secundaria"></a>
         </figure>
         <figcaption>Retratos</figcaption>
       </div>
     </div>
     <footer>
       <div class="footer1">
         <h1>Contacto</h1>
         <p>floresmatias0@gmail.com</p>
         <p>Crisantemo 6521</p>
         <p>Telefono: 1169047409</p>
       </div>
       <div class="footer1">
        <h1>Terminos</h1>
        <p>Conoce nuestros terminos y condiciones</p>
       </div>
       <div class="footer1">
         <h1>Redes Sociales</h1>
         <p>Comparte con tus amigos</p>
         <li><a href="http://www.facebook.com">Facebook</a></li>
         <li><a href="http://www.twitter.com">Twitter</a></li>
         <li><a href="http://www.instagram.com">Instagram</a></li>
       </div>
       <div class="footer1">
         <h1>Derechos</h1>
         <p>@Copyright - 2020</p>
       </div>
     </footer>
    </div>
  </body>
</html>
