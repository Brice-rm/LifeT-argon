<template>
  <!-- <header class="header-global">
    <div style="position: relative">
      <img src="img/Life/logo life travel.png" id="logo">
      <base-nav type="white" effect="light" expand>
      
        <ul class="navbar-nav m-0 flex justify-content-lg-end">
          <li class="nav-item">
            <a class="nav-link nav-link-icon" href="#"> ACCUEIL </a>
          </li>
          <li class="nav-item">
            <a class="nav-link nav-link-icon" href="#"> PANIER </a>
          </li>
               <li class="nav-item">
            <a class="nav-link nav-link-icon" href="#"> CONTACTS </a>
          </li>
          

        </ul>
      </base-nav>
    </div>
  </header> -->
  <b-navbar toggleable type="light" variant="light">
   <img src="img/Life/logo life travel.png" id="logo">

    <b-navbar-toggle target="navbar-toggle-collapse">
      <template #default="{ expanded }">
        <b-icon v-if="expanded" icon="chevron-bar-up"></b-icon>
        <b-icon v-else icon="chevron-bar-down"></b-icon>
      </template>
    </b-navbar-toggle>

    <b-collapse id="navbar-toggle-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="#">ACCUEIL</b-nav-item>
        <b-nav-item href="#">PANIER</b-nav-item>
        <b-nav-item href="#" disabled>CONTACTS</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>


// export default {

// };
</script>
<style>

* {
  margin: 0;
  padding: 0;
  color: #4F555C;
}
p {
   margin: 0;
}

/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
/* HEADER */
/* !!!!!!!!!!!!!!!!!!!!!!!!!!! */
#logo {
  height: 60px;
  margin: 10px 0px 0px 10px;
}

@media screen and (min-width: 770px) and (max-width: 990px) {
  #logo {
    height: 60px;
    margin: 5px 0px 0px 10px;
  }
}
@media screen and (min-width: 991px) {
  #logo {
    height: 60px;
    margin: 0px 0px 0px 15px;
  }
}
.navbar{
  z-index: 100;
}
</style>
