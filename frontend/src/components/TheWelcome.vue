<script setup>

</script>
<template>
  <div class="welcome-section">
    <div class="card">
      <h1>Верещака Артем</h1>
      <h3>Golang Dev</h3>
      <label class="switch">
									<input type="checkbox">
									<div class="slider"></div>
								</label>
    </div>
    <p>
      Я решил сменить карьеру и окунуться в мир IT, чтобы заниматься тем, что меня действительно увлекает — программированием.
      Моя цель — стать профессиональным разработчиком на Go, и я активно работаю над этим.
      Здесь вы найдете информацию обо мне и моих проектах.
      Этот проект выполнен на Vue 3 + Vite и развернут с помощью Docker.
    </p>
  </div>
</template>
  
<style scoped>


.card {
 display: flex;
 flex-direction: column;
 align-items: flex-start;
}

.card h1 {
  margin: 0;
  font-size: 32px;
  font-weight: bold;
  line-height: 32px;
}

.card h3 {
 
  font-size: 18px;
}

input[type="checkbox"] {
  margin: 20px 0;
}

label {
  font-size: 16px;
  color: #fff;
  cursor: pointer;
}

p {
  font-size: 18px;
  line-height: 1.6;
  color: #555;
}





.switch {
  display: inline-block;
  height: 1.9em;
  position: relative;
  vertical-align: middle;
  width: 3.5em;
}

.switch input {
  display: none;
  margin: 0;
}

.slider {
  background-color: #ccc;
  border-radius: 1em;
  bottom: 0;
  cursor: pointer;
  left: 0;
  position: absolute;
  right: 0;
  top: 0;
  transition: all 0.4s ease 0s;
}

.slider::before {
  background-color: white;
  border-radius: 0.7em;
  bottom: 4px;
  content: "";
  height: 1.4em;
  left: 4px;
  position: absolute;
  transition: all 0.4s ease 0s;
  width: 1.4em;
}

input:checked + .slider {
  background-color: #40bb93;
}

input:checked + .slider:before {
  -webkit-transform: translateX(1.5em);
  -ms-transform: translateX(1.5em);
  transform: translateX(1.5em);
}
</style>

