<template>
  <section id="destination">
    <div id="container-titre1">
      <p id="titre1">NOTRE SELECTION</p>
    </div>
    <div id="contain-dest">
      <div id="dest1">
        <b-carousel id="carousel1"
            controls
            indicators>
            <!-- Text slides with image -->
            <b-carousel-slide img-src="img/Life/phu-quoc/phu-quoc.jpg"></b-carousel-slide>
            <b-carousel-slide img-src="img/Life/phu-quoc/phu-quoc-paysage.jpg"></b-carousel-slide>
            <b-carousel-slide img-src="img/Life/phu-quoc/hotel-phu-quoc.jpg"></b-carousel-slide>
        </b-carousel>
          <div class="infos-produit">
            <p class="pays">Thailande</p>
            <p class="ville">Phú Quốc<span class="t-">-</span>All inclusive</p>
            <p class="prix">dès<span class="euro">100€</span>ttc</p>
          </div>
        </div>

        <div id="dest2">                    
          <b-carousel id="carousel1"
                      controls
                      indicators>
              <!-- Text slides with image -->
              <b-carousel-slide img-src="img/Life/italie/venise.jpg"></b-carousel-slide>
              <b-carousel-slide img-src="img/Life/italie/paysage-venise.jpg"></b-carousel-slide>
              <b-carousel-slide img-src="img/Life/italie/hotel-italy.jpg"></b-carousel-slide>
          </b-carousel>
          <div class="infos-produit">
            <p class="pays">Italie</p>
            <p class="ville">Venise<span class="t-">-</span>All inclusive</p>
            <p class="prix">dès<span class="euro">100€</span>ttc</p>
          </div>
        </div>

        <div id="dest3">
          <b-carousel id="carousel1"
                      controls
                      indicators>
              <!-- Text slides with image -->
              <b-carousel-slide img-src="img/Life/france/chamonix.jpg"></b-carousel-slide>
              <b-carousel-slide img-src="img/Life/france/mont-blanc.jpg"></b-carousel-slide>
              <b-carousel-slide img-src="img/Life/france/hotel-chamonix.jpg"></b-carousel-slide>
          </b-carousel>
          <div class="infos-produit">
            <p class="pays">France</p>
            <p class="ville">Chamonix<span class="t-">-</span>All inclusive</p>
            <p class="prix">dès<span class="euro">100€</span>ttc</p>
          </div>
        </div>
      </div>
  </section>
</template>  
<script>
import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";

export default {
  components: {
    BCarousel,
    BCarouselSlide,
  },
};
</script>
<style>
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* Body index*/
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
#titre1 {
  margin-top: 50px;
  font-size: 20px;
  font-family: "Roboto", sans-serif;
  font-weight: 300;
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 200px;
  border-bottom: 1px solid #ffa755;
  padding: 10px;
}
#container-titre1,
#contain-dest {
  display: flex;
  flex-direction: column;
  align-items: center;
}


.dest-img {
  width: 200px;
}
#contain-dest {
  font-size: 5px;
  margin-top: 20px;
}
#dest1 a,
#dest2 a,
#dest3 a {
  text-decoration: none;
}
#dest1,
#dest2,
#dest3 {
  margin-bottom: 25px;
  width: 300px;
}
.infos-produit {
  border: #c4c4c4 1px solid;
  margin-top: -7px;
  border-top: none;
  padding: 15px;
  font-family: "Roboto", sans-serif;
  font-size: 15px;
}
.pays {
  font-weight: bold;
  padding-bottom: 2px;
}
.t- {
  padding: 5px;
}
.prix {
  display: flex;
  justify-content: flex-end;
  text-align: center;
  font-weight: 500;
  margin: 0px 2px 2px 0px;
  color: #ffa755;
}
.euro {
  font-weight: bold;
  color: #ffa755;
}
@media screen and (min-width: 770px) and (max-width: 990px) {
  /* DESTINATION */
  #titre1 {
    width: 270px;
    font-size: 25px;
    margin: 100px 0px;
  }
  #dest1,
  #dest2,
  #dest3,
  .dest-img {
    width: 400px;
    height: 250px;
  }
  #dest1,
  #dest2,
  #dest3 {
    margin-bottom: 150px;
  }
  .infos-produit {
    padding: 15px;
  }
  .pays {
    font-size: 20px;
    margin-bottom: 5px;
  }
  .ville {
    font-size: 15px;
  }
}
@media screen and (min-width: 991px) {
  /* DESTINATION */
  #titre1 {
    width: 300px;
    font-size: 30px;
  }
  #contain-dest {
    margin-top: 100px;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
  }
  #dest1,
  #dest2,
  #dest3,
  .dest-img {
    width: 320px;
    height: 250px;
  }
  #dest1,
  #dest2,
  #dest3 {
    margin-bottom: 400px;
  }
  .infos-produit {
    padding: 15px;
  }
  .pays {
    font-size: 20px;
    margin-bottom: 5px;
  }
  .ville {
    font-size: 15px;
  }
}
</style>