<!-- <template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png"> 
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <p>hi</p>
  </div>
</template> -->

<!-- <script>
// // @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

// export default {
//   name: 'HomeView',
//   components: {
//     HelloWorld
//   }
// }
</script> -->

<!-- <style>
.home{
  height:10000px;

}
</style> -->

<!-- hero section ------------------------------------------------------------ -->
<template>
<div class="container">
  <div class="hero">
<div class="image-container">
  <img src="../assets/333.jpg" alt="Image">
<p></p>
</div>
</div>
<div class="content-container">
  <h2 class="image-title">E N L I G H T</h2>
  <h3 class="image-creator">Enlighten yoursself </h3>
  <p class="image-description">Books and Novels are not to be read on screens, it is something to be felt, something to fall for, a reality break from the digital lights we all surf in. Books holds certain keys for your wildest imaginations</p>
 <div class="bttn"><router-link to="/abt"><button class="fade-button">Know more</button></router-link></div>
</div>

</div>

<!-- sticy navbar -------------------------------------------------------------------------->
<nav class="sticky-navbar">
  <ul class="nav-links">
    <li><a><router-link to="/abt"><a href="#">Book now</a></router-link></a></li>
    <li><a><router-link to="/about"><a href="#">Contribute</a></router-link></a></li>
  </ul>
</nav>

<!-- courosel --------------------------------------->
<div class="chill-container">
  <p class="head">OUR TOP FEATURED</p>

  <p class="descp">Have a look on our exciting and most anticipated books early bookings now available</p>
  <router-link to="/abt"><button class="fade-button">Read all</button></router-link>
  
</div>

<!---cards--------------------------------------------------------------->
<div class="boxy-container">
  <div class="cards">
    <div class="black-box1"></div>
    <h3>Book name</h3>
    <p>AUTHOR</p>
    <p>A book is a medium for recording information in the form of writing or images, </p>
    <router-link to="/abt"><a href="#">Read More</a></router-link>
    
  </div>
  <div class="cards">
    <div class="black-box2"></div>
    <h3>Book name</h3>
    <p>AUTHOR</p>
    <p>A book is a medium for recording information in the form of writing or images, </p>
    <router-link to="/abt"><a href="#">Read More</a></router-link>
  </div>
  <div class="cards">
    <div class="black-box3"></div>
    <h3>Book Name</h3>
    <p>AUTHOR</p>
    <p>A book is a medium for recording information in the form of writing or images, </p>
    <router-link to="/abt"><a href="#">Read More</a></router-link>
  </div>
  <div class="cards">
    <div class="black-box4"></div>
    <h3>Book Name</h3>
    <p>AUTHOR</p>
    <p>A book is a medium for recording information in the form of writing or images, </p>
    <router-link to="/abt"><a href="#">Read More</a></router-link>
  </div>
  
</div>



<!-- courosel --------------------------------------->

<div class="chilli-container">
  <p class="headi">OUR MOST READ</p>

  <p class="descpi">Reading is not just reciting, it is to enulf in multiverse of advetures</p>
  <button class="fade-button" style="margin-left:10px;">Read all</button>
</div>






<div class="containeri">
  <main class="gridi">
    <article><div class="bga">
      <img src="../assets/5.jpg" alt="Sample photo"></div>
      <div class="text">
        <h3 style="margin-top:1px;margin-bottom:1px; font-size:32px;">Book name </h3>
        <h2 style="margin-top:10px;margin-bottom:1px; font-size:20px;">Author name</h2>
        <p style="margin-top:36px;">A book that takes you to the journey of your imagination</p>
        <a href="#" class="btn btn-primary btn-block">Book now</a>
        <p style="font-weight:bold;color:#0080ff;">most viewed 1.2k tims</p>
      </div>
    </article>
    <article>
      <div class="bga">
        <img src="../assets/6.jpg" alt="Sample photo"></div>
  
      <div class="text">
        <h3 style="margin-top:1px;margin-bottom:1px; font-size:32px;">Book name </h3>
        <h2 style="margin-top:10px;margin-bottom:1px; font-size:20px;">Author name</h2>
        <p style="margin-top:36px;">A book that takes you to the journey of your imagination</p>
        <a href="#" class="btn btn-primary btn-block">Book now</a>
        <p style="font-weight:bold;color:#0080ff;">most viewed 1.2k tims</p>
      </div>
    </article>
    <article>
      <div class="bga">
        <img src="../assets/7.jpg" alt="Sample photo"></div>
  
      <div class="text">
        <h3 style="margin-top:1px;margin-bottom:1px; font-size:32px;">Book name </h3>
        <h2 style="margin-top:10px;margin-bottom:1px; font-size:20px;">Author name</h2>
        <p style="margin-top:36px;">A book that takes you to the journey of your imagination</p>
        <a href="#" class="btn btn-primary btn-block">Book now</a>
        <p style="font-weight:bold;color:#0080ff;">most viewed 1.2k tims</p>
      </div>
    </article>
    <article>
      <div class="bga">
        <img src="../assets/8.jpg" alt="Sample photo"></div>
  
      <div class="text">
        <h3 style="margin-top:1px;margin-bottom:1px; font-size:32px;">Book name </h3>
        <h2 style="margin-top:10px;margin-bottom:1px; font-size:20px;">Author name</h2>
        <p style="margin-top:36px;">A book that takes you to the journey of your imagination</p>
        <a href="#" class="btn btn-primary btn-block">Book now</a>
        <p style="font-weight:bold;color:#0080ff;">most viewed 1.2k tims</p>
      </div>
    </article>
    <article>
      <div class="bga">
        <img src="../assets/9.jpg" alt="Sample photo"></div>
  
      <div class="text">
        <h3 style="margin-top:1px;margin-bottom:1px; font-size:32px;">Book name </h3>
        <h2 style="margin-top:10px;margin-bottom:1px; font-size:20px;">Author name</h2>
        <p style="margin-top:36px;">A book that takes you to the journey of your imagination</p>
        <a href="#" class="btn btn-primary btn-block">Book now</a>
        <p style="font-weight:bold;color:#0080ff;">most viewed 1.2k tims</p>
      </div>
    </article>
    <article>
      <div class="bga">
        <img src="../assets/10.jpg" alt="Sample photo"></div>
  
      <div class="text">
        <h3 style="margin-top:1px;margin-bottom:1px; font-size:32px;">Book name </h3>
        <h2 style="margin-top:10px;margin-bottom:1px; font-size:20px;">Author name</h2>
        <p style="margin-top:36px;">A book that takes you to the journey of your imagination</p>
        <a href="#" class="btn btn-primary btn-block">Book now</a>
        <p style="font-weight:bold;color:#0080ff;">most viewed 1.2k tims</p>
      </div>
    </article>
    <article>
      <div class="bga">
        <img src="../assets/11.jpg" alt="Sample photo"></div>
  
      <div class="text">
        <h3 style="margin-top:1px;margin-bottom:1px; font-size:32px;">Book name </h3>
        <h2 style="margin-top:10px;margin-bottom:1px; font-size:20px;">Author name</h2>
        <p style="margin-top:36px;">A book that takes you to the journey of your imagination</p>
        <a href="#" class="btn btn-primary btn-block">Book now</a>
        <p style="font-weight:bold;color:#0080ff;">most viewed 1.2k tims</p>
      </div>
    </article>
    <article>
      <div class="bga">
        <img src="../assets/12.jpg" alt="Sample photo"></div>
  
      <div class="text">
        <h3 style="margin-top:1px;margin-bottom:1px; font-size:32px;">Book name </h3>
        <h2 style="margin-top:10px;margin-bottom:1px; font-size:20px;">Author name</h2>
        <p style="margin-top:36px;">A book that takes you to the journey of your imagination</p>
        <a href="#" class="btn btn-primary btn-block">Book now</a>
        <p style="font-weight:bold;color:#0080ff;">most viewed 1.2k tims</p>
      </div>
    </article>
  </main>
</div>




<!-- stylist _______________________________________________________________________________________-->
<div class="stylist-container">
  
  <div class="tex-container">
    <h2>Not just a LIBRARY</h2>
    <p>READ EXPLORE AND CONTRIBUTE, THE WORLD OF BOOKS AWAITS YOUR PRESENCE</p>
    <button class="fade-button" style="margin-left:0.001px; margin-top:20px;">Read all</button>
  </div>
  <div class="portrait"></div>
  
</div>



<!-- courosel-part-2 --------------------------------------->

<div class="chilli-containerz">
  <p class="headiz">MUST READSS!!!</p>

  <p class="descpiz">You just cant miss reading these books, just jump on already</p>
  <button class="fade-button" style="margin-left:10px;">Read all</button>
</div>






<div class="containeri" >
  <main class="gridi" style="padding-top:100px;">
    <article>
      <div class="bga">
        <img src="../assets/13.jpg" alt="Sample photo"></div>
  
      <div class="text">
        <h3 style="margin-top:1px;margin-bottom:1px; font-size:32px;">Book name </h3>
        <h2 style="margin-top:10px;margin-bottom:1px; font-size:20px;">Author name</h2>
        <p style="margin-top:36px;">A book that takes you to the journey of your imagination</p>
        <a href="#" class="btn btn-primary btn-block">Book now</a>
        <p style="font-weight:bold;color:#0080ff;">most viewed 1.2k tims</p>
      </div>
    </article>
    <article>
      <div class="bga">
        <img src="../assets/14.jpg" alt="Sample photo"></div>
  
      <div class="text">
        <h3 style="margin-top:1px;margin-bottom:1px; font-size:32px;">Book name </h3>
        <h2 style="margin-top:10px;margin-bottom:1px; font-size:20px;">Author name</h2>
        <p style="margin-top:36px;">A book that takes you to the journey of your imagination</p>
        <a href="#" class="btn btn-primary btn-block">Book now</a>
        <p style="font-weight:bold;color:#0080ff;">most viewed 1.2k tims</p>
      </div>
    </article>
    <article>
      <div class="bga">
        <img src="../assets/15.jpg" alt="Sample photo"></div>
  
      <div class="text">
        <h3 style="margin-top:1px;margin-bottom:1px; font-size:32px;">Book name </h3>
        <h2 style="margin-top:10px;margin-bottom:1px; font-size:20px;">Author name</h2>
        <p style="margin-top:36px;">A book that takes you to the journey of your imagination</p>
        <a href="#" class="btn btn-primary btn-block">Book now</a>
        <p style="font-weight:bold;color:#0080ff;">most viewed 1.2k tims</p>
      </div>
    </article>
    <article>
      <div class="bga">
        <img src="../assets/16.jpg" alt="Sample photo"></div>
  
      <div class="text">
        <h3 style="margin-top:1px;margin-bottom:1px; font-size:32px;">Book name </h3>
        <h2 style="margin-top:10px;margin-bottom:1px; font-size:20px;">Author name</h2>
        <p style="margin-top:36px;">A book that takes you to the journey of your imagination</p>
        <a href="#" class="btn btn-primary btn-block">Book now</a>
        <p style="font-weight:bold;color:#0080ff;">most viewed 1.2k tims</p>
      </div>
    </article>
    
  </main>
</div>

<div class="contain">
  <h1>E N L I G H T</h1>
  <h2>Enlight yourself in this ocean of books called Library</h2>
  <button class="fade-button" >Enlighten</button>

</div>



<footer class="footer">
  <div class="footer-content">
    <p>&copy; 2023 ENLIGHT. All rights reserved.</p>
    <ul class="footer-links">
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      
    </ul>
  </div>
</footer>




















</template>











<style>
@import url('https://fonts.googleapis.com/css2?family=Kanit&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Pacifico&family=Sacramento&display=swap');

#app {
font-family: Avenir, Helvetica, Arial, sans-serif;
-webkit-font-smoothing: antialiased;
-moz-osx-font-smoothing: grayscale;
 
color: #88c3ff;
}
/*NAVBAR ******************************************************************************************/
.navbar {
font-family: 'Kanit', sans-serif;
position: fixed;
top: 0;
left: 0;
width: 100%;
height: 50px;
background-color: #f1f1f1;
display: flex;
justify-content: space-between;
align-items: center;
padding-left:49px;
z-index: 30;

}

.navbar-brand {
font-size: 20px;
font-weight: bold;
}

.navbar-links {
display: flex;
justify-content: flex-end;
align-items: center;
padding-right:65px;
}

.navbar-links a {
margin-left: 2px;
margin-right:18px;
text-decoration: none;
color: #333;
font-size: 16px;
}

/*image css ***********************************************************************************/

.container {
display: flex;
align-items: flex-start;
gap:10px;
padding-top:40px;

background-color: black;
}

.hero{
background-color: white;
width:500px;
padding-right: 40px;
}

.image-container img {
width: 200px;
height: auto;
align-items:center;
justify-content: center;
display:flex;
padding-top:30px;
width:400px;
padding-left:30px;
text-align: center;
border-radius: 220px 40px 220px 20px; 
}
.image-container p{

margin-left:160px;
margin-top:7px;
font-weight: bold;
color: #043363;
} 

.content-container {
display: flex;
flex-direction: column;
gap: 0.1px;
padding-left:100px;
font-size:50px
}

.image-title {
font-size: 74px;
font-weight: bold;
margin-top: 200px;
margin-bottom: 0px;
}

.image-creator {
font-size: 38px;
margin-top: -7px;
margin-bottom: 0px;
color: #03417e;
}

.image-description {
font-size: 16px;
margin-top: 20px;
margin-bottom: 0px;
padding-right: 170px;
color: #d4e9ff;
}




/*sticy navbar**************************************************************************************/
.sticky-navbar {
  position: sticky;
  top: 0;
  background-color: #f8f8f8;
  padding-top:59px;
  padding-bottom:10px;
  background-color: black;
  color:rgb(159, 250, 255);
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  z-index: 10;
}

.nav-links {
  display: flex;
  justify-content: center;
  list-style: none;
  margin: 0;
  padding: 0;
}

.nav-links li {
  margin: 0 60px;
}

.nav-links a {
  color: #afdbff;
  text-decoration: none;
  font-weight: bold;
}

.nav-links a:hover {
  color: #007bff;
}

/*courosel*********************************************************************************/

.chill-container {
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100px;
  flex-direction: column;
  padding-bottom:200px;
}



.head {
  font-family: 'Bree Serif', serif;
  margin-top:190px;
  font-size: 96px;
 
  margin-bottom: 1px;
}

.descp {
  font-size: 18px;
  margin-top: 1px;
}

/**card boxes**********************************************************/

.boxy-container {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-gap: 10px;
  padding-top:20px;
 
  justify-content: center;
  align-items: center;
  color:#b9dbff;
  
}

.cards{
  padding-top:20px;
  padding-right:10px;
  padding-left: 10px;
  background-color: #0c0c0c;
  border: 1px solid #008cff;
  border-radius: 10px;
  padding-bottom:30px;
  text-align: center;
}

.black-box1 {
  width: 200px;
  border-radius: 10px;
  height: 150px;
  background-image: url("../assets/16.jpg");
  background-color: rgb(255, 255, 255);
  margin: 0 auto 10px;
}
.black-box2 {
  width: 200px;
  border-radius: 10px;
  height: 150px;
  background-image: url("../assets/333.jpg");
  background-color: rgb(255, 255, 255);
  margin: 0 auto 10px;
}
.black-box3 {
  width: 200px;
  border-radius: 10px;
  height: 150px;
  background-image: url("../assets/13.jpg");
  background-color: rgb(255, 255, 255);
  margin: 0 auto 10px;
}
.black-box4 {
  width: 200px;
  border-radius: 10px;
  height: 150px;
  background-image: url("../assets/222.png");
  background-color: rgb(255, 255, 255);
  margin: 0 auto 10px;
}
h3 {
  font-size: 34px;
  font-weight: bold;
}

p {
  font-size: 16px;
  margin-bottom: 10px;
}

a {
  text-decoration: none;
  color: rgb(0, 102, 255);
}

/*courosel*********************************************************************************/

.chilli-container {
  text-align: left;
  display: flex;
  justify-content: left;
  align-items:left;
  height: 100px;
  flex-direction: column;
  padding-bottom:200px;
  padding-left:30px;
}



.headi {
  font-family: 'Bree Serif', serif;
  margin-top:120px;
  font-size: 136px;
 
  margin-bottom: 1px;
}

.descpi {
  font-size: 28px;
  margin-top: 1px;
  padding-left:10px;
}


/**our most viewed**********************************************************************************/

.gridi {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  grid-gap: 20px;
  align-items: stretch;
  padding-top:170px;
}
.bga{
  background-color: rgba(202, 234, 255, 0.468);
  border-radius: 16px;
  padding-bottom: 9px;
  padding-top: 9px;
}
.gridi > article {
  border: 3px solid #89b1ff;
  box-shadow: 2px 2px 6px 0px rgba(0, 0, 0, 0.002);
  border-radius: 20px;
  background-color: rgb(255, 255, 255);
}

.gridi > article img {
  max-width: 100%;
  border-radius: 9px;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 135px;
  margin-left: 75px;
}

.gridi .text {
  padding: 20px;
}

/* Stylis__________________________________________________________________________________________*/


.stylist-container {
  background-color: black;
  display: flex;
  align-items: center;
  justify-content: left;
  padding: 20px;
  margin-top:30px;
  border-radius: 20px;
}

.portrait {
  width: 400px;
  height: 540px;
  background-image:url("../assets/111.jfif");
  margin-left:10px;
  border-radius: 7px;
  margin-bottom: 20px;
  margin-top: 20px;
  /* You can add an image or other styling to the portrait rectangle ../assets/16.jpg */
}

.tex-container {
  color: white;
  padding-left: 10px;
  margin-left:10px;
  padding-right:60px;
}

.tex-container h2 {
  font-size: 74px;
  margin-bottom: 10px;
  color:#bae0ff;
}

.tex-container p {
  font-size: 16px;
  color:#e7f4ff;
}





/*courosel*********************************************************************************/

.chilli-containerz {
  text-align: left;
  display: flex;
  justify-content: left;
  align-items:left;
  height: 100px;
  flex-direction: column;
  padding-bottom:200px;
  padding-left:30px;
}



.headiz {
  font-family: 'Bree Serif', serif;
  margin-top:70px;
  font-size: 136px;
 
  margin-bottom: 1px;
}

.descpiz {
  font-size: 28px;
  margin-top: 1px;
  padding-left:10px;
}











.contain {
  text-align: center;
  
}

.contain h1 {
  font-size: 204px;
  margin-bottom: 10px;
  color:rgb(124, 167, 255);
}

.contain h2 {
  font-size: 28px;
  margin-top: 0;
  color:rgb(175, 199, 255);
}








/*FOOTER________________________________________________________________________*/
.footer {
  margin-top:100px;
  background-color: #afdbff;
  color:#003468;
  padding: 20px;
  text-align: center;
}

.footer-content {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.footer p {
  margin-bottom: 10px;
}

.footer-links {
  list-style: none;
  padding: 0;
  margin: 0;
}

.footer-links li {
  display: inline;
  margin: 0 10px;
}

.footer-links li a {
  color: #4a4d59;
  text-decoration: none;
}

.footer-links li a:hover {
  text-decoration: underline;
}








/*BUTTON----------------------------------------------------------------*/
.bttn{
  margin-left:0.01px;
  
  }
  .fade-button {
  padding-top:7px;
  padding-bottom:7px;
  background-color: #000000;
  border-radius: 40px;
  background-color: transparent;
  border: 2px solid #70b3ff;
    
    color: #70b3ff;
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
    transition: background-color 1.3s ease, color 1.3s ease;
  margin:auto;
  padding-left:30px;
  padding-right:30px;
  }
  
  
  
  .fade-button:hover{
    border: 2px solid #70b3ff00;
    color: #69b9ff;
  }
  

  
</style>















<script>





</script>
