<script setup>
  
</script>
<template>
  <div class="welcome-section">
    <div class="card">
      <h1>Верещака Артем</h1>
      <h3>Golang Developer</h3>
      <div class="card-checkbox" ><label id="card-checkbox">
									<input type="checkbox" id="one" checked disabled>
									<div class="slider"></div>
                  
								</label>
                <p>В поиске работы!</p></div>
      
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
  margin: 10px 0 25px 0;
} 

.card h1 {
  margin: 0;
  font-size: 32px;
  font-weight: bold;
  line-height: 32px;
}

.card h3 {
  margin: 5px 0;
  font-size: 18px;
  font-weight: 600;
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




.card-checkbox {
  display: flex;
  align-items: center;
 
}
.card-checkbox p {
    font-family: 'Noto Sans', Courier, monospace;
    margin-left: 10px;
  
}
#card-checkbox {
  display: inline-block;
  height: 1.9em;
  position: relative;
  vertical-align: middle;
  width: 3.5em;
}

#card-checkbox input {
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

