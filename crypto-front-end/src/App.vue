<script setup>
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "@/components/HelloWorld.vue";
</script>

<template>
  <header>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
      <nav class="navbar navbar-light" style="background-color: #e3f2fd;">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/user"> User</RouterLink>
        <RouterLink to="/crypto"> crypto</RouterLink>
         <!-- <RouterLink to="/firebase"> firebase</RouterLink> -->
      </nav>
     
  </header>

 <body class="container">
   
  <RouterView />
 </body>
</template>

<style>
table{
  display: block;
}

</style>
