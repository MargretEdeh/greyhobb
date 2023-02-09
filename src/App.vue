<template>
  <div class="the-component" >
  <div class="hero">
    <firstSection />
    <!-- <GridedImages/> -->
    <img class="grid-img animate__animated animate__fadeInRight" src="./assets/hero-right-pic.png" alt="pic"/>
  </div>
  <!-- <div>
  <Socials/>  
  </div> -->
  <div>
  <SecondSection/>  
  </div>
  </div>
</template>

<script>
import firstSection from "./components/FirstSection";
import SecondSection from "./components/SecondSection.vue";
// import GridedImages from "./components/GridedImages.vue";

export default {
  name: "App",
  components: {
    firstSection,
    SecondSection,
    // GridedImages
  },
};
</script>

<style>
.hero {
  margin:2em 0 0 10em;
  padding: 0;
  display:flex;
}
.photo-sec {
  border: 2px solid red;
}
.each-pic {
  max-width: 40%;
  width: 50%;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}
.the-component {
  max-width: 100%;
  width: 100%;
  max-width: 100%;
  padding: 0;
}
.grid-img{
  height: auto;
  max-width:100%;
  width: 80%;
}
* {
  
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  max-width: 100%;
  margin: 5px;
  padding: 10px;
}
@media screen and (max-width: 1300px) {
  .hero {
    margin:0;
  flex-direction: column;
}
.grid-img{
max-width: 100%;
width: 75%;
margin: 0 auto;

}
}
  
</style>

https://i.imgur.com/waYx2ir.png https://i.imgur.com/64phpkV.png
https://i.imgur.com/XG4j9ha.png https://i.imgur.com/OFdfhJb.png
https://i.imgur.com/QPi5iRU.png https://i.imgur.com/CkR6Lxf.png
blob:https://imgur.com/84fc9248-7db3-4079-a719-df00d2c9d270
https://i.imgur.com/LL7Ymvg.png


<!-- div class="each-pic">
        <PhotosSection source=" https://i.imgur.com/waYx2ir.png" />
        <PhotosSection source="https://i.imgur.com/64phpkV.png" />
        <PhotosSection source="https://i.imgur.com/XG4j9ha.png" />
        <PhotosSection source="https://i.imgur.com/OFdfhJb.png" />
        <PhotosSection source="https://i.imgur.com/QPi5iRU.png" />
        <PhotosSection source="https://i.imgur.com/CkR6Lxf.png" />
        <PhotosSection source="https://i.imgur.com/SU2XR4T.png" />
        <PhotosSection source="https://i.imgur.com/LL7Ymvg.png " />
      </div> -->

     