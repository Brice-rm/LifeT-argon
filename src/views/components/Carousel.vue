<template>
      <section id="destination">
        <div id="container-titre1">
          <p id="titre1">NOTRE SELECTION</p>
        </div>
        <div id="contain-dest">
          <div id="dest1">
            <div>
  <b-carousel
    id="carousel-fade"
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
    img-width="1024"
    img-height="480"
  >
    <b-carousel-slide
      caption="First slide"
      img-src="https://zupimages.net/up/20/50/571l.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Second Slide"
      img-src="https://zupimages.net/up/20/50/571l.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Third Slide"
      img-src="https://zupimages.net/up/20/50/571l.jpg"
    ></b-carousel-slide>
  </b-carousel>
</div>
            <div class="infos-produit">
              <p class="pays">Thailande</p>
              <p class="ville">
                Phú Quốc<span class="t-">-</span>All inclusive
              </p>
              <p class="prix">dès<span class="euro">100€</span>ttc</p>
            </div>
          </div>

          <div id="dest2">
            <img
              src="images/Life/venice-italy.jpg"
              alt="urbain"
              class="dest-img"
            />
            <div class="infos-produit">
              <p class="pays">Italie</p>
              <p class="ville">Venise<span class="t-">-</span>All inclusive</p>
              <p class="prix">dès<span class="euro">100€</span>ttc</p>
            </div>
          </div>

          <div id="dest3">
            <img
              src="images/Life/mont-blanc.jpg"
              alt="montagne"
              class="dest-img"
            />
            <div class="infos-produit">
              <p class="pays">France</p>
              <p class="ville">
                Chamonix<span class="t-">-</span>All inclusive
              </p>
              <p class="prix">dès<span class="euro">100€</span>ttc</p>
            </div>
          </div>
        </div>
      </section>

    
</template>  
<script>

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
  width: 100%;
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
#dest2 {
  margin-bottom: 25px;
}

.infos-produit {
  border: #c4c4c4 1px solid;
  margin-top: -7px;
  border-top: none;
  padding: 10px 0px 0px 5px;
  font-family: "Roboto", sans-serif;
  font-size: 10px;
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
