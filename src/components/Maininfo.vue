<script>
export default {
  name: 'Maininfo',
}
</script>

<template>
  <div class="maininfo container">
    <div class="maininfo_left">
      <h1>
        Делаем<br>
        сотрудников<br>
        <span style="color: #92DD34;font-weight: 600;font-size: 42px">счастливыми</span>
      </h1>
      <p>Приготовим и доставим комплексное питание <br>
        для команд от 2 до 2000 человек</p>
      <div class="maininfo_download">
        <p>Пример еженедельного<br>
          рациона КБЖУ</p>
        <a href="javascript:void(0)" class="defult_btn maininfo_btn">
          Скачать PDF <img src="../assets/image/download.svg">
        </a>
      </div>
    </div>
    <div class="maininfo_right">
      <div class="maininfo_grid">
        <div class="maininfo_grid_col">
          <div class="card_title_flex">
            <p>Детские сады</p>
            <img src="../assets/image/info.svg">
          </div>
          <img class="grid_card_img" src="../assets/image/mc1.png">
        </div>
        <div class="maininfo_grid_col">
          <div class="card_title_flex">
            <p>Офисы</p>
            <img src="../assets/image/info.svg">
          </div>
          <img class="grid_card_img" src="../assets/image/mc2.png">
        </div>
        <div class="maininfo_grid_col">
          <div class="card_title_flex">
            <p>Строительные <br>
              площадки</p>
            <img src="../assets/image/info.svg">
          </div>
          <img class="grid_card_img" src="../assets/image/mc3.png">
        </div>
        <div class="maininfo_grid_col">
          <div class="card_title_flex">
            <p>Бизнес-центры</p>
            <img src="../assets/image/info.svg">
          </div>
          <img class="grid_card_img" src="../assets/image/mc4.png">
        </div>
      </div>
    </div>
  </div>

</template>

<style scoped>
.maininfo_grid{
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 30px;
}
  .grid_card_img{
    position: absolute;
    right: 0;
    bottom: 0;
  }
  .maininfo_grid_col{
    width: 439px;
    height: 304px;
   background: #F8F8F8;
    border-radius: 20px;
    padding: 20px;
    position: relative;
    cursor: pointer;
    transition: 0.2s;
  }
  .maininfo_grid_col:hover{
    box-shadow: 8px 5px 5px 0px rgba(0,0,0,0.23);
    -webkit-box-shadow: 8px 5px 5px 0px rgba(0,0,0,0.23);
    -moz-box-shadow: 8px 5px 5px 0px rgba(0,0,0,0.23);
  }
  .card_title_flex{
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .card_title_flex img{
    opacity: 0.2;
    transition: 0.2s;
    cursor: pointer;
  }
  .card_title_flex img:hover{
    opacity: 1;
  }
  .card_title_flex p{
    font-weight: 700;
    font-size: 22px;
  }
  .maininfo{
    margin-top: 244px;
    display: flex;
    justify-content: space-between;
  }
  .maininfo_left p{
    margin-top: 30px;
  }
  .maininfo_download{
    margin-top: 192px;
    position: relative;
  }
  .maininfo_download::after{
    content: url("../assets/image/bg_download.png");
    width: 295px;
    height: 362px;
    position: absolute;
    top: -60px;
    left: -100px;
  }
  .maininfo_download p{
    font-weight: 700;
    font-size: 22px;
    margin-bottom: 53px;
  }
  .maininfo_btn{
    align-items: center;
    max-width: 291px;
    gap: 10px;
  }
  .maininfo_btn img{
    margin-left: 10px;
    position: relative;
    top: 3px;
  }
</style>