
<template>
  <div id="app" class="container-fluid">
       <hr>
      <Accueil msg="Bienvenue sur mon portfolio"/>
        <img class="headline img-responsive center-block" src="./assets/mario_avatar.png" alt="logo_header" width="300">
        <hr>
      <br>
      <div class="cover">
      </div>
      <hr>
      <br>
      <!-- Début à propos de moi -->
      <div class="container cover_img" id="apropos">
        <br>
        <br>
       <h1>A Propos de moi</h1>
       <br>
       <hr>
        <div class="row">
          <div class="container col-4 img-responsive center-block"><img src="./assets/retro_gaming_logo.png" alt="A Propos de moi" width="350"></div>
          <div class="container col-8img-responsive center-block">
            <br>
              <div class="container">

                <p>Développeur web (Backend (symfony 4) et frontend(Vue JS)) et aussi mobile(IOS & Android) curieux, motivé et passionné par les nouvelles technologies et aussi le DEEP LEARNING, j'aime les applications simples, rapides et efficaces.</p>

                  <p>Actuellement en licence professionnelle informatique à l'IUT 1 de Grenoble, je suis déterminé à acquérir des bases solides et devenir le meilleur dans mon domaine qui est l'informatique.</p>

                  <p>Je n'ai pas peur de relever des défis parce que c'est comme ça que l'on devient meilleur dans ce que l'on fait !</p>    
              </div>
                
             <br> 
             <br> 
             <h5>Web Design</h5>
             <div class="progress">
             <div class="progress-bar progress-bar-striped progress-bar-animated bg-danger" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 60%">60%</div>
             </div>
             <br> 
             <br>
              <h5>Developpement Informatique</h5>
             <div class="progress">
              <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 80%">80%</div>
             </div> 
             <br> 
             <br>
              <h5>Deep Learning</h5>
              <div class="progress">
              <div class="progress-bar progress-bar-striped progress-bar-animated bg-success" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 50%">50%</div>
             </div> 
             <br> 
             <br>
           
          </div> 
          
        </div>
        <a class="btn btn-success" href="cv.html" target="_blank">Voir mon CV</a>
        <br>
        <br>
        </div>
        <!-- Fin à propos de moi -->
      <br>
      <br>
     
      <div class="container cover2">
       
      </div>
      <br>
      <br>
      
      <!-- début langages -->

      <div class="container cover_img" id="langages">
        <br>
        <br>
        <h1>Mes langages utilises</h1>
        <hr>
          <!-- Example row of columns -->
          <div class="row">
            <div class="col-md-4">
              <h2> Web <i class="fas fa-code"></i></h2>
              <p>
                <ul>
                  <li>HTML 5</li>
                  <li>CSS 3</li>
                  <li>Boostrap 4</li>
                  <li>Sass</li>
                  <li>Vue JS</li>
                  <li>PHP (Symfony 4 / Laravel)</li>
                  <li>Ruby on rails</li>
                  <li>Git</li>
                  <li>Kraken</li>
                </ul>
                </p>
            </div>
            <div class="col-md-4">
              <h2>Mobile Native et Hybride<i class="fas fa-mobile-alt"></i></h2>
              <p>
                <ul>
                  <h6>Android</h6>
                  <li>Android Studio</li>
                  <li>Java</li>
                  <li>XML</li>
                </ul>

                <ul>
                  <h6>IOS</h6>
                  <li>X Code</li>
                  <li>Swift</li>
                </ul>
                <ul>
                  <h6>Hybride</h6>
                  <li>Ionic</li>
                </ul>

                <ul>
                  <h6>UI</h6>
                  <li>Adobe XD</li>
                  <li>Photoshop</li>
                </ul>
              </p>
            </div>
            <div class="col-md-4">
              <h2>Deep Learning<i class="fas fa-atom"></i></h2>
              <p>
                <ul>
                  <li>Anaconda Navigator</li>
                  <li>Python 3.5</li>
                  <li>Spyder</li>
                </ul>
              </p>
            </div>
          </div>
        </div>

        <!-- Fin langages -->  
       <br>
        
        <div class="container cover3">
       
        </div>

        <br>
        <br>

        <!-- Début etudes -->

        <div class="container cover_img" id="etudes">
        <br>
        <br>
          <h1>Etudes</h1>
        <hr>

        <div class="container text-left">

        <ul>
          <li>
              <span></span>
              <h1 class="text">Licence Professionnelle Informatique</h1>
              <div class="">IUT 1 Grenoble</div>
              <div class="">Developpement web, androîd et IOS</div>
              <div class="time">
                  <span>2018 - 2019</span>
              </div>
          </li>
          <br>
          <br>
          <li>
              <span></span>
              <h1 class="text">2 eme Annee de Brevet de Technicien Superieur Systeme Numerique</h1>
              <div class="">Lycée du Grésivaudan Meylan</div>
              <div class="">Informatique et Réseau</div>
              <div class="time">
                  <span style="">2017 - 2018</span>
              </div>
          </li>
          <br>
          <br>
          <li>
              <span></span>
              <h1 class="text">1 ere Annee de Brevet de Technicien Superieur Systeme Numerique</h1>
              <div class="">Lycée du Grésivaudan Meylan</div>
              <div class="">Informatique et Réseau</div>
              <div class="time">
                  <span>2016 - 2017</span>
              </div>
          </li>
          <br>
          <br>
          <li>
              <span></span>
              <h1 class="text">Terminale STI2D (Sciences et Technologies de l'Industrie et du Developpement Durable)</h1>
              <div class="">Lycée Vaucanson Grenoble</div>
              <div class="">Système Informatique et Numérique</div>
              <div class="time">
                  <span>2015 - 2016</span>
              </div>
          </li>

        </ul>  
        </div>
        <br>
        <br>          
        </div>

        <!-- Fin études -->  
      <br>
        <br> 
      <div class="container cover4">
       
      </div>
       <br>
       <br>

      <div class="container cover_img">
      <br>
      <h1>Jouer a Super Mario Bros !</h1>
      <a class="btn btn-danger" href="/mario/game.html" target="_blank">Jouer</a>
      <br>
      <br>
      </div>
      <br> 
      <div class="container cover4">
       
      </div>
       <br>
       <br>
    
    <button onclick="topFunction()" id="myBtn" title="Go to top" style="display: block;margin-bottom: 40px"><i class="fas fa-arrow-up"></i></button>

      <!-- Fin Contact -->  
      <br>
      <br>
      <footer class="container">
        <div class="float-center" >
          <p>© René Mumba Kibutika - Développeur FullStack 2017-2018</p>
        </div>
        
      </footer>

  </div>
</template>

<script>
import Accueil from './components/Accueil.vue'

export default {
  name: 'app',
  components: {
    Accueil
  }
}
</script>

<style>
@font-face {
   font-family: 'SMB';
   src:  local('SuperMarioBros.'),
   url('./assets/fonts/SuperMarioBros.ttf') format('truetype');
   font-weight: normal;
  font-style: normal;
   }


#app {
  font-family: 'Press Start 2P', 'Indie Flower', 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}


.text {
  font-size: 20px;
}

ul li {
  list-style:none;
}
.cover_img {
  background-color: #dbc960; 
}
.cover {
    width: 100%;
    height: 800px;
    background-image: url("./assets/gaming.jpg");
    background-size: cover;
    background-color: white;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);

  }

  .cover2 {
    width: 100%;
    height: 100px;
    background-image: url("./assets/mario_world.jpg");
    background-size: cover;
    background-color: white;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);

  }

    .cover3 {
    width: 100%;
    height: 100px;
    background-image: url("./assets/mario_world.jpg");
    background-size: cover;
    background-color: white;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);

  }


    .cover4 {
    width: 100%;
    height: 100px;
    background-image: url("./assets/mario_world.jpg");
    background-size: cover;
    background-color: white;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);

  }
  h1, .competences {
  text-decoration: underline;
  font-weight: bold;
  color:#ff5050;
}

p {
  text-align: left
}

#myBtn {
  display: none;
  position: fixed;
  bottom: 20px;
  right: 30px;
  z-index: 1;
  font-size: 18px;
  border: none;
  outline: none;
  background-color: red;
  color: white;
  cursor: pointer;
  padding: 15px;
  border-radius: 35px;
}


#myBtn:hover {
  background-color: #555;
}
</style>
