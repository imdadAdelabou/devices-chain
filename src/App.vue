<template>
  <header class="clearfix">
    <button id="hamburger__button">
      <div class="hamburger__bar"> </div>
      <div class="hamburger__bar"> </div>
      <div class="hamburger__bar"> </div>
    </button>
  </header>
  <Home></Home>
  <!-- <footer> 
  </footer> -->
</template>

<script>
import Home from './views/Home';
export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
body {
  padding: 0;
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0;
}

header {
  margin: 0;
  background-color: #A6C8FB;
}

.hamburger__bar {
  width: 22px;
  height: 3px;
  border-radius: 10px;
  background-color: black;
  margin-bottom: 2px;
}
#hamburger__button {
  cursor: pointer;
  border: none;
  float: left;
  background: none;
  margin-top: 20px;
}
.clearfix:after{
    content: "";
    display: block;
    clear: both;
}
@media screen and (max-width: 480px) {
  body {
    
  }
  
}
</style>
