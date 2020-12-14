<template>
     <section id="contact">
        <div id="contain-titre-cont">
            <p class="titre-cont">CONTACTS</p>
        </div>
        <section id="contain-ctc">
            <form class="form-ctc">
                <div class="form-headcont">
                    <h4 class="cont-msg">ENVOYEZ NOUS UN MESSAGE</h4>
                </div>
                <div class="form-bodcont ">

                    <div class="form-group col-12">
                        <label for="exampleFormControlInput1">Email address</label>
                        <input type="email" class="form-control" id="exampleFormControlInput1"
                            placeholder="nom@exemple.fr">
                    </div>


                    <div class="form-row col-12 pr-2 pl-2 pb-3">
                        <div class="col">
                            <input type="text" class="form-control" placeholder="Nom" required>
                        </div>
                        <div class="col">
                            <input type="text" class="form-control" placeholder="Prénom" required>
                        </div>
                    </div>


                    <div class="form-group col-12">
                        <label for="exampleFormControlTextarea1">Message</label>
                        <textarea class="form-control" id="exampleFormControlTextarea1" rows="12"></textarea>
                    </div>
                    <div class="send-btn">
                        <button type="submit" class="btn btn-primary btn-sm color">Submit</button>
                    </div>
                </div>
            </form>
        </section>

    </section>
</template>
<script>
export default {
    
}
</script>
<style>
    #contact {
  width: auto;
  font-family: "Roboto", sans-serif;
}
#contact .titre-cont {
  display: none;
}
#contact #contain-ctc {
  margin-bottom: 20px;
}
#contact .form-headcont {
  width: 100%;
  height: 70px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background-color: #b5e0cf;
}
#contact .form-bodcont {
  width: auto;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 5%;
  background-color: white;
}
#contact .form-bodcont .infos-cont {
  width: 80%;
  height: 25px;
  opacity: 0.5;
}
#contact .form-bodcont .title-cont {
  width: 80%;
  margin-top: 10px;
  font-size: 13px;
}
#contact .form-bodcont .cont-msg {
  width: 80%;
  height: 150px;
  opacity: 0.5;
}
#contact .form-bodcont .send-btn {
  width: 100%;
  display: flex;
  justify-content: flex-end;
}
#contact .form-bodcont .send-btn .color {
  border: none;
  background-color: #FFA755;
}
@media screen and (min-width: 770px) and (max-width: 990px) {
  #contact #contain-ctc {
    margin-bottom: 20px;
  }
  #contact .form-headcont {
    width: 100%;
    height: 70px;
  }
  #contact .form-bodcont {
    width: auto;
    padding: 5%;
  }
  #contact .form-bodcont .infos-cont {
    width: 90%;
    height: 25px;
    opacity: 0.5;
  }
  #contact .form-bodcont .title-cont {
    width: 90%;
    margin-top: 10px;
    font-size: 13px;
  }
  #contact .form-bodcont .cont-msg {
    width: 90%;
    height: 250px;
    opacity: 0.5;
  }
}
@media screen and (min-width: 991px) {
    #contact {
    display: flex;
    flex-direction: row;
    align-items: center;
    background-image: url("https://zupimages.net/up/20/51/hhb2.png");
    background-size: cover;
    width: 100%;
    height: 100%;
  }
  #contact #contain-titre-cont {
    width: 50%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  #contact #contain-titre-cont .titre-cont {
    display: flex;
    color: white;
    font-size: 60px;
    font-family: "Oswald", sans-serif;
  }
  #contact #contain-ctc {
    margin-bottom: 20px;
    width: 50%;
    height: auto;
  }
  #contact .form-headcont {
    width: 100%;
    margin-top: 50px;
    height: 60px;
    font-size: 20px;
  }
  #contact .form-bodcont {
    padding: 5%;
    background-color: #b5e0cf;
  }
  #contact .form-bodcont .infos-cont {
    width: 90%;
    height: 30px;
    opacity: 0.5;
  }
  #contact .form-bodcont .title-cont {
    width: 90%;
    margin-top: 10px;
    font-size: 15px;
  }
  #contact .form-bodcont .cont-msg {
    width: 90%;
    height: 300px;
    opacity: 0.5;
  }
}
</style>