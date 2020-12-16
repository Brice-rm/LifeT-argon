<template>
<section id="picto">
        <div id="contain-img">
          <img src="img/Life/picto-avion.png" alt="picto-avion" class="picto-img">

          <img src="img/Life/placeholder.png" alt="picto-map" class="picto-img">

          <img src="img/Life/shopping-bag.png" alt="picto-shop" class="picto-img">
        </div>
        <div class="contain-descr">
          <p class="descr-picto">Transport inclu.</p>
          <p class="descr-picto">Destination aux Choix.</p>
          <p class="descr-picto">Achat Online.</p>
        </div>
      </section>
</template>
<script>
  export default {};
</script>
<style>
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* PICTO */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
#picto {
  background-image: url("https://zupimages.net/up/20/50/lhyj.jpg");
  background-repeat: no-repeat;
  margin-top: 50px;
  height: 130px;
  width: auto;
  background-size: 100%;
  box-shadow: 0px 3px 4px #c4c4c4;
}
#contain-img,
.contain-descr {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
.picto-img {
  margin: 25px 0px 10px 0px;
  width: 40px;
  height: 50px;
  padding-bottom: 10px;
  border-bottom: 1px solid #4f555c;
}
.descr-picto {
  font-size: 10px;
  font-family: "Roboto", sans-serif;
  font-weight: bold;
  text-align: center;
}
/* Video */
.video {
  margin-top: 30px;
  width: auto;
  display: flex;
  justify-content: center;
}
@media screen and (min-width: 770px) and (max-width: 990px) {
 /* PICTO */
  #picto {
   
    margin-top: 50px;
    height: 180px;
    width: auto;
    background-size: 100%;
  }
  .picto-img {
    margin: 50px 0px 10px 0px;
    width: 55px;
    height: 65px;
    padding-bottom: 10px;
  }
  .descr-picto {
    font-size: 12px;
  }
}
@media screen and (min-width: 991px) {
  
  /* PICTO */
  #picto {
    height: 400px;
    background-size: 100%;
  }
  .picto-img {
    margin: 150px 0px 10px 0px;
    width: 100px;
    height: 110px;
    border-bottom: 1px solid #4f555c;
  }
  .descr-picto {
    text-align: center;
    font-size: 20px;
    width: 200px;
  }
  /* Video */
  .video {
    margin-bottom: 70px;
  }
}
</style>
