<template>
  <div class="header">
    <img
      class="logo-ironhack"
      src="../../../img/ironhack-logo-negro1-removebg-preview.png"
    />
    <div class="div-hamburguer-menu">
    <img src = "../../../img/images-removebg-preview.png" alt="hamburguer-menu" class="hambuerguer-menu"/>
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
@import url(https://fonts.googleapis.com/css?family=Raleway);

.logo-ironhack {
  width: 5%;
  height: 5%;
}
.header{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    width: 90%;
    margin: 0 auto;
    margin-top: 2%;
}

.div-hamburguer-menu{
    
    width: 5%;
    height: 7%;
}
.hambuerguer-menu{
width: 100%;
height: 100%;
}
</style>
