<template>
  <div class="container">
    <section id="main-banner"></section>
    <section id="popular-location" class="popular-location">
      <h4 class="section-title blue-text text-lighten-1 center">Popular Destinations</h4>
      <div class="row">
        <div class="col s12 m4">
          <img class="responsive-img popular-image" src="../assets/images/bali.jpg" alt="bali" />
        </div>
        <div class="col s12 m4">
          <img class="responsive-img popular-image" src="../assets/images/toba.jpg" alt="toba" />
        </div>
        <div class="col s12 m4">
          <img class="responsive-img popular-image" src="../assets/images/lombok.jpg" alt="lombok" />
        </div>
        <div class="col s12 m4">
          <img
            class="responsive-img popular-image"
            src="../assets/images/raja-ampat.jpeg"
            alt="raja ampat"
          />
        </div>
        <div class="col s12 m4">
          <img
            class="responsive-img popular-image"
            src="../assets/images/bandung.jpg"
            alt="bandung"
          />
        </div>
        <div class="col s12 m4">
          <img
            class="responsive-img popular-image"
            src="../assets/images/derawan.jpeg"
            alt="derawan"
          />
        </div>
      </div>
    </section>
    <section id="main-usp" class="main-usp">
      <h4 class="section-title blue-text text-lighten-1 center">Our Services</h4>
      <div class="row">
        <div class="col m6 s12">
          <i class="material-icons blue-text text-lighten-2 medium left">device_hub</i>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda ullam sed alias maiores! Vel nemo sed quos ab delectus consectetur.</p>
        </div>
      </div>
      <div class="row">
        <div class="col m6 s12 right">
          <i class="material-icons medium left blue-text text-lighten-2">local_offer</i>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda ullam sed alias maiores! Vel nemo sed quos ab delectus consectetur.</p>
        </div>
      </div>
      <div class="row">
        <div class="col m6 s12">
          <i class="material-icons medium left blue-text text-lighten-2">card_travel</i>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda ullam sed alias maiores! Vel nemo sed quos ab delectus consectetur.</p>
        </div>
      </div>
      <div class="row">
        <div class="col m6 s12 right">
          <i class="material-icons medium left blue-text text-lighten-2">location_on</i>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda ullam sed alias maiores! Vel nemo sed quos ab delectus consectetur.</p>
        </div>
      </div>
      <div class="row">
        <div class="col m6 s12">
          <i class="material-icons medium left blue-text text-lighten-2">local_phone</i>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda ullam sed alias maiores! Vel nemo sed quos ab delectus consectetur.</p>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.section-title {
  margin-bottom: 30px;
}

.main-usp p {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

.popular-location .row .col {
    padding: 0.4rem;
}

.responsive-img {
  height: 200px;
  width: 100%;
}

.popular-image {
  /* border: 1px solid; */
  border-radius: 5px;
}
</style>

<script>
export default {
  name: "main-page"
};
</script>