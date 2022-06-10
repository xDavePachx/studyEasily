<template>
  <div class="tutores"> 
  <div id="nav">
      <img src="@/assets/m1.png" id="icon" alt="User Icon" width="100" /> |
      <router-link to="/">Register</router-link> |
      <router-link to="/about">Home</router-link> |
      <router-link to="/ayuda">Ayuda</router-link> |
      <router-link to="/tutores">Tutores</router-link>
      
    </div>
    <router-view />
    <img src="@/assets/m8.jpeg" width="60%" />
  
  
  </div>
</template>


<style scoped>
</style>