<template>
    <div>
        <mainimgbis></mainimgbis>
        <rechercheb></rechercheb>
    </div>
</template>
<script>
import Mainimgbis from './recherchev/Mainimgbis';
import Rechercheb from './recherchev/Rechercheb';


// import Video from './components/video';

export default {
  name: "recherchev",
  components: {
    Mainimgbis,  
    Rechercheb

    // Video
  }
};

</script>