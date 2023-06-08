<template>
  

  <div class="navbar">
    <div class="navbar-brand">ENLIGHT</div>
    <div class="navbar-links">
      

      <router-link to="/"><a href="#">Home</a></router-link>
      <router-link to="/abt"><a href="#">Books</a></router-link>
        <a href="https://lmsa.firelight0130.repl.co/">Search</a>
    </div>
</div>

<!-- hero section ------------------------------------------------------------ -->






  <router-view/>
</template>











<style>
@import url('https://fonts.googleapis.com/css2?family=Kanit&display=swap');

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

</style>















<script>





</script>