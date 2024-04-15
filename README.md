<!DOCTYPE html>
<html>
 <head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width,  initial-scale=1">
 	<title> Code lesson</title>
 	<link rel="stylesheet" href="style.css">
 </head>
  <script src="https://kit.fontawesome.com/cd0e3109d3.js"crossorigin="anonymous"></script>
       <!-- ligne Font Awesome avant script pour permettre display des images-->

 <body>
   <div class="container">
      <div class="card-white" id="firstdiv">
         Bienvenue sur mon profil !
       </div>
      <img src="Image/Photo professionnelle.png" id="pdp">
      <p id="VB">Valentin Betton</p>
      <div class="card-white">
         <h3>Etudes <i class="fa-solid fa-school"></i></h3>
         <p>Classe préparatoire ECS lycée Touchard-Washington</p>
            <p>Programme Grande Ecole d'Audencia</p>
      </div>
      <div class="card-white">
         <h3>Finance <i class="fa-solid fa-coins"></i></h3>
         <p>J'ambitionne de travailler dans le secteur de la finance de marché. Afin de m'y former je travaille en tant que trésorier dans mon association et j'ai choisi le programme de managmement approfondi en M1. Je projette pour ce faire de suivre le MSc in Financial Analysis and Investment Management d'Audencia.</p>
       </div>
      <div class="card-white">
         <h3>Mes passions 
            <a <i class="fa-solid fa-basketball"></i></a>
            <a <i class="fa-solid fa-calculator"></i></a></i></i></h3> 
     <p>Je suis joueur et fan de basketball et j'adore les jeux mathématiques.</p>
       </div>
      <div class="card-white" id="lastdiv">
          Follow me
          <p>
            <a href="https://www.facebook.com/search/top/?q=Valentin%20Dom" target="_blank"><i class="fa-brands fa-facebook"></i></a>
            <a href="https://www.instagram.com/valentin_betton/" target="_blank"><i class="fa-brands fa-square-instagram"></i></a>
            <a href="https://www.linkedin.com/in/valentin-betton-a862a0296/" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
         </p>
         </div>
      
   </div>
 </body>
</html>
body{ 
   background: rgb(240, 250, 250);
   text-align: center;
   margin: 60px 0px;
   padding: 0px 20px;
}

p{
   color: black;
}


#pdp {
   border-radius: 30%;
   border: 3px hidden darkblue;
   width: 20%;
}

#VB {
   font-size: 30px;
}


#firstdiv {
   font-size: 30px;
}

#lastdiv a{
   padding: 15px;
}


.container {
  width: 700px;
  margin: 40px auto;
  border-radius: 1%;
  border: 1px solid black;
   box-shadow: 10px 10px 30px rgba(0,0,0,0.1);
}

.card-white{
   color: blue;
   border-radius: 10px;
   box-shadow: 10px 10px 30px rgba(0,0,0,0.1);
   margin: 40px;
   padding: 10px;

}

.fa-brand{
   margin: 10px;
}

@media (max-width: 960px) {
  .container {
    width: 80%;
  }
}
