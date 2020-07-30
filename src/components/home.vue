<template>
  <div class="container-fluid m-0 p-0">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.6.3/css/all.css" integrity="sha384-UHRtZLI+pbxtHCWp1t77Bi1L4ZtiqrqD80Kn4Z8NTSRyMA2Fd33n5dQ8lWUE00s/" crossorigin="anonymous">
    <img class="seccion1" src="../assets/vector1.png">
  <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
  <a class="navbar-brand" href="#">Foodies</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav navtext ml-md-auto">
      <li class="nav-item mx-3">
        <a class="nav-link" href="#">Acerca de</a>
      </li>
      <li class="nav-item mx-3">
        <a class="nav-link" href="#">Restaurantes</a>
      </li>
      <li class="nav-item mx-3">
        <a class="nav-link" href="#">Menú</a>
      </li>
      <li class="nav-item mx-3">
        <a class="nav-link" href="#">Contáctanos</a>
      </li>
    </ul>
  </div>
</nav>
<!-- first section -->
  <div class="container">
    <div class="row pt-5">
      <div class="col-sm pt-5">
      <h2 class="text-sm-left h2row1">Un nuevo sabor esta <mark class="mark">en la ciudad</mark></h2>
      <p class="text-muted text-sm-left opensans">Estamos a punto de descubrir un mundo lleno de sabores y de emociones inigualables.</p>
      <p class="font-weight-bold text-sm-left syne-font"><a href="#">Encuentranos</a></p>
      </div>
      <div class="col-sm">

      </div>
      <div class="col-sm pt-5">
      <img class="img-fluid img-responsive" src="../assets/ham.png">
      </div>
    </div>
    <!-- second section -->
     <div class="row mx-auto">
      <div class="col-sm pt-5">
        <img class="img-responsive img-fluid" src="../assets/img1.png">
        <h2 class="h2row2 pt-3">LA COMIDA ES <span class="text-warning">NUESTRO ARTE</span></h2>
      </div>
      <div class="col-sm pt-5 text-sm-left">
      <p class="syne-font">¿Quién es Foodies?</p>
      <p class="text-muted opensans">Elit irure ad nulla id elit laborum nostrud mollit irure. Velit reprehenderit sunt nulla enim aliquip duis tempor est culpa fugiat consequat culpa consectetur Lorem. Reprehenderit dolore culpa irure eiusmod minim occaecat et id minim ullamco. </p>
      <p class="font-weight-bold text-sm-left syne-font"><a href="#">Contáctanos</a></p>
      </div>
    </div>
    <!-- third section -->
     <div class="row mx-auto">
      <div class="col-sm pt-5">
        <h1 class="h2row3"><p>Estamos para ti</p></h1>
        <div class="row border border-dark">
        <div class="col-sm bg-dark pt-3">
          <p class="text-white syne-font"><span class="pr-3"><img src="../assets/icon1.png"></span>Para llevar</p>
        </div>
        <div class="col-sm pt-3">
          <p class="syne-font text-black"><span class="pr-3"><img src="../assets/icon2.png"></span>Domicilio</p>
        </div>
      </div>
        <div class="row">
          <div class="input-group">
          <input type="text" class="form-control" placeholder="Buscar nombre o dirección">
          <div class="input-group-append">
          <button class="btn btn-secondary" type="button">
          <i class="fa fa-search"></i>
          </button>
          </div>
          </div>
        </div>
      </div>
      <div class="col-sm pt-5">
      <img class="img-responsive img-fluid" src="../assets/map.png">
      </div>
    </div>
  <!-- fourth section -->
     <div class="row pt-3 mx-auto">
      <div class="col-sm">
       <img class="vector2 pl-5 d-none d-sm-block" src="../assets/vector2.png">
      </div>
     <div class="col-sm pt-5">
        <h2 class="h2row4"><p>“El mejor lugar para degustar en familia y amigos!”</p></h2>
        <p class="text-muted opensans">Es el mejor lugar al que he venido con mi familia, la comida es rica, sirven rápido y te atienden de la mejor manera. </p>
     </div>
     <div class="col-sm">
             <img class="img-responsive img-fluid d-none d-sm-block" src="../assets/bottle.png">
     </div>
    </div>

     <!-- fifth section -->
     <div class="row pt-3 bg-dark mx-auto">
         <div class="col-sm pt-3">
         <p class="text-white h2row5">Cuentanos tu experiencia</p>
         <p class="text-white opensans">Don't miss out on our great offers & Receive deals from all our
          top restaurants via e-mail.</p>
       </div>
    </div>
    <div class="row bg-dark pt-3 mx-auto">
         <div class="col-sm">
           <div class="form-group">
          <p class="text-left opensans"><label class="text-white" for="usr">Nombre y Apellido:</label></p>
          <input type="text" class="form-control" id="usr" placeholder="Tu nombre y apellido aqui">
          </div>
          <div class="form-group">
          <p class="text-left opensans"><label class="text-white" for="pwd">Correo electrónico:</label></p>
           <input type="password" class="form-control" id="pwd" placeholder="tucorreo@aqui">
          </div> 
         </div>
         <div class="col-sm">
            <div class="form-group">
            <p class="text-white text-left opensans">Mensaje:</p>
            <textarea class="form-control" rows="5" id="comment" placeholder="El día de ahora mi experiencia fue..."></textarea>
            <p class="text-right pt-2 opensans"><button type="button" class="btn btn-warning">Enviar comentarios</button></p>
            </div> 
         </div>
          </div>

 <!-- six section -->
     <div class="row pt-3 mx-auto">
       <div class="col-sm">
         <img class="img-responsive img-fluid" src="../assets/phone.png">
       </div>
       <div class="col-sm pt-3">
         <h2 class="text-sm-left h2row6">Obten más beneficios <mark class="mark">Descarga nuestra App</mark></h2>
         <div class="row pt-5 mx-auto">
           <div class="col-sm pt-4">
            <i class="fas fa-heart"></i>
            <h2>Solicita Rapido</h2>
           <p class="">Curabitur in eleifend turpis, id vehicula odio. Donec pulvinar tellus eget magna aliquet ultricies.</p>
           </div>
           <div class="col-sm pt-4">
            <i class="fas fa-heart"></i>
            <h2>Facil de usar</h2>
           <p class="">Curabitur in eleifend turpis, id vehicula odio. Donec pulvinar tellus eget magna aliquet ultricies.</p>
           </div>
         </div>
         <div class="row pt-4 mx-auto">
           <div class="col-sm">
            <i class="fas fa-heart"></i>
            <h2>Promociones especiales</h2>
           <p class="">Curabitur in eleifend turpis, id vehicula odio. Donec pulvinar tellus eget magna aliquet ultricies.</p>
         </div>
         </div>
       </div>
     </div>
     <div class="row mx-auto pt-4">
       <div class="col-sm">
        <p class="navbar-brand text-muted">Foodies</p>
       </div>
       <div class="col-sm"></div>
       <div class="col-sm pt-3">
         <img class="img-responsive img-fluid" src="../assets/store1.png">
       </div>
       <div class="col-sm pt-3">
            <img class="img-responsive img-fluid" src="../assets/store2.png">
       </div>
     </div>
<hr>
     <!-- Footer -->
<footer class="page-footer font-small">

  <!-- Copyright -->
  <div class="footer-copyright text-center py-3">© 2020 Copyright:
    <a href="mailto: davidoquem@gmail.com">David Melendez</a>
  </div>
  <!-- Copyright -->

</footer>
<!-- Footer -->

  </div>
</div>
</template>

<script>
export default {
  data () {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.cdnfonts.com/css/syne');
@import url('https://fonts.cdnfonts.com/css/open-sans');
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.4.0/css/font-awesome.css');
@import url(//db.onlinewebfonts.com/c/3724259186746d86859fbb0fde0fa44a?family=Druk+Text+Wide+Web+Medium);
@font-face {font-family: "Druk Text Wide Web Medium"; src: url("//db.onlinewebfonts.com/t/3724259186746d86859fbb0fde0fa44a.eot"); src: url("//db.onlinewebfonts.com/t/3724259186746d86859fbb0fde0fa44a.eot?#iefix") format("embedded-opentype"), url("//db.onlinewebfonts.com/t/3724259186746d86859fbb0fde0fa44a.woff2") format("woff2"), url("//db.onlinewebfonts.com/t/3724259186746d86859fbb0fde0fa44a.woff") format("woff"), url("//db.onlinewebfonts.com/t/3724259186746d86859fbb0fde0fa44a.ttf") format("truetype"), url("//db.onlinewebfonts.com/t/3724259186746d86859fbb0fde0fa44a.svg#Druk Text Wide Web Medium") format("svg"); } 


.testimonio {


  
  text-align: left;

}

.vector2 {
  transform: scaleX(-1);

}


.map {
  width: 824px;
  height: 600px;
}

.overimage {
  position: absolute;
  width: 500px;
  top: 350px;
  left: 250px;
  color: white;


}

.h2row1 {
font-family: Druk Text Wide Web Medium;
font-style: normal;
font-weight: bold;
font-size: 40px;
line-height: 50px;
color: black;
}

.h2row2 {
font-family: Druk Text Wide Web Medium;
font-style: normal;
font-weight: bold;
font-size: 40px;
text-align: left;
}

.h2row3 {
font-family: Druk Text Wide Web Medium;
font-style: normal;
font-weight: bold;
font-size: 30px;
line-height: 30px;
text-align: center;
color: black;
}

.h2row4 {
font-family: Druk Text Wide Web Medium;
font-style: normal;
font-weight: bold;
font-size: 30px;
line-height: 30px;
text-align: center;
color: black;
}

.h2row5 {
font-family: Druk Text Wide Web Medium;
font-style: normal;
font-weight: bold;
font-size: 30px;
line-height: 30px;
text-align: center;
color: black;
}

.h2row6 {
font-family: Druk Text Wide Web Medium;
font-style: normal;
font-weight: bold;
font-size: 35px;
line-height: 50px;
color: black;
}

.seccion1 {
background-image: url(../assets/vector1.png);
background-repeat: no-repeat;
position: absolute;
width: 800px;
height: 800px;
right: 0px;
top: 0px;

}

.mark {
  background-color: #FFD600;
  color: black;
}
.parrafo-row1 {
position: relative;
font-family: Druk Text Wide Web Medium;
font-style: normal;
font-weight: bold;
font-size: 40px;
color: black;
top: -700px;

}

.parrafo-row2 {
position: relative;
font-family: Druk Text Wide Web Medium;
font-style: normal;
font-weight: bold;
font-size: 40px;
line-height: 60px;
color: black;
right: 300px;

}

.syne-font {
font-family: Syne;
font-style: normal;
font-weight: bold;
font-size: 22px;
line-height: 26px;

}

.opensans {
font-family: Open Sans;


}


.vector1{
position: relative;
width: 800px;
height: 800px;
left: 545px;
top: -60px;
  

}

.ham {

  width: 400px;


}



.col-right {
background-image: url(../assets/vector1.png);
background-repeat: no-repeat;
position: absolute;
width: 900px;
height: 900px;
left: 1130px;
top: 0px;
}

.containerbox1 {
position: absolute;
width: 1426.29px;
height: 1021.04px;
left: 88.71px;
top: -200px;
}

.navbarbox1 {
position: absolute;
width: 775px;
height: 27px;
left: 101px;
top: 57px;
}



.navbar-brand {

font-family: Druk Text Wide Web Medium;
font-style: normal;
font-weight: bold;
font-size: 27px;
color: black;
}

.navtext {

font-family: Syne;
font-style: normal;
font-weight: bold;
font-size: 20px;

color: black;
}

.navtext-black {
  color: black;
}

</style>
