<!-- slider di immagini  -->
<script>

  export default {
  name: "SliderSection",

  data() {
    return {
      slides: [
        { img: "https://picsum.photos/seed/picsum/200/300", }, { img: "https://picsum.photos/seed/picsum/200/300", }, { img: "https://picsum.photos/seed/picsum/200/300", }, { img: "https://picsum.photos/seed/picsum/200/300", },
      ],
    };
  },
};
</script>

<!-- Template -->
<template>
    <section class="slider-section">
        <div class="slider">
            <div class="slide" v-for="(slide, index) in slides" :key="index">
                <img :src="slide.img" alt="slide" />
            </div>
        </div>
    </section>
</template>

<!-- Style -->
<style scoped>
.slider-section {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  border: dotted 1px #42b983;
}

.slider {
  width: 80%;
  height: 80%;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  gap: 2rem;
  cursor: pointer;
  padding: 1rem;
}

.slide {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.slide img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.slide img:hover {
  transform: scale(1.1);
  transition: all 0.3s ease-in-out;
}
</style>