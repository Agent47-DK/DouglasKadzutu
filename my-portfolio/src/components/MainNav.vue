<template>
  <nav class="navbar navbar-expand-lg fixed-top">
    <div class="container-fluid">
      <a class="navbar-brand" href="#" @click="handleMenuItemClick">Dee Kay</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link" href="#section1">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#section2">Education</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#section2">Projects</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#section2">Employment</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#section2">Interests</a>
          </li>
          <!-- Add more list items for other sections -->
        </ul>
      </div>
    </div>
  </nav>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "MainNav",
  // components: { to import},
  // props: {},
  setup() {
    const handleMenuItemClick = () => {
      console.log("menu clicked");
    };

    return {
      handleMenuItemClick,
    };
  },
});
</script>

<style lang="scss" scoped>
.navbar {
    margin-bottom: 0px;
    background-color: transparent !important;

}
.navbar-nav .nav-item .nav-link ,.navbar-brand{
    color: #FFFF66;
    font-size: larger;
}


</style>
