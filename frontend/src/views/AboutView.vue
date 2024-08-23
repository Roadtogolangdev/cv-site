<template>
  <div class="about">
    <h1>Описание опыта работы:</h1>

    <div class="about-block">
      <p class="about-title">Энергостройкомплекс</p>
      <p class="about-text">Организация работы фирмы на всех уровнях</p>
      <ul>
        <li>Поиск и налаживание контактов с заказчиками и подрядными организациями</li>
        <li>Постоянная актуализация ассортимента материалов и цен на услуги</li>
        <li>Формирование налоговой отчетности и работа с кадровыми документами</li>
        <li>Участие и сопровождение тендерных активностей</li>
      </ul>
      <p class="about-text">На данный момент работа в целом автоматизирована. В силу специфики выполняемых работ, а именно "строительно-монтажные работы в сфере электроэнергетики", крайне редко появляются задачи, требующие полного погружения в процесс.</p>
      <p class="about-text">Исходя из достигнутых результатов, принял решение о смене сферы деятельности.</p>
      <p class="about-text">Если это читает HR-специалист или мой будущий работодатель, уверяю, что нет никаких проблем с выходом из организации и дальнейшим трудоустройством у вас.</p>
    </div>

    <div class="about-block">
      <p class="about-title">Roky.rocks, веб-студия, Самара</p>
      <p class="about-text">Опыт работы, о котором мне очень приятно вспоминать.</p>
      <p class="about-text">Крутые руководители Саша и Женя. Они многому меня научили, и я старался выкладываться, чтобы продемонстрировать свою преданность "камню".</p>
      <ul>
        <li>Верстка страниц, приложений и компонентов с использованием HTML, CSS и JS</li>
        <li>Эксперименты с библиотеками и фреймворками для улучшения пользовательского опыта (Vue, React, Three.js, D3.js и другие)</li>
        <li>Запуск с нуля сайта по доставке еды в г. Самара (адаптивная верстка, платежные API, интеграция с БД)</li>
        <li>Работа в команде из дизайнеров, бэкенд-разработчиков, менеджера проекта с использованием Jira, Notion и тайм-трекеров</li>
      </ul>
      <p class="about-text">Полученный опыт в этой веб-студии помог мне познакомиться с миром IT, направлениями и задачами, которые в нем существуют. Это дало хорошую базу для дальнейшего развития и становления конкурентоспособным специалистом.</p>
    </div>

    <div class="about-block">
      <h1>В силу загруженности, этот раздел еще будет заполняться</h1>
      
    </div>
  </div>
</template>

<style>

.about-block {
  margin-bottom: 30px;
  position: relative;
  padding: 20px;
  background: #f3f4f6;
  border-radius: 10px;
 
}

.about-title {
  font-size: 22px;
  color: #2980b9;
  margin-bottom: 15px;
  font-weight: bold;
  position: relative;
}

.about-title::after {
  content: '';
  display: block;
  width: 60px;
  height: 3px;
  background-color: #2980b9;
  margin-top: 5px;
  border-radius: 2px;
}

.about-text {
  font-size: 18px;
  line-height: 1.8;
  margin-bottom: 15px;
}

ul {
  list-style-type: disc;
  margin: 15px 0 15px 20px;
  padding: 0;
  font-size: 18px;
}

ul li {
  margin-bottom: 10px;
  position: relative;
}



@media (min-width: 1024px) {
  .about {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}
</style>

