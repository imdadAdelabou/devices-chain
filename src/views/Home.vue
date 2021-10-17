<template>
  <div class="home">
   <div id="firstBody">
      <img src="../assets/logo_device.png" />
      <p>Votre sécurité, notre priorité</p>
      <CustomButton content="S’enregistrer"> </CustomButton>
      <CustomButton content="Se connecter"> </CustomButton>
  </div>
  </div>
</template>

<script>
// @ is an alias to /src
import CustomButton from '../components/CustomButton';
export default {
  name: "Home",
  components: {
   CustomButton
  },
};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans&display=swap');
#firstBody {
  width: 100%;
  
  background-color: #A6C8FB;
}

#firstBody  p {
  color: white;
  font-weight: bold;
  font-family: 'Josefin Sans';
  font-size: 20px;
  padding-top: 0;
  margin-bottom: 70px;
}

footer {
  width: 100%;
  height: 100px;
  background-color: black;
  bottom: 0;
  position: absolute;
  padding: 0;
}
.clearfix:after{
    content: "";
    display: block;
    clear: both;
}
</style>
