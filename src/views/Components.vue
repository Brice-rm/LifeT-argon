<template>
<div>
    <mainimg></mainimg>
    <carousel></carousel>
    <picto></picto>
    <!-- <video></video> -->
</div>
</template>
<script>
import Carousel from './components/Carousel';
import Mainimg from './components/Mainimg';
import Picto from './components/Picto';
// import Video from './components/video';

export default {
  name: "components",
  components: {
    Mainimg,
    Carousel,
    Picto,
    // Video
  }
};

</script>
