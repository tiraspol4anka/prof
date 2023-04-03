<template>
  <div class="logo__item">
    <div class="container">
      <div class="bg_logo">
        <a href="#" class="logo">
          <img class="logo_items" src="../assets/images/logo.jpg"
        /></a>
        <div class="logo_title">
          <p>Профи</p>
          <p><PhoneNumber phone_num="8-968-641-31-87" /></p>
        </div>
      </div>
    </div>
  </div>
</template>



<style scoped>
.bg_logo {
  background-image: url(../assets/images/bg_logo.jpg);
  min-height: 425px;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: top center;
}

.logo_title {
  font-size: 24px;
}

.bg_logo {
  padding-top: 114px;
  padding-left: 260px;
}

@media (max-width: 1024px) {
  .bg_logo {
    padding-top: 114px;
    padding-left: 10%;
  }

  .logo_title {
    font-size: 24px;
    
  }

  .bg_logo {
    background-image: url(../assets/images/bg_logo.jpg);
    min-height: 425px;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: top center;
  }
}
</style>