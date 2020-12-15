<template>
    <section id="main-img2">
        <h1 id="votre-voy">VOTRE VOYAGE</h1>
    </section>
</template>
<script>
export default {
    
}
</script>
<style>
#main-img2 {
  background-image: url("https://zupimages.net/up/20/49/yed6.jpg");
  height: 100px;
  width: auto;
  margin-bottom: 35px;
}

#nav {
  margin-bottom: 10px;
}

#votre-voy {
  font-family: "Oswald", sans-serif;
  font-weight: 400;
  font-size: 35px;
  color: white;
  height: 100px;
  display: flex;
  justify-content: center;
  align-items: center;
}

@media screen and (min-width: 770px) and (max-width: 990px)  {
  /* main image */
  #main-img2 {
    height: 150px;
    margin-bottom: 35px;
  }

  #votre-voy {
    font-size: 40px;
    height: 150px;
  }
}
@media screen and (min-width: 991px) {
  /* main-img */
  #main-img2 {
    height: 300px;
  }

  #votre-voy {
    font-size: 75px;
    height: 300px;
  }
}
</style>


