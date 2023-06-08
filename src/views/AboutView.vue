<template>
  <!-- stylist _______________________________________________________________________________________-->
  <div class="stylist-container">
    
      
      <div class="portrait1"></div>
      <div class="texi-container" style="margin-left:20px;">
          <h2>Help our readers</h2>
          <p>Books help children make sense of the world around them</p>
          
        </div>
    </div>

    
    <div class="stylist-container">
      <div class="texi-container" style="margin-left:20px;">
        <h2>Dont just borrow</h2>
        <p>Share what you have , lets grow togther</p>
        
      </div>
      
      <div class="portrait2"></div>
      
    </div>


    <div class="stylist-container">
    
      
      <div class="portrait3"></div>
      <div class="texi-container" style="margin-left:20px;">
          <h2>Become a Prime</h2>
          <p>By contributing , you become our prime memeber</p>
          
        </div>
    </div>


    <div class="contai">
      <h1>Contribute today</h1>
      <h2>Lets change the world for better and greater</h2>
      <button class="fade-button" >Join now</button>
    
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
  /* Stylis__________________________________________________________________________________________*/

  
  .stylist-container {
      background-color: black;
      display: flex;
      align-items: center;
      justify-content: left;
      border-radius: 40px;
      
    }
    
    .portrait1 {
      width: 400px;
      height: 540px;
      background-image:url("../assets/444.jfif");
      margin-left:10px;
      border-radius: 7px;
      margin-bottom: 20px;
      margin-top: 20px;
      /* You can add an image or other styling to the portrait rectangle ../assets/16.jpg */
    }

    .portrait2 {
      width: 400px;
      height: 540px;
      background-image:url("../assets/222.png");
      margin-left:10px;
      border-radius: 7px;
      margin-bottom: 20px;
      margin-top: 20px;
      /* You can add an image or other styling to the portrait rectangle ../assets/16.jpg */
    }

    .portrait3 {
      width: 400px;
      height: 540px;
      background-image:url("../assets/111.jfif");
      margin-left:10px;
      border-radius: 7px;
      margin-bottom: 20px;
      margin-top: 20px;
      /* You can add an image or other styling to the portrait rectangle ../assets/16.jpg */
    }
    
    .texi-container {
      color: white;
      padding-left: 10px;
      margin-left:10px;
      padding-right:60px;
    }
    
    .texi-container h2 {
      font-size: 74px;
      margin-bottom: 10px;
      color:#bae0ff;
    }
    
    .texi-container p {
      font-size: 26px;
      color:#e7f4ff;
    }
    
    



    .contai {
      text-align: center;
      
    }
    
    .contai h1 {
      font-size: 100px;
      margin-bottom: 10px;
      color:rgb(124, 167, 255);
    }
    
    .contai h2 {
      font-size: 38px;
      margin-top: 0;
      color:rgb(175, 199, 255);
    }
    
    
    
  
  
  
  
  
  
  
  
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
    
    
    
    
  
  
  </style>