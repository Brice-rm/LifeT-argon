<template>
 <section id="all-contain">
        <section id="contain-resum">
            <div class="contain-select1">
                <img src="img/Life/phu-quoc/hotel-phu-quoc.jpg" alt="dest1" class="img-select">
                <div class="contain-text">
                    <p class="hotel-select">Salinda Resort Phu Quoc Island 5*</p>
                    <ul class="ul-select">
                        <li class="li-select">- Un cadre unique et apaisant</li>
                        <li class="li-select">- Une plage préservée</li>
                        <li class="li-select">- Une sublime piscine</li>
                    </ul>
                </div>
            </div>
            <div class="contain-vol">
                <div class="contain-aller">
                    <p>ALLER</p>
                    <p>SAMEDI 1 MAI</p>
                </div>
                <div class="contain-infos-air">
                    <img src="img/Life/Logo-airfrance.png" alt="air-france" class="air-france">
                    <p class="text-company">AIR FRANCE</p>
                    <p class="text-infos">21H20<br>CDG<br><small>Paris</small></p>
                    <p class="arrow">→</p>
                    <p class="text-infos">10H30 <small>(J+1)</small><br>HKT<br><small>Phuket</small></p>
                </div>
                <p class="billet">BILLET INCLUS</p>
            </div>
            <div class="contain-vol">
                <div class="contain-aller">
                    <p>RETOUR</p>
                    <p>MARDI 4 MAI</p>
                </div>
                <div class="contain-infos-air">
                    <img src="img/Life/Logo-airfrance.png" alt="air-france" class="air-france">
                    <p class="text-company">AIR FRANCE</p>
                    <p class="text-infos">10H30<br>HKT<br><small>Phuket</small></p>
                    <p class="arrow">→</p>
                    <p class="text-infos">21H20<small>(J+1)</small><br>CDG<br><small>Paris</small></p>
                </div>
                <p class="billet">BILLET INCLUS</p>
            </div>
        </section>

        <section id="all-form">
            <section id="login">
                <form class="form-log">
                    <div class="form-headlog">
                        <h4 class="title">CONNECTION</h4>
                    </div>
                    <div class="form-bodlog">
                        <!-- mail -->
                        <p class="title-log">Adresse Mail</p>
                        <div class="col">
                            <input type="text" class="form-control" placeholder="" required>
                        </div>
                        <!-- mdp -->
                        <p class="title-log">Mot de passe</p>
                        <div class="col">
                            <input type="text" class="form-control" placeholder="" required>
                        </div>
                        <p class="subscribe">TOUJOURS PAS INSCRIT ? <a href="#">inscrit toi.</a></p>
                        <button type="submit" class="btn btn-primary btn-sm " id="color1">Connection</button>
                    </div>
                </form>
            </section>
            <section id="paiement">
                <form class="credit-card">
                    <div class="form-header">
                        <h4 class="title">PAIEMENT</h4>
                    </div>

                    <div class="form-body">

                        <!-- Titulaire -->
                        <p class="title-pay">Titulaire de carte</p>
                        <div class="col mb-2">
                            <input type="text" class="form-control" placeholder="" required>
                        </div>
                        <!-- Card Number -->
                        <p class="title-pay">Numéro de carte</p>
                        <div class="col mb-2">
                            <input type="tel" class="form-control" placeholder="" required>
                        </div>

                        <!-- Date Field -->
                        <div class="date-field">
                            <div class="month">
                                <select name="Month">
                                    <option value="january">Janvier</option>
                                    <option value="february">Fevrier</option>
                                    <option value="march">Mars</option>
                                    <option value="april">Avril</option>
                                    <option value="may">Mai</option>
                                    <option value="june">Juin</option>
                                    <option value="july">Juillet</option>
                                    <option value="august">Aout</option>
                                    <option value="september">Septembre</option>
                                    <option value="october">Octobre</option>
                                    <option value="november">Novembre</option>
                                    <option value="december">Decembre</option>
                                </select>
                            </div>
                            <div class="year">
                                <select name="Year">
                                    <option value="2016">2016</option>
                                    <option value="2017">2017</option>
                                    <option value="2018">2018</option>
                                    <option value="2019">2019</option>
                                    <option value="2020">2020</option>
                                    <option value="2021">2021</option>
                                    <option value="2022">2022</option>
                                    <option value="2023">2023</option>
                                    <option value="2024">2024</option>
                                </select>
                            </div>
                        </div>

                        <!-- Card Verification Field -->
                        <div class="card-verification">
                            <div class="cvv-input">
                                <input class="cvv" type="text" placeholder="CVV">
                            </div>
                            <div class="cvv-details">
                                <p>3 chiffres situés au dos de la carte</p>
                            </div>
                        </div>

                        <!-- Buttons -->
                        <button type="submit" class="proceed-btn"><a href="#">Payer</a></button>
                        <button type="submit" class="paypal-btn"><a href="#">Pay With</a></button>
                    </div>
                </form>
            </section>
        </section>
    </section>
</template>
<script>
export default {
    
}
</script>
<style>
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/*  PANIER BODY*/
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */

#all-contain {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  font-family: "Roboto", sans-serif;
}
#all-contain .contain-vol {
  width: 300px;
  height: 120px;
  display: flex;
  flex-wrap: wrap;
  background-color: rgba(133, 140, 148, 0.1);
  border: 1px solid #4F555C;
  margin-bottom: 50px;
}

#all-contain .contain-select1{
width: 300px;
height: 120px;
display: flex;
background-color: rgba(133, 140, 148, 0.1);
border: 1px solid #4F555C;
margin-bottom: 50px;
}
.hotel-select{
  font-size: 12px;
  font-weight: bold;
  padding-left: 5px;
}

.contain-select1 .li-select{
  font-size: 10px;
}
.ul-select{
  padding: 5px;
}

.contain-select1 img{
  height: 100%;
  width: 55%;
}

.contain-aller {
  width: 100%;
  height: 20px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  font-size: 10px;
}
.contain-aller p {
  padding: 5px;
  font-weight: bold;
}

.contain-infos-air {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  background-color: white;
  width: 100%;
  height: 80px;
}
.contain-infos-air img {
  width: auto;
  height: 60px;
  margin: 2%;
}
.contain-infos-air .text-company {
  font-size: 8px;
  width: 70px;
  font-weight: bold;
  margin-right: 20px;
}
.contain-infos-air .arrow {
  font-size: 20px;
}
.contain-infos-air p {
  font-size: 10px;
  padding-top: 15px;
}

.billet {
  width: 100%;
  font-size: 10px;
  font-weight: bold;
  margin-bottom: 2px;
  color: #FFA755;
  display: flex;
  justify-content: flex-end;
}


@media screen and (min-width: 770px) and (max-width: 990px)  {
  #all-contain {
    width: 100%;
  }
  #all-form{
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
  }
  #all-contain .contain-vol {
    width: 455px;
    height: 160px;
    margin-bottom: 30px;
  }

  #all-contain .contain-select1{
    width: 455px;
    height: 160px;
    display: flex;
    background-color: rgba(133, 140, 148, 0.1);
    border: 1px solid #4F555C;
    margin-bottom: 50px;
    }
    .hotel-select{
      font-size: 15px;
      font-weight: bold;
    }
    .contain-select1 .li-select{
      font-size: 12px;
    }

  .contain-aller {
    width: 100%;
    height: 35px;
    font-size: 13px;
  }
  .contain-aller p {
    padding: 10px;
  }

  .contain-infos-air {
    width: 100%;
    height: 100px;
  }
  .contain-infos-air img {
    height: 80px;
    margin: 2%;
  }
  .contain-infos-air .text-company {
    font-size: 13px;
    width: 100px;
  }
  .contain-infos-air .arrow {
    font-size: 25px;
    margin-right: 25px;
  }
  .contain-infos-air .text-infos {
    font-size: 13px;
    width: 70px;
  }

  .billet {
    width: 100%;
    font-size: 13px;
    padding: 5px;
  }
}
@media screen and (min-width: 991px) {
  #all-contain {
    display: flex;
    flex-direction: row;
    width: 100%;
    height: 100%;
  }
  #all-contain #contain-resum {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    width: 70%;
    height: 810px;
    margin: 35px;
  }
  #all-contain #all-form {
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    width: 30%;
    height: 810px;
    margin: 35px;
  }
  #all-contain .contain-select1 {
    width: 600px;
    height: 250px;
    margin-bottom: 30px;
  }

  .hotel-select{
    font-size: 20px;
    font-weight: bold;
  }
  .contain-select1 .li-select{
    font-size: 15px;
  }

  #all-contain .contain-aller, #all-contain .billet {
    font-size: 13px;
  }
  #all-contain .contain-vol {
    width: 600px;
    height: 200px;
    margin-bottom: 30px;
  }
  #all-contain .contain-vol .contain-infos-air {
    height: 130px;
  }
  #all-contain .contain-vol .contain-infos-air img {
    height: 100px;
    margin: 2%;
  }
  #all-contain .contain-vol .contain-infos-air .text-company {
    font-size: 13px;
    width: 100px;
  }
  #all-contain .contain-vol .contain-infos-air .arrow {
    font-size: 40px;
    margin-right: 45px;
  }
  #all-contain .contain-vol .contain-infos-air .text-infos {
    font-size: 15px;
    width: 100px;
  }
  .billet {
    width: 100%;
    font-size: 13px;
    padding-right: 5px;
  }
}







/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* form connection (panier) */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */

#login {
  margin-bottom: 20px;
}

.form-headlog {
  width: 260px;
  height: 70px;
  border-radius: 5px 5px 0px 0px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #c4c4c4;
}

.form-bodlog {
  width: auto;
  height: 250px;
  border: 1px solid #4F555C;
  border-top: none;
  border-radius: 0px 0px 5px 5px;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 2%;
  background-color: white;
}
.form-bodlog .infos-log {
  width: 200px;
  height: 25px;
  opacity: 0.5;
}
.form-bodlog .title-log {
  width: 200px;
  margin-top: 10px;
  margin-bottom: 0px;
  font-size: 13px;
}
.form-bodlog .subscribe {
  margin-top: 10px;
  width: 200px;
  font-size: 50%;
}
.form-bodlog .subscribe a {
  color: blue;
}
#color1{
  border: none;
  background-color: #FFA755;
  
}
@media screen and (min-width: 770px) and (max-width: 990px)  {
  .form-headlog {
    width: 355px;
    height: 70px;
  }

  .form-bodlog {
    width: auto;
  }
  .form-bodlog .infos-log {
    width: 250px;
    height: 25px;
    opacity: 0.5;
  }
  .form-bodlog .title-log {
    width: 280px;
    margin-top: 10px;
    font-size: 15px;
  }
  .form-bodlog .subscribe {
    margin-top: 10px;
    width: 250px;
    font-size: 60%;
  }
  .form-bodlog .subscribe a {
    color: blue;
  }
}
@media screen and (min-width: 991px) {
  .form-headlog {
    width: 355px;
    height: 70px;
  }

  .form-bodlog {
    width: auto;
  }
  .form-bodlog .infos-log {
    width: 250px;
    height: 25px;
    opacity: 0.5;
  }
  .form-bodlog .title-log {
    width: 280px;
    margin-top: 10px;
    font-size: 15px;
  }
  .form-bodlog .subscribe {
    margin-top: 10px;
    width: 250px;
    font-size: 60%;
  }
  .form-bodlog .subscribe a {
    color: blue;
  }
}









/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* PANIER PAIEMENT
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */

#paiement {
  margin-bottom: 100px;
}
#paiement .form-log {
  width: 100%;
  height: 400px;
}

.form-header {
  width: 260px;
  height: 70px;
  border-radius: 5px 5px 0px 0px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #c4c4c4;
}

.form-body {
  width: auto;
  height: 320px;
  border: 1px solid #4F555C;
  border-top: none;
  border-radius: 0px 0px 5px 5px;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 5%;
  background-color: white;
}
.form-body .card-number {
  width: 200px;
  height: 25px;
  opacity: 0.5;
}
.form-body .title-pay {
  width: 200px;
  margin-bottom: 0px;
  font-size: 13px;
}

.date-field {
  display: flex;
  justify-content: space-between;
  margin-top: 10px;
  width: 200px;
}
.date-field .month, .date-field .year {
  height: 15px;
  opacity: 0.5;
}

.card-verification {
  display: flex;
  width: 200px;
  opacity: 0.5;
}

.cvv-input {
  margin: 10px 0px 25px 0px;
  width: 200px;
  height: 15px;
}
.cvv-input .cvv {
  width: 85px;
  margin-bottom: 20px;
}

.cvv-details {
  margin-top: 6%;
  font-size: 9px;
}

.paypal-btn,
.proceed-btn {
  cursor: pointer;
  width: 100%;
  height: 30px;
  border-color: transparent;
  border-radius: 6px;
  font-size: 16px;
}

.proceed-btn {
  margin-bottom: 10px;
  background: #FFA755;
}

.paypal-btn a,
.proceed-btn a {
  text-decoration: none;
  cursor: pointer;
}

.proceed-btn a {
  color: #fff;
}

.paypal-btn a {
  color: rgba(242, 242, 242, 0.7);
}

.paypal-btn {
  padding-right: 95px;
  background: url("https://designmodo.com/demo/creditcardform/paypal-logo.svg") no-repeat 65% 56% #009cde;
}



@media screen and (min-width: 770px) and (max-width: 990px) {

  #paiement {
    margin-bottom: 100px;
  }
  #paiement .credit-card {
    width: 100%;
    height: 400px;
  }

  .form-header {
    width: 355px;
    height: 70px;
  }

  .form-body {
    width: auto;
    height: 330px;
  }
  .form-body .card-number {
    width: 250px;
    height: 25px;
    opacity: 0.5;
  }
  .form-body .title-pay {
    width: 250px;
    margin-top: 10px;
    font-size: 15px;
  }

  .date-field {
    display: flex;
    justify-content: space-between;
    margin-top: 10px;
    width: 280px;
  }
  .date-field .month, .date-field .year {
    height: 15px;
    opacity: 0.5;
  }

  .card-verification {
    display: flex;
    width: 280px;
    opacity: 0.5;
  }

  .cvv-input {
    margin: 10px 0px 25px 0px;
    width: 200px;
    height: 15px;
  }
  .cvv-input .cvv {
    width: 85px;
    margin-bottom: 20px;
  }
  
  .cvv-details {
    margin-top: 6%;
    font-size: 9px;
  }
  
  .paypal-btn,
  .proceed-btn {
    cursor: pointer;
    width: 100%;
    height: 30px;
    border-color: transparent;
    border-radius: 6px;
    font-size: 16px;
  }
  
  .proceed-btn {
    margin-bottom: 10px;
    background: #FFA755;
  }
  
  .paypal-btn a,
  .proceed-btn a {
    text-decoration: none;
    cursor: pointer;
  }
  
  .proceed-btn a {
    color: #fff;
  }
  
  .paypal-btn a {
    color: rgba(242, 242, 242, 0.7);
  }
  
  .paypal-btn {
    padding-right: 95px;
    background: url("https://designmodo.com/demo/creditcardform/paypal-logo.svg") no-repeat 65% 56% #009cde;
  }
}
@media screen and (min-width: 991px) {
  #paiement {
    margin-bottom: 100px;
  }
  #paiement .credit-card {
    width: 100%;
    height: 400px;
  }

  .form-header {
    width: 355px;
    height: 70px;
  }

  .form-body {
    width: auto;
    height: 350px;
  }
  .form-body .card-number {
    width: 250px;
    height: 25px;
    opacity: 0.5;
  }
  .form-body .title-pay {
    width: 250px;
    margin-top: 10px;
    font-size: 15px;
  }

  .date-field {
    display: flex;
    justify-content: space-between;
    margin-top: 10px;
    width: 280px;
  }
  .date-field .month, .date-field .year {
    height: 15px;
    opacity: 0.5;
  }

  .card-verification {
    display: flex;
    width: 280px;
    opacity: 0.5;
  }
}
</style>