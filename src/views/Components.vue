<template>
<main>
    <section id="main-img">

        <div id="block">
            <form action="search" id="form-home">

                <h2 class="titre-form">TROUVE TON VOYAGE</h2><br>

                <h4 class="sous-titre">DE</h4>
                <div class="block-1">
                    <input type="from" class="input">
                </div>

                <h4 class="sous-titre">A</h4>
                <div class="block-1">
                    <input type="to" class="input">
                </div>

                <div id="choose">
                    <div class="selection">
                        <h4 class="duration">DATE DEPART</h4>
                        <select name="option" class="select1">
                            <option disabled="disabled" selected="selected">Select</option>
                            <option value="">1</option>
                            <option value="">2</option>
                            <option value="">3</option>
                            <option value="">4</option>
                        </select>
                    </div>

                    <div class="selection">
                        <h4 class="duration">DATE FINAL</h4>
                        <select name="option" class="select1">
                            <option disabled="disabled" selected="selected">Select</option>
                            <option value="">1</option>
                            <option value="">2</option>
                            <option value="">3</option>
                            <option value="">4</option>
                        </select>
                    </div>
                </div>

                <div id="people">
                    <div class="selection">
                        <h4 class="duration">ADULTE</h4>
                        <select name="option" class="select1">
                            <option disabled="disabled" selected="selected">Select</option>
                            <option value="">1</option>
                            <option value="">2</option>
                            <option value="">3</option>
                            <option value="">4</option>
                        </select>
                    </div>

                    <div class="selection">
                        <h4 class="duration">ENFANTS</h4>
                        <select name="option" class="select1">
                            <option disabled="disabled" selected="selected">Select</option>
                            <option value="">1</option>
                            <option value="">2</option>
                            <option value="">3</option>
                            <option value="">4</option>
                        </select>
                    </div>
                </div>

                <div class="block-1">
                    <a href="rechercheV.html"><button type="search" id="search-input">GO</button></a>
                </div>
            </form>
        </div>




    </section>

    <section id="destination">

        <div id="container-titre1">
            <p id="titre1">NOTRE SELECTION</p>
        </div>
        
    </section>
</main>    
</template>
<script>
import Hero from "./components/Hero";
import BasicElements from "./components/BasicElements";
import Inputs from "./components/Inputs";
import CustomControls from "./components/CustomControls";
import Navigation from "./components/Navigation";
import JavascriptComponents from "./components/JavascriptComponents";
import Carousel from "./components/Carousel";
import Icons from "./components/Icons";
import Examples from "./components/Examples";
import DownloadSection from "./components/DownloadSection";

export default {
  name: "components",
  components: {
    Hero,
    BasicElements,
    Inputs,
    CustomControls,
    Navigation,
    JavascriptComponents,
    Carousel,
    Icons,
    Examples,
    DownloadSection
  }
};
</script>
<style>
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/*  FORM index */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */


#form-home {
  width: 300px;
  height: 250px;
  padding: 8px;
  background-color: rgba(255, 255, 255, 0.7);
  border-radius: 7px;
  margin: 0px 0px 0px 0px;
  border: 1px solid #c4c4c4;
  font-family: "Oswald", sans-serif;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
}

.titre-form {
  margin: 3px 60px -20px -90px;
  font-size: 12px;
}

.sous-titre {
  font-size: 10px;
  margin: 4px 0px 2px -230px;
}

.duration {
  font-size: 10px;
  margin: 5px;
}

.input, #search-input {
  height: 20px;
  width: 250px;
  border-radius: 10px;
  border: none;
}

#choose, #people {
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}

.select1 {
  height: 20px;
  width: 110px;
  border-radius: 10px;
  border: none;
  font-size: 10px;
  padding-left: 50px;
  appearance: none;
}

#search-input {
  background-color: #ffa755;
  font-weight: bold;
  margin: 10px;
  font-size: 8px;
}

@media screen and (min-width: 770px) and (max-width: 990px) {
  #main-img {
    height: 400px;
    width: auto;
  }

  #block {
    height: 400px;
  }
  #block #form-home {
    width: 400px;
    height: 300px;
    padding: 8px;
  }
  #block .titre-form {
    margin: 0px 80px -25px -60px;
    font-size: 20px;
  }

  .sous-titre {
    font-size: 13px;
    margin: 0px 0px 0px -270px;
  }
  .duration {
    font-size: 13px;
    margin: 5px;
  }

  .input, #search-input {
    height: 20px;
    width: 300px;
    font-size: 12px;
  }
}
@media screen and (min-width: 991px) {
  #main-img {
    height: 800px;
    width: auto;
    background-size: cover;
    background-repeat: no-repeat;
  }

  /* Form */
  #block {
    height: 900px;
    margin-right: 150px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
  }

  #form-home {
    width: 550px;
    height: 600px;
    background-color: rgba(255, 255, 255, 0.7);
    border-radius: 7px;
    margin: 0px 40px 180px 50px;
  }

  .titre-form {
    margin: 10px 0px 0px -250px;
    font-size: 26px;
  }

  .sous-titre, .duration {
    font-size: 15px;
  }

  .sous-titre {
    margin: -30px;
    margin-left: -450px;
    margin-bottom: -45px;
  }

  .input, #search-input {
    border-radius: 20px;
    border: none;
    height: 35px;
    width: 450px;
  }

  .input, #search-input, .select1:focus {
    outline: none;
  }

  #choose, #people {
    width: 450px;
    justify-content: space-between;
  }

  .select1 {
    border-radius: 20px;
    border: none;
    height: 35px;
    width: 200px;
    font-size: 15px;
    padding-left: 80px;
  }

  #search-input {
    font-size: 13px;
  }
}
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* Body index*/
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */


#main-img {
  background-image: url(https://zupimages.net/up/20/49/yed6.jpg);
  height: 300px;
  background-size: cover;
  background-repeat: no-repeat;
  margin: 10px 0px 0px 0px;
}

#block {
  height: 300px;
  display: flex;
  justify-content: center;
  align-items: center;
}

#titre1 {
  margin-top: 50px;
  font-size: 20px;
  font-family: "Roboto", sans-serif;
  font-weight: 300;
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 200px;
  border-bottom: 1px solid #FFA755;
  padding: 10px;
}

#container-titre1, #contain-dest {
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

#dest1 a, #dest2 a, #dest3 a {
  text-decoration: none;
}

#dest1, #dest2 {
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
  color: #FFA755;
}

.euro {
  font-weight: bold;
  color: #FFA755;
}

/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* PICTO */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
#picto {
  background-image: url();
  background-repeat: no-repeat;
  margin-top: 50px;
  height: 130px;
  width: auto;
  background-size: 100%;
  box-shadow: 0px 3px 4px #c4c4c4;
}

#contain-img, .contain-descr {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}

.picto-img {
  margin: 25px 0px 10px 0px;
  width: 40px;
  padding-bottom: 10px;
  border-bottom: 1px solid #4F555C;
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

/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* MEDIAS QUERIES */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
@media screen and (min-width: 770px) and (max-width: 990px) {
  /* DESTINATION */
  #titre1 {
    width: 270px;
    font-size: 25px;
    margin: 100px 0px;
  }

  #dest1, #dest2, #dest3, .dest-img {
    width: 400px;
    height: 250px;
  }

  #dest1, #dest2, #dest3 {
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


  /* PICTO */
  #picto {
    background-image: url();
    margin-top: 50px;
    height: 180px;
    width: auto;
    background-size: 100%;
  }

  .picto-img {
    margin: 50px 0px 10px 0px;
    width: 55px;
    padding-bottom: 10px;
  }

  .descr-picto {
    font-size: 12px;
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

  #dest1, #dest2, #dest3, .dest-img {
    width: 320px;
    height: 250px;
  }

  #dest1, #dest2, #dest3 {
    margin-bottom: 400px;
  }

  .infos-produit {
    padding: 15px;
  }

  .pays {
    font-size: 20px;
    margin-bottom: 5px;
  }

  .ville{
    font-size: 15px;
  }

  /* PICTO */
  #picto {
    height: 400px;
    background-size: 100%;
  }

  .picto-img {
    margin: 150px 0px 10px 0px;
    width: 100px;
    border-bottom: 1px solid #4F555C;
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
