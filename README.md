<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>




     <!-- LINKS OF BOOTSTapP -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js" integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN" crossorigin="anonymous"></script>


<script src="quiz.js"></script>


<link rel="stylesheet" href="style1.css">


<style>
 
    h1{
        color: yellow;
        background-color: rgb(141, 136, 136);
        font-size: 40px;
        margin-left: 400px;
        
        width: 500px;
    }
    /* *{
      background-color: rgb(164, 155, 155);
    } */
    p{
        display: flexbox;
        margin-top: 20px;
        color: black;
        font: 30px;
        margin-left: 5px;
        background-color: aqua;
    }
    .important{
        color: rgb(7, 212, 14);
        background-color: rgb(0, 0, 0);
        font-size: 40px;
        margin-left: 500px;
        margin-top: 20px;
        border: 4px solid black;
         border-radius: 20px;        
        width: fit-content;
    }
    .swiper{
      width: 80%;
      height: fit-content;
      align-items: center;
      justify-content: center;
      display: flexbox;
      background-color: rgb(13, 12, 12);
    }
    .swiper-slide-img{
      width: 100%;

    }
   th{
   background-color: rgb(9, 223, 20);
   }
   td{
    background-color: rgb(11, 231, 187);
   }
    /* *{
        background-image: url(youtube.jpg);
        background-repeat: no-repeat;
        background-size: cover;
    } */
   .swiper {
  width: 600px;
  height: 300px;
}
.container{
  margin-top: 15px;
}
table{
  margin-top: 20px;
}
th,td{
  padding: 15px;
  border: 2px solid black;
}
.container_2{
  margin-top: 20px;
 

 
}
:hover.animation{
  width: 200px;
  height: 200px;
  background-color:aqua;
 border: 4px solid rebeccapurple;
 animation-name: op;
 animation-timing-function: ease-in-out;
 direction: alternate;
 animation-duration: 5s;
 animation-iteration-count: 10;

}
@keyframes op {
  0%{
    width: 200px;
  height: 200px;
  background-color:aqua;
  border: 4px solid rebeccapurple;
  }
  25%{
    width: 300px;
  height: 300px;
  border-radius: 50%;
  background-color:aqua;
  border: 4px solid rebeccapurple;
  }
  50%{
    width: 200px;
  height: 200px;
  background-color:aqua;
  border: 4px solid rebeccapurple;
  }
  75%{
    width: 300px;
  height: 300px;
  border-radius: 50%;
  background-color:aqua;
  border: 4px solid rebeccapurple;
  }
  100%{
    width: 200px;
  height: 200px;
  background-color:aqua;
  border: 4px solid rebeccapurple;
  }
}
.fact{
  margin-left: 550px;
  font-size: 30px;
  width: fit-content;
  border-radius: 20px;
 
  border: 3px solid greenyellow;
  background-color: #a1dd15;
}
</style>
<link
rel="stylesheet"
href="https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.css"
/>

</head>
<body>
 
    <h1>Welcome to Crazy maths!</h1>





    <!-- NAVBAR BY BOOTSRAP -->
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid">
          <a class="navbar-brand" href="https://www.youtube.com/@crazymaths24/videos"><img style="border-radius: 50%;" height="30px" width="30px" src="crazy.jpg" alt=""></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="https://www.youtube.com/@crazymaths24/about">link of youtube</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Dropdown
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="https://www.youtube.com/@crazymaths24/about">About</a></li>
                  <li><a class="dropdown-item" href="https://www.youtube.com/@crazymaths24/about">pdf of important chapter</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="https://www.youtube.com/@crazymaths24/about">important telegram links</a></li>
                </ul>
              </li>
              <!-- <li class="nav-item"> -->
                <!-- <a class="nav-link disabled">Disabled</a> -->
              <!-- </li> -->
            </ul>
            <form class="d-flex" role="search">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
          </div>
        </div>
      </nav>









      <div class="img">
      <!-- <img width="100%" style="ima" src="youtube.jpg" alt=""></div> -->
      <p>hi my name is vinayak tiwari! i read in class 8. recently i open youtube channell crazy maths but subscriber do not increase . but i do not stop for work i create this website for helping you in this website you get update related to jee mains,jee advanced,important pdf of chapters and telegram channell. </p>

      <div class="important">important Updates</div>




      <!-- SWIPER KA CODE -->
     
<script src="https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.js"></script>


<!-- Slider main container -->
<div class="container">
<div class="swiper">
  <!-- Additional required wrapper -->
  <div class="swiper-wrapper">
    <!-- Slides -->






    <div class="swiper-slide"><img style="height: 100%; width: 100%;" src="ramanujan.jpg" alt=""></div>
   
    <div class="swiper-slide"><img style="height: 100%; width: 100%;"  src="youtube.jpg" alt=""></div>

    <div class="swiper-slide"><img style="height: 100%; width: 100%;"  src="nasa.jpg" alt=""></div>

    <div class="swiper-slide"><img style="height: 100%; width: 100%;"  src="nasa.jpg" alt=""></div>

    <div class="swiper-slide"><img style="height: 100%; width: 100%;"  src="CIRCLE THUMBNAIL.png" alt=""></div>

    <div class="swiper-slide"><img style="height: 100%; width: 100%;"  src="cat.gif" alt=""></div>

    <div class="swiper-slide"><a href="https://youtu.be/5dNpQrO7AN4"><img style="height: 100%; width: 100%;"  src="limit.jpg" alt=""></a></div>





    ...
  </div>
  <!-- If we need pagination -->
  <div class="swiper-pagination"></div>

  <!-- If we need navigation buttons -->
  <div class="swiper-button-prev"></div>
  <div class="swiper-button-next"></div></div>
  <script>const swiper = new Swiper('.swiper', {
    // Optional parameters
    // direction: 'vertical',
    autoplay:{
      delay:3000,
      disableInteraction:false,
    },
    loop: true,
  
    // If we need pagination
    pagination: {
      el: '.swiper-pagination',
      clickable:true,
    },
  
    // Navigation arrows
    navigation: {
      nextEl: '.swiper-button-next',
      prevEl: '.swiper-button-prev',
    },
  
   
  });
  
  </script>
  <div class="fact">Intresting Facts</div>
 <table>
  
  <tr>
    <th>maths</th>
    <th>science</th>
    <th>hindi</th>
    <th>english</th>
    <th>SST</th>
    <th>computer science</th>
  </tr>
  <tr>


    <!-- maths -->
    <td>
      <ul>in this section we se important facts about maths
        <li>The word “hundred” comes from the old Norse term, “hundrath”, which actually means 120 and not 100.</li>
        <li>In a room of 23 people there's a 50% chance that two people have the same birthday</li>
        <li>In a room of 23 people there's a 50% chance that two people have the same birthday</li>
        <li>In a room of 23 people there's a 50% chance that two people have the same birthday</li>
      </ul>

<!-- SCIENCE -->

      <td>
        <ul>in this section we se important facts about science
          <li>The oceans produce the majority of the oxygen on Earth. ...</li>
          <li>Bananas are radioactive. .</li>
          <li>Water can exist in three states at the same time. ...</li>
          <li>Water can exist in three states at the same time. ...</li>
          <li>Water can exist in three states at the same time. ...</li>
        </ul>
      </td>


      <!-- HINDI -->
      <td>
        <ul>in this section we se important facts about science
          <li>The oceans produce the majority of the oxygen on Earth. ...</li>
          <li>Bananas are radioactive. .</li>
          <li>Water can exist in three states at the same time. ...</li>
          <li>Water can exist in three states at the same time. ...</li>
          <li>Water can exist in three states at the same time. ...</li>
        </ul>
      </td>




       <!-- ENGLISH -->

      <td>
        <ul>in this section we se important facts about science
          <li>The oceans produce the majority of the oxygen on Earth. ...</li>
          <li>Bananas are radioactive. .</li>
          <li>Water can exist in three states at the same time. ...</li>
          <li>Water can exist in three states at the same time. ...</li>
          <li>Water can exist in three states at the same time. ...</li>
        </ul>
      </td>



      <!-- SST -->
      <td>
        <ul>in this section we se important facts about science
          <li>The oceans produce the majority of the oxygen on Earth. ...</li>
          <li>Bananas are radioactive. .</li>
          <li>Water can exist in three states at the same time. ...</li>
          <li>Water can exist in three states at the same time. ...</li>
          <li>Water can exist in three states at the same time. ...</li>
        </ul>
      </td>


      <!-- COMPUTER SCIENCE -->
      <td>
        <ul>in this section we se important facts about science
          <li>The oceans produce the majority of the oxygen on Earth. ...</li>
          <li>Bananas are radioactive. .</li>
          <li>Water can exist in three states at the same time. ...</li>
          <li>Water can exist in three states at the same time. ...</li>
          <li>Water can exist in three states at the same time. ...</li>
        </ul>
      </td>
    </td>
  </tr>
  
 </table>
 <div style="background-color: aqua; margin-top: 10px;" class="content">OUR FREE CLASSES CLICK ON IMAGE TO WATCH FULL VIDEO IN FREE </div>
  <div class="container_2">
  <a href="https://www.youtube.com/@crazymaths24/videos"><img src="limits photos.webp" alt=""></a>
  <a href="https://www.youtube.com/@crazymaths24/videos"><img src="olympiad_2.webp" alt=""></a>
  <a href="https://www.youtube.com/@crazymaths24/videos"><img src="rolles.webp" alt=""></a>
  <a href="https://www.youtube.com/@crazymaths24/videos"><img src="tangent_2.webp" alt=""></a>
  </div>

 <!-- QUIZ FOR MY WEBSITE -->

 <style>
  
body {
  background-color: #f2f2f2;
  font-family: Arial, sans-serif;
}

h1 {
  color: #2c3e50;
  text-align: center;
  margin-top: 50px;
}

#quiz-form {
  margin-top: 30px;
  width: 1200px;
  
  /* max-width: 500px; */
  margin: 0 auto;
  padding: 20px;
  border: 1px solid #ccc;
  border-radius: 5px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
  background-color: #fff;
  color: #333;
 
}

#quiz-form h2 {
  font-size: 20px;
  font-weight: bold;
  margin-top: 30px;
  color: #2c3e50;
}

#quiz-form p {
  font-size: 18px;
  margin-top: 20px;
  color: #a1dd15;
}

#quiz-form label {
  font-size: 16px;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
  color: #0bb8c4;
}

#quiz-form input[type="radio"] {
  margin-right: 10px;
}

#submit-button {
  background-color: #2ecc71;
  color: #fff;
  border: none;
  border-radius: 5px;
  padding: 10px 20px;
  font-size: 18px;
  cursor: pointer;
  margin-top: 20px;
}

#submit-button:hover {
  background-color: #08e765;
}

#results {
  margin-top: 20px;
  font-size: 24px;
  font-weight: bold;
  text-align: center;
  color: #437ab0;
  border: 3px solid black;
  background-color: rgb(98, 179, 152);
}
.quiz-container{
  margin-top: 30px;
}
.form{
  align-content: center;
}
.details{
  border: 3px solid blue;
  background-color: rgb(113, 138, 161);
  margin-top: 20px;
}
.top{
  margin-top: 5px;
  font-size: 25px;
  margin-left: 15px;
}
.about{
  margin-left: 500px;
  font-size: 30px;
  margin-top: 5px;
  margin-bottom: 5px;
}
 </style>

 <script>

function checkAnswers() {
  var quizForm = document.getElementById("quiz-form");
  var resultsDiv = document.getElementById("results");
  var score = 0;

  // Check the answer to the first question
  var q1Answer = quizForm.elements["q1"].value;
  if (q1Answer === "a") {
    score += 1;
  }

  // Check the answer to the second question
  var q2Answer = quizForm.elements["q2"].value;
  if (q2Answer === "b") {
    score += 1;
  }

  // Check the answer to the third question
  var q3Answer = quizForm.elements["q3"].value;
  if (q3Answer === "a") {
    score += 1;
  }

  // Display the results to the user
  resultsDiv.innerHTML = "Congratulation Your scored " + score + " out of 3.";

  // Disable the quiz form to prevent further submissions
  quizForm.disabled = true;
}
 </script>


 <!-- <div class="quiz-container"> -->
  <div class="QUIZ"><h1>Quiz</h1></div>



  <div class="form">
  <form id="quiz-form" onsubmit="checkAnswers(); return false;">
    <h2>Question 1</h2>
    <p>A number N in base 10, is 503 in base b and 305 in base b + 2. What is the product of the digits of N?</p>
    <label><input type="radio" name="q1" value="a">64</label><br>
    <label><input type="radio" name="q1" value="b">45</label><br>
    <label><input type="radio" name="q1" value="c">89</label><br>

    <h2>Question 2</h2>
    <p> Let ABCD be a rectangle in which AB + BC + CD = 20 and AE = 9, where E is the midpoint of the side BC. Find the area of the rectangle?</p>
    <label><input type="radio" name="q2" value="a">12</label><br>
    <label><input type="radio" name="q2" value="b">19</label><br>
    <label><input type="radio" name="q2" value="c">24</label><br>

    <h2>Question 3</h2>
    <p> Let ABCD be a rectangle in which AB + BC + CD = 20 and AE = 9, where E is the midpoint of the side BC. Find the area of the rectangle.</p>
    <label><input type="radio" name="q3" value="a">18</label><br>
    <label><input type="radio" name="q3" value="b">17</label><br>
    <label><input type="radio" name="q3" value="c">14</label><br>

    <button type="submit">Submit Answer</button>
  </form></div>

  <div id="results"></div>
<!-- </div> -->


<!-- <div class="about">ABOUT US</div> -->
<div class="details">
  <div class="about">ABOUT US</div>
  <div class="top">thanks for visting my website</div>
  <div class="top">Our goal is sptread efucation</div>
 <div class="top"> youtube channell link <a href="https://www.youtube.com/@crazymaths24/videos">Crazy Mths</a></div>
 <div class="top">&copy; 2023 CrazyMaths.com</div>
</div>





</body>
</html>

