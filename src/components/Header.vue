<script>
export default {
  name: 'Header'
}
</script>

<template>
  <header class="header container_header">
    <div class="header-nav container">
      <div class="header-left">
        <div class="logo">
          <img src="../assets/image/logo.svg" alt="Logo">
        </div>
        <a href="#" class="city_change">Санкт-Петербург</a>
      </div>
      <div class="header-center">
        <div class="header-menu">
          <a href="#">Доставка</a>
          <a href="#">Оплата</a>
          <a href="#">О нас</a>
          <a href="#">Связаться</a>
        </div>
      </div>
      <div class="header-right">
        <div class="header-call">
          <a href="tel:88005300060" class="phone-number">8 800 530-00-60</a>
          <a id="form_cell_to_me" href="javascript:void(0)">Перезвоните мне</a>
        </div>
        <div class="header-icons">
          <a href="/"><img src="../assets/image/lk.svg" alt="Icon"></a>
          <a href="/"><img src="../assets/image/cart.svg" alt="Icon"></a>
        </div>
      </div>
    </div>
    <div class="container header_content">
      <h1>
        Организация <br>
        корпоративного питания <br>
        в Санкт-Петербурге
      </h1>
      <a href="javascript:void(0)" class="header_btn">Получить предложение</a>
    </div>
    <h2 class="container title_section_eat">Пример ежедневного <span class="orange">рациона</span></h2>
    <div class="container dishes_wrapper">
      <div class="dishes_single">
        <p class="dishes_title">Понедельник</p>
        <div class="dishes_info">
          <p class="dishes_energy">900 ккал</p>
          <p class="dishes_number">3 блюда</p>
        </div>
        <div class="dishes_image">
          <img src="../assets/image/eat.png">
        </div>
      </div>
      <div class="dishes_single">
        <p class="dishes_title">Понедельник</p>
        <div class="dishes_info">
          <p class="dishes_energy">900 ккал</p>
          <p class="dishes_number">3 блюда</p>
        </div>
        <div class="dishes_image">
          <img src="../assets/image/eat.png">
        </div>
      </div>
      <div class="dishes_single">
        <p class="dishes_title">Понедельник</p>
        <div class="dishes_info">
          <p class="dishes_energy">900 ккал</p>
          <p class="dishes_number">3 блюда</p>
        </div>
        <div class="dishes_image">
          <img src="../assets/image/eat.png">
        </div>
      </div>
      <div class="dishes_single">
        <p class="dishes_title">Понедельник</p>
        <div class="dishes_info">
          <p class="dishes_energy">900 ккал</p>
          <p class="dishes_number">3 блюда</p>
        </div>
        <div class="dishes_image">
          <img src="../assets/image/eat.png">
        </div>
      </div>
      <div class="dishes_single">
        <p class="dishes_title">Понедельник</p>
        <div class="dishes_info">
          <p class="dishes_energy">900 ккал</p>
          <p class="dishes_number">3 блюда</p>
        </div>
        <div class="dishes_image">
          <img src="../assets/image/eat.png">
        </div>
      </div>
      <div class="dishes_single">
        <p class="dishes_title">Понедельник</p>
        <div class="dishes_info">
          <p class="dishes_energy">900 ккал</p>
          <p class="dishes_number">3 блюда</p>
        </div>
        <div class="dishes_image">
          <img src="../assets/image/eat.png">
        </div>
      </div>
      <div class="dishes_single">
        <p class="dishes_title">Понедельник</p>
        <div class="dishes_info">
          <p class="dishes_energy">900 ккал</p>
          <p class="dishes_number">3 блюда</p>
        </div>
        <div class="dishes_image">
          <img src="../assets/image/eat.png">
        </div>
      </div>
    </div>
  </header>
</template>

<style scoped>
.dishes_single{
  background: linear-gradient(0deg, #F3FFEF 0%, #EEFFE1 100%);
  max-width: 218px;
  border-radius: 10px;
  padding: 18px 22px;
}
.dishes_wrapper{
  display: flex;
  gap: 12px;
}
.dishes_title{
  font-size: 22px;
  font-weight: 700;
  margin-bottom: 15px;
}
.dishes_image{
  max-width: 150px;
  margin: 0 auto;
}
.dishes_energy{
  font-weight: 700;
  background: #92DD34;
  padding: 5px 9px;
  font-size: 16px;
  border-radius: 10px;
}
.dishes_number{
  font-size: 14px;
  color: #12221A;
  font-weight: 400;
}
.dishes_info{
  display: flex;
  margin-bottom: 40px;
  align-items: center;
  gap: 15px;
}
.title_section_eat{
  margin-top: 135px;
  margin-bottom: 35px;
}
.title_section_eat > span{
  font-weight: 600;
  font-size: 28px;
}
  .header_btn{
    margin-top: 40px;
    padding: 14px 30px;
    background: #FFA333;
    color: #fff;
    display: block;
    max-width: 275px;
    border-radius: 10px;
  }
  .header-icons{
    display: flex;
    gap: 10px;
    margin-right: 15px;
    position: relative;
    top: 3px;
  }
  .header-nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    border-radius: 90px;
    max-height: 60px;
    background: #fff;
  }
  .header-call{
    max-height: 82px;
    margin-right: 60px;
  }
  #form_cell_to_me{
    color: #FFA333;
    border-bottom: 1px dotted #FFA333;
  }
  .header_content{
   margin-top: 56px;
  }
  .logo{
    margin-right: 37px;
  }
  .logo img{
    position: relative;
    top: 4px;
  }
  .header{
    background-image: url('../assets/image/bg.png');
    background-repeat: no-repeat;
  }
  .container_header{
    max-width: 1859px;
    margin: 0 auto;
    margin-top: 16px;
    padding-top: 13px;
  }
  .header-left {
    display: flex;
    align-items: center;
  }
  .header-menu {
    display: flex;
    align-items: center;
    gap: 20px;
    margin-left: 60px;
  }
  .header-menu a {
    text-decoration: none;
    color: #282828;
    font-weight: 500;
  }

  .header-right {
    display: flex;
    align-items: center;
  }

  .phone-number {
    margin-right: 20px;
  }
</style>