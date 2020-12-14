<template>
    <footer>
        <div id="cont-img2">
            <img src="img/Life/twitter-logo.png" alt="twitter" class="img-f">
            <img src="img/Life/snapcatch-logo.png" alt="snap" class="img-f">
            <img src="img/Life/instagram-logo.png" alt="insta" class="img-f">
            <img src="img/Life/facebook.png" alt="fb" class="img-f">
        </div>
        <div id="cont-text">
            <p class="p-f1">SUPPORT</p>
            <p class="p-f2">NUMERO</p>
            <p class="p-f3">MAIL</p>
        </div>
    </footer>
</template>
<script>
export default {
}
</script>
<style>
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* FOOTER */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
footer {
  margin-top: 50px;
  height: 75px;
  width: 100%;
  background-color: #c4c4c4;
  padding-top: 15px;
  display: flex;
  flex-direction: column;
  padding-bottom: 5px;
}
.img-f {
  margin-left: 10px;
  width: 20px;
  height: 20px;
}
#cont-text {
  margin-top: 10px;
}
#cont-text, #cont-img2 {
  display: flex;
  flex-direction: row;
  justify-content: center;
}
.p-f1, .p-f2, .p-f3 {
  padding-left: 10px;
  font-size: 10px;
  font-family: "Roboto", sans-serif;
  font-weight: bold;
}
@media screen and (min-width: 770px) and (max-width: 990px)  {
  footer {
    margin-top: 60px;
    height: 80px;
    width: 100%;
  }
  .img-f {
    margin-left: 10px;
    width: 25px;
    height: 25px;
  }
  #cont-text {
    margin-top: 10px;
  }
  .p-f1, .p-f2, .p-f3 {
    font-size: 12px;
  }
}
@media screen and (min-width: 991px) {
  footer {
    margin-top: 60px;
    height: 120px;
    width: 100%;
    padding-top: 15px;
    padding-bottom: 5px;
  }
  .img-f {
    margin: 10px;
    width: 30px;
    height: 30px;
  }
  #cont-text, #cont-img2 {
    display: flex;
    flex-direction: row;
    justify-content: center;
  }
  .p-f1, .p-f2, .p-f3 {
    padding-left: 10px;
    font-size: 15px;
    font-family: "Roboto", sans-serif;
    font-weight: bold;
  }
}
</style>
