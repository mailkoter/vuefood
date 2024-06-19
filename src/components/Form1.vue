<script>
export default {
  name: 'Form1',
}
</script>

<template>
  <div class="form_section_1">
    <div class="container">
      <div class="from_s1_left">
        <h2 class="form_title">
          Идеальные обеды<br>
          <span style="color: #72b126;font-size: 42px;font-weight: 600">на рабочем месте</span></h2>
        <p class="pre_title_form">Скачать пример меню на неделю:</p>
        <form>
          <div><input name="first_name" type="text" placeholder="Ваше имя"></div>
          <div class="tel">
            <input type="tel" placeholder="(999)999-99-99">
          </div>
          <a href="javascript:void(0)" class="defult_btn maininfo_btn">
            Скачать PDF <img src="../assets/image/download.svg">
          </a>
        </form>
        <p class="form_notif">
          Нажимая кнопку “Скачать PDF” вы соглашаетесь на обработку <br>
          персональных данных в соответствии с политикой конфиденциальности</p>
      </div>
      <div class="form_s1_right">
        <img src="../assets/image/pc_txt.png">
        <img src="../assets/image/pc.png">
      </div>
    </div>
  </div>
</template>

<style scoped>
.form_s1_right{
  position: relative;
}
.form_s1_right img:nth-child(1){
  position: relative;
  left: -80px;
  top: -40px;
}
.form_s1_right img:nth-child(2){
  position: absolute;
  right: -189px;
  bottom: -167px;
}
.form_section_1 > div{
  display: flex;
}
form a{
  padding: 17px 48px;
}
.form_notif{
  color: #7E7E7F;
  line-height: 19.36px;
  margin-top: 40px;
}
.form_title::before{
  content: url("../assets/image/fs1_title_icon.svg");
  position: absolute;
  width: 182px;
  height: 45px;
  top: 138px;
  z-index: 1;
}
.pre_title_form{
  position: relative;
  font-size: 22px;
  font-weight: 700;
  color: #000;
  margin-top: 120px;
  margin-bottom: 40px;
}
  .form_section_1{
    margin-top: 134px;
    background-image: url("../assets/image/bg_form1.png");
    background-repeat: no-repeat;
    width: 100%;
    height: 836px;
    max-width: 1916px;
    margin: 0 auto;
    margin-top: 161px;
    padding-top: 13px;
  }
  .from_s1_left{
    position: relative;
    z-index: 999;
  }
  .from_s1_left::before{
    content: url('../assets/image/vector_on.svg');
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: -1;
  }
  .form_title{
    font-size: 42px;
    font-weight: 600;
    line-height: 52.08px;
    padding-top: 190px;
  }
</style>