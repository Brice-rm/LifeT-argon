<template>

<div style="position: relative">
<base-nav type="white" effect="light" expand>
    <a class="navbar-brand" href="#"></a>

    <div class="row" slot="content-header" slot-scope="{closeMenu}">
        <div class="col-6 collapse-brand">
                <img src="img/Life/logo life travel.png" id="logo">
        </div>
        <div class="col-6 collapse-close">
            <close-button type="button" @click="closeMenu"></close-button>
        </div>
    </div>

    <ul class="navbar-nav ml-lg-auto">
        <li class="nav-item">
            <router-link to='/' class="nav">
                ACCUEIL
            </router-link>
        </li>
        <li class="nav-item">
            <a class="nav-link nav-link-icon" href="#">
                PANIER
            </a>
        </li>
          <li class="nav-item">
            <router-link to='/Landing' class="nav" >
                CONTACTS
            </router-link>
        </li>
    </ul>
 </base-nav>
</div>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};
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
.nav{
  font-family: "Roboto", sans-serif;
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

