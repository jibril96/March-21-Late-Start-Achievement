<template>
 <div>
    <TheHeader :title = "pageHeader"  :description = "pageDescription" />
    <main>
      <p>This is on the home page</p>
      </main>
      <TheFooter />
  </div>
</template>

<script setup>
import TheHeader from './components/TheHeader.vue';
import TheFooter from './components/TheFooter.vue';
const pageHeader = 'HomePage!';
const pageDescription = 'This is the landing page';
</script>

<style>
 #pp {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>