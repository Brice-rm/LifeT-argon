<template>
  <main>
    <div id="container-titre1">
      <p id="titre1">PAYSAGE</p>
    </div>
    <section class="video">
      <iframe
        width="500"
        height="315"
        src="https://www.youtube.com/embed/BHACKCNDMW8?start=26"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
    </section>
  </main> 
</template>
<script>
  export default {};
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
    margin-top: 150px;
    height: 80px;
    width: 100%;
  }

  .img-f {
    margin-left: 10px;
    width: 25px;
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
    margin-top: 30px;
    height: 120px;
    width: 100%;
    padding-top: 15px;
    padding-bottom: 5px;
  }

  .img-f {
    margin: 10px;
    width: 30px;
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