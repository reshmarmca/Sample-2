<template>
<div>
     <div class="second">
     <img class="ss" src="http://getwallpapers.com/wallpaper/full/a/e/4/1084504-rose-gold-wallpapers-1920x1080-for-ipad.jpg">
    

    <nav class="navbar navbar-expand-lg navbar-light ">
 
  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <div class="collapse navbar-collapse" id="navbarNav">


    <ul class="nav navbar-nav ml-auto">
      <li class="nav-item ">
        <a class="nav-link"  href="#" style="color:DodgerBlue;">Home <span class="sr-only"></span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#" style="color:DodgerBlue;margin-left:30px;">Services</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#" style="color:DodgerBlue;margin-left:30px;">Works</a>
      </li>
            <li class="nav-item">
        <a class="nav-link " href="#" style="color:DodgerBlue;margin-left:30px;">Blog</a>
      </li>
      <li class="nav-item">
        <a class="nav-link " href="#" style="color:DodgerBlue;margin-left:30px;">Contacts</a>
      </li>
    </ul>
    </div>
  </div>
</nav>
  
  
<div class="card" style="width: 18rem;">
  <img class="card-img-top" src="../assets/t22.jpg" alt="Card image cap">

  <div class="card-body">
    <h5 class="card-title" style="color:DodgerBlue;;">Romulus Whitaker</h5>
    <p class="card-text" style="text-align:justify;"><font size="2">Romulus Earl Whitaker is an Indian herpetologist, 
    wildlife conservationist and founder of the Madras Snake Park, 
    The Andaman and Nicobar Environment Trust, and the Madras Crocodile Bank Trust.</font></p>
    <a href="#" class="btn btn-primary">GET IN TOUCH</a>
  </div>

</div>


<div class="flip-card" style="position:absolute;top:20%;right:5%;">
  <div class="flip-card-inner">
    <div class="flip-card-front">
      <img class="rounded-circle" src="../assets/t24.jpeg" alt="Avatar" style="width:300px;height:300px;">
    </div>
    <div class="flip-card-back">
      <h1>Romulus Whitaker</h1> 
      <p style="align:justify;">Whitaker was the founder director of the Snake Park in Chennai. 
      The park was conceived to rehabilitate the Irula tribe who are known for their expertise in catching snakes. 
      The tribals were left jobless after the ban of snake trading.</p>
    </div>
  </div>
</div>
 </div>

 <div style="background-color:white;margin-top:550px;">
             <h1 style="color:DodgerBlue;">About</h1>
             <br>

            <div class="row">
              <div class="col-sm-6" style="background-color:white;"> 
                <img  src="../assets/t24.jpg"  style="width:400px;height:230px;" alt="twitter">
              </div>
              <div class="col-sm-6" style="background-color:white;"> 

 
      
<p style="margin-top:25px;"><u>Born</u>	23 May 1943 (age 76)
United States<br>
<u>Nationality</u>	Indian<br>
<u>Education</u>	BSc (wildlife management)<br>
Alma mater	Pacific Western University<br>
<u>Occupation</u>	Herpetologist, Conservationist<br>
<u>Known for</u>	Wildlife film-making, Herpetology, Rolex Award</p>    
    
  
</div> 



              </div>

              <div class="row">
              
              <div class="col-sm-6" style="background-color:white;"> 

 
      
<p style="margin-top:25px;text-align:justify;padding-left:60px;padding-top:30px;">Whitaker was the founder director of the Snake Park in Chennai. The park was conceived to rehabilitate the Irula tribe who are known for their expertise in catching snakes. The tribals were left jobless after the ban of snake trading. Whitaker
 helped the Irula tribe to get involved in extracting snake venom used for the production of antivenom drugs.</p>    
    
  
</div> 

<div class="col-sm-6" style="background-color:white;"> 
                <img  src="../assets/t26.jpg"  style="width:400px;height:230px;" alt="twitter">
              </div>

              </div>
            </div>

</div>
       
</div>

         
</template>

<script>



</script>


<style scoped>
.second{
  position:absolute;
  top:0;
}
.ss{
width:100%;
height:500px;

}
.navbar{
  position:absolute;
  top:0;
 width:100%;
 
}
.card{
  position:absolute;
  top:60px;
  left:60px;
 }

.flip-card {
  background-color: transparent;
  width: 300px;
  height: 300px;
  perspective: 1000px;
}

.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.6s;
  transform-style: preserve-3d;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
}

.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

.flip-card-front, .flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  backface-visibility: hidden;
}

.flip-card-front {
  background-color: #bbb;
  color: black;
}

.flip-card-back {
  background-color: #2980b9;
  color: white;
  transform: rotateY(180deg);
}

</style>
