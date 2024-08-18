<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <div class="wrapper">
      <HelloWorld msg="Hello, i am Vereshaka Artem" />
      
      <nav>
        <RouterLink to="/">Главная</RouterLink>
        <RouterLink to="/about">О себе</RouterLink>
        <RouterLink to="/work">Портфолио</RouterLink>
      </nav>
    </div>
  </header>
  <transition name="fade" mode="out-in">
    <RouterView />
  </transition>
</template>

<style scoped>
.wrapper { display: flex;
  justify-content: space-between ;
  align-items: flex-end;
}
header {box-shadow: 0px 1px 0px 0px rgba(0, 0, 0, 0.2);

}
.fade-enter-active, .fade-leave-active {
  transition: opacity 0.5s ease;
}
.fade-enter-from, .fade-leave-to {
  opacity: 0;
}


</style>
