<template>
  <div class="bottom_inner">
    <div class="container">
      <div class="bottom__content">
        <span class="garant">Мы гарантируем лучший уровень сотрудничества!</span><br />
        <span class="experience">Наш опыт позволяет решить любые ваши задачи!</span><br />
        <div class="line" align="center"></div>
        <br />
        Звоните<br />
        <br />
        <p class="phone"><PhoneNumber phone_num="8-968-641-31-87" /></p>
        <br />
        <br />
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  background-color: #f4f4f4;
}

.bottom__content {
  text-align: center;
}

.bottom_inner {
  padding-top: 78px;
}

.garant {
  font-size: 28px;
}

.experience {
  font-size: 20px;
}

.line {
  border-bottom: 3px solid red;
  width: 80px;
  display: inline-block;
}

.phone {
  font-size: 30px;
}
</style>