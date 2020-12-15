<template>
    <div>
    <button id="hamburger" v-on:click="cache()">AFFINER MA RECHERCHE</button>
    <section id="form-result">
            <div id="block2">
                <form action="search" id="form-home2">

                    <h2 class="titre-form2">TROUVE TON VOYAGE</h2><br>
                    <div class="block-2">
                        <h4 class="sous-titre2">DE</h4>
                        <input type="from" class="input2">
                    </div>
                    <div class="block-2">
                        <h4 class="sous-titre2">A</h4>
                        <input type="to" class="input2">
                    </div>

                    <div id="choose2">
                        <div class="selection2">
                            <h4 class="duration2">DATE DEPART</h4>
                            <select name="option" class="select2">
                                <option disabled="disabled" selected="selected">Select</option>
                                <option value="">1</option>
                                <option value="">2</option>
                                <option value="">3</option>
                                <option value="">4</option>
                            </select>
                        </div>

                        <div class="selection2">
                            <h4 class="duration2">DATE FINAL</h4>
                            <select name="option" class="select2">
                                <option disabled="disabled" selected="selected">Select</option>
                                <option value="">1</option>
                                <option value="">2</option>
                                <option value="">3</option>
                                <option value="">4</option>
                            </select>
                        </div>
                    </div>

                    <div id="people2">
                        <div class="selection2">
                            <h4 class="duration2">ADULTE</h4>
                            <select name="option" class="select2">
                                <option disabled="disabled" selected="selected">Select</option>
                                <option value="">1</option>
                                <option value="">2</option>
                                <option value="">3</option>
                                <option value="">4</option>
                            </select>
                        </div>

                        <div class="selection2">
                            <h4 class="duration2">ENFANTS</h4>
                            <select name="option" class="select2">
                                <option disabled="disabled" selected="selected">Select</option>
                                <option value="">1</option>
                                <option value="">2</option>
                                <option value="">3</option>
                                <option value="">4</option>
                            </select>
                        </div>
                    </div>

                    <div class="block-2">
                        <button type="search" id="search-input2">GO</button>
                    </div>  
                </form>
                <a href="#"><button class="refresh">ACTUALISER LA RECHERCHE</button></a>
            </div>
        

        <section id="select">
            <div class="contain-select">
                <img src="img/Life/phu-quoc/hotel-phu-quoc.jpg" alt="dest1" class="img-select">
                <div class="contain-text1">
                    <p class="hotel-select1">Salinda Resort Phu Quoc Island 5*</p>
                    <ul class="ul-select1">
                        <li class="li-select1">- Un cadre unique et apaisant</li>
                        <li class="li-select1">- Une plage préservée</li>
                        <li class="li-select1">- Une sublime piscine</li>
                    </ul>
                </div>
                <button class="selectionner"><a href="#">SELECTIONNER</a></button>
            </div>
            <div class="contain-select">
                <img src="img/Life/italie/hotel-italy.jpg" alt="dest1" class="img-select">
                <div class="contain-text1">
                    <p class="hotel-select1">Tintoretto 3*</p>
                    <ul class="ul-select1">
                        <li class="li-select1">- Un hôtel dans une rue calme</li>
                        <li class="li-select1">- Un bon rapport qualité/prix</li>
                        <li class="li-select1">- Des chambres très charmantes</li>
                    </ul>
                </div>
                <button class="selectionner"><a href="#">SELECTIONNER</a></button>
            </div>
            <div class="contain-select">
                <img src="img/Life/france/hotel-chamonix.jpg" alt="dest1" class="img-select">
                <div class="contain-text1">
                    <p class="hotel-select1">Heliopic Hotel 4*</p>
                    <ul class="ul-select1">
                        <li class="li-select1">- À proximité de la montagne </li>
                        <li class="li-select1"> - Des chambres confortables</li>
                        <li class="li-select1">- Un établissement moderne</li>
                    </ul>
                </div>
                <button class="selectionner"><a href="#">SELECTIONNER</a></button>
            </div>
            <div class="contain-select">
                <img src="img/Life/hotel-canada.jpg" alt="dest1" class="img-select">
                <div class="contain-text1">
                    <p class="hotel-select1">Renaissance Hotel Montreal 4*</p>
                    <ul class="ul-select1">
                        <li class="li-select1">- Un rooftop avec piscine </li>
                        <li class="li-select1">- Des chambres élégantes</li>
                        <li class="li-select1">- Un centre de fitness</li>
                    </ul>
                </div>
                <button class="selectionner"><a href="#">SELECTIONNER</a></button>
            </div>
            <div class="contain-select">
                <img src="img/Life/hotel-espagne.jpg" alt="dest1" class="img-select">
                <div class="contain-text1">
                    <p class="hotel-select1">Portblue Club Pollentia Resort & Spa 4*</p>
                    <ul class="ul-select1">
                        <li class="li-select1">- Front de mer</li>
                        <li class="li-select1">- Une superbe piscine</li>
                        <li class="li-select1">- Une cuisine authentique</li>
                    </ul>
                </div>
                <button class="selectionner"><a href="#">SELECTIONNER</a></button>
            </div>
        </section>
    </section>
    </div>
</template>
<script>
  function cache()
  {
    if (document.getElementById('hamburger').innerHTML == 'AFFINER MA RECHERCHE')
    {
      document.getElementById('hamburger').innerHTML = 'CACHER MA RECHERCHE';
      document.getElementById('block2').style.display= 'flex';
    }
    else
    {
      document.getElementById('hamburger').innerHTML = 'AFFINER MA RECHERCHE'
      document.getElementById('block2').style.display= 'none'
    }
    if (window.innerWidth > 1024) {
      document.getElementById('block2').style.display = 'flex'
  }
  }
</script>
<style>
    /* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* RECHERCHE VOYAGE */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */

/* Burger */
#hamburger {
  border: none;
  display: block;
  background-color: #ffa755;
  font-size: 12px;
  height: 25px;
  width: 200px;
  font-family: "Roboto", sans-serif;
}

/* form */
#block2 {
  width: 100%;
  display: none;
  flex-direction: column;
  justify-content: flex-end;
  align-items: center;
}
#block2 #form-home2 {
  width: 300px;
  height: 450px;
  background-color: rgba(133, 140, 148, 0.1);
  border-radius: 7px;
  margin-top: 30px;
  border: 1px solid #c4c4c4;
  font-family: "Oswald", sans-serif;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
}
#block2 .titre-form2 {
  margin: 0px 0px -60px 0px;
  font-size: 20px;
}
#block2 .sous-titre2 {
  font-size: 15px;
}
#block2 .duration2 {
  font-size: 13px;
  margin-left: 5px;
}
#block2 .input2, #block2 #search-input2 {
  height: 30px;
  width: 260px;
  border-radius: 10px;
  border: 1px solid #c4c4c4;
}
#block2 #choose2, #block2 #people2 {
  width: 290px;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
#block2 .select2 {
  height: 30px;
  width: 130px;
  border-radius: 10px;
  border: 1px solid #c4c4c4;
  font-size: 13px;
  padding-left: 50px;
  appearance: none;
}
#block2 #search-input2 {
  background-color: #ffa755;
  font-weight: bold;
  font-size: 10px;
  height: 30px;
}

.refresh {
  background-color: rgba(133, 140, 148, 0.1);
  border-radius: 7px;
  margin-top: 30px;
  border: 1px solid #c4c4c4;
  height: 30px;
  width: 310px;
  font-family: "Oswald", sans-serif;
}

/* select */
#select{
  display: flex;
  flex-direction: column;
  align-items: center;
}
.contain-select {
  margin: 30px;
  width: 320px;
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  background-color: rgba(133, 140, 148, 0.1);
  border-top: 1px solid #4F555C;
  border-right: 1px solid #4F555C;
}

.img-select {
  width: 170px;
  height: 130px;
}

.contain-text1 {
  font-family: "Roboto", sans-serif;
  font-size: 11px;
  height: 90px;
  width: 45%;
  padding-left: 5%;
  padding-top: 1%;
}

.hotel-select1 {
  font-weight: bold;
  width: auto;
}

.li-select1 {
  list-style: none;
  padding-top: 3%;
}

.selectionner {
  width: 100%;
  height: 20px;
  border: none;
  background-color: #ffa755;
  font-size: 12px;
  font-family: "Roboto", sans-serif;
}

.selectionner a {
  text-decoration: none;
}

@media screen and (min-width: 770px) and (max-width: 990px) {
  /* Burger */
  .affiner {
    font-size: 14px;
    height: 30px;
    width: 250px;
  }

  /* form */
  #block2 {
    width: 100%;
    display: flex;
    justify-content: center;
  }

  #block2 #form-home2 {
    width: 450px;
    height: 450px;
  }

  #block2 .titre-form2 {
    margin: 0px 0px -60px 0px;
    font-size: 20px;
  }
  #block2 .sous-titre2 {
    font-size: 15px;
  }
  #block2 .duration2 {
    font-size: 13px;
    margin-left: 5px;
  }
  #block2 .input2, #block2 #search-input2 {
    height: 30px;
    width: 350px;
    border-radius: 10px;
    border: 1px solid #c4c4c4;
  }
  #block2 #choose2, #block2 #people2 {
    width: 450px;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
  }
  #block2 .select2 {
    height: 30px;
    width: 130px;
    border-radius: 10px;
    border: 1px solid #c4c4c4;
    font-size: 13px;
    padding-left: 50px;
    appearance: none;
  }
  #block2 #search-input2 {
    background-color: #ffa755;
    font-weight: bold;
    font-size: 10px;
    height: 30px;
  }
  
  .refresh {
    background-color: rgba(133, 140, 148, 0.1);
    border-radius: 7px;
    margin-top: 30px;
    border: 1px solid #c4c4c4;
    height: 30px;
    width: 450px;
    font-family: "Oswald", sans-serif;
  }

  /* select */
  #select {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .contain-select {
    margin: 30px;
    width: 550px;
    display: flex;
    align-items: center;
    flex-wrap: wrap;
  }

  .img-select {
    width: 280px;
    height: 200px;
  }

  .contain-text1 {
    height: auto;
    width: 45%;
    margin-bottom: 5%;
  }
  .contain-text1 .hotel-select1 {
    font-size: 14px;
    font-weight: bold;
    width: auto;
    margin-bottom: 10%;
  }
  .contain-text1 .li-select1 {
    font-size: 13px;
    list-style: none;
    padding-top: 3%;
  }

  .selectionner {
    width: 100%;
    height: 20px;
    font-size: 12px;
  }
}
@media screen and (min-width: 991px) {
  /* burger */
  #hamburger {
    display: none;
  }

  /* Form */
  #block2 {
    display: flex;
    justify-content: flex-start;
    width: 40%;
  }

  #block2 #form-home2 {
    width: 370px;
    height: 450px;
  }

  .titre-form2 {
    margin: 0px 60px -100px -100px;
    font-size: 20px;
  }

  .sous-titre2 {
    font-size: 15px;
  }

  .duration2 {
    font-size: 13px;
    margin-left: 5px;
  }

  .input2, #search-input2 {
    height: 30px;
    width: 350px;
  }

  #choose2, #people2 {
    width: 400px;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
  }

  .select2 {
    height: 30px;
    width: 150px;
    font-size: 13px;
    padding-left: 50px;
  }

  #search-input2 {
    font-size: 10px;
    height: 30px;
  }

  .refresh {
    height: 30px;
    width: 370px;
  }

  /* select */
  #form-result {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: space-around;
  }

  #select {
    width: 60%;
    margin-right: 5%;
  }

  .contain-select {
    width: 550px;
    margin-top: 30px;
    display: flex;
    flex-wrap: wrap;
  }

  .img-select {
    width: 275px;
    height: auto;
  }

  .contain-text1 {
    height: auto;
    width: 45%;
    margin-bottom: 3%;
  }
  .contain-text1 .hotel-select1 {
    font-size: 20px;
    font-weight: bold;
    width: auto;
    margin-bottom: 10%;
  }
  .contain-text1 .li-select1 {
    font-size: 16px;
    list-style: none;
    padding-top: 3%;
  }

  .selectionner {
    width: 100%;
    height: 35px;
    font-size: 13px;
  }

  .selectionner a {
    text-decoration: none;
  }
}
</style>