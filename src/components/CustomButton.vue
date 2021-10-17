<template>
    <button class="custom-btn">{{content}}</button>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans&display=swap');

.custom-btn {
  width: 200px;
  height: 50px;
  top: 250px;
  left: 50px;
  border-radius: 30px;
  border: none;
  font-size: 20px;
  color: #71A4F1;
  cursor: pointer;
  font-family: 'Josefin Sans';
  font-weight: 500;
  margin-bottom: 70px;
}
</style>
    
<script>

export default {
    name: "CustomButton",
    props: {
        content: {type: String, required: true}
    }
}
</script>
