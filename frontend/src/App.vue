<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import FooterBar from './components/Footer.vue'



</script>

<template>
  
  <header >
    
      <HelloWorld msg="Hello!" />
      
      <nav>
        <RouterLink to="/">main</RouterLink>
        <RouterLink to="/about">about</RouterLink>
        <RouterLink to="/work">workflow</RouterLink>
      </nav>
    
  </header>
  <div class="content">
    <transition name="fade" mode="out-in">
    <RouterView />
  </transition>
  </div>
  <FooterBar />
  
</template>

<style scoped>
header { display: flex;
  justify-content: space-between ;
  align-items: center;
}

.fade-enter-active, .fade-leave-active {
  transition: opacity 0.5s ease;
}
.fade-enter-from, .fade-leave-to {
  opacity: 0;
}
a {
    text-decoration: none;
    color: #333;
    border-bottom: 1px solid transparent;
    transition: border-color 0.3s;
    font-size: 22px;
    font-weight: bold;
    
}
a + a{
  margin-left: 30px;
}

a:hover {
    border-bottom: 1px solid #333;
}
.router-link-active {
    border-bottom: 1px solid #e20000;
}

.content {
  flex-grow: 1;
 margin: 50px 10px 0 10px;
  max-width: 900px;
  margin: 40px auto;
  padding: 20px;
  background-color: #ffffff;
  border-radius: 12px;
  box-shadow: 0 6px 20px rgba(0, 0, 0, 0.15);
  transition: transform 0.3s ease, box-shadow 0.3s ease;


}
footer {
  flex-shrink: 0;
}

</style>
