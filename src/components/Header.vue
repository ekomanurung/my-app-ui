<template>
  <div class="navbar-fixed">
    <nav class="blue lighten-1">
      <div class="nav-wrapper">
        <div class="container">
          <a href="#!" class="brand-logo">
            <i class="material-icons logo">polymer</i>picnic
          </a>
          <a href="#" data-target="mobile-nav" class="sidenav-trigger">
            <i class="material-icons" @click="loadHamburger()">menu</i>
          </a>
          <ul class="right hide-on-med-and-down">
            <li>
              <a href="#">Services</a>
            </li>
            <li>
              <a href="#">Contact us</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <ul class="sidenav" id="mobile-nav">
      <li>
        <a href="#">Services</a>
      </li>
      <li>
        <a href="#">Contact us</a>
      </li>
    </ul>
  </div>
</template>


<style scoped>
.brand-logo {
  font-family: cursive;
  font-size: 25px;
}

.brand-logo i,
.brand-logo i.material-icons {
    margin-right: 5px;
}
</style>

<script>
import M from "materialize-css";
export default {
  name: "header",
  methods: {
    loadHamburger() {
      M.Sidenav.init(this.elem);
    }
  },
  computed: {
    elem() {
      return document.querySelectorAll(".sidenav");
    }
  }
};
</script>