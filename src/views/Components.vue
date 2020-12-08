<template>
    <div>
      <mainimg></mainimg>
      <carousel></carousel>
      <picto></picto>
      <video></video>
      
    </div>
</template>
<script>
import Mainimg from "./components/mainimg";
import Carousel from "./components/carousel";
import Picto from "./components/picto";
import Video from "./components/video";



export default {
  name: "components",
  components: {
    Mainimg,
    Carousel,
    Picto,
    Video
  },
};
</script>
