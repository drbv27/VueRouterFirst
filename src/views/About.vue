<template>
  <div class="about">
    <Titulo texto="Acerca de: " />
    <!-- <h1>This is an about page</h1> -->
  </div>
</template>
<script>
import Titulo from "../components/Titulo.vue";

export default {
  name: "About",
  components: {
    Titulo,
  },
};
</script>
