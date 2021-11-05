<template>
  <Titulo texto="Ruta con parametro" />
  <h2>Parametro: {{ $route.params.id }}</h2>
</template>

<script>
import Titulo from "../components/Titulo.vue";
export default {
  components: {
    Titulo,
  },
};
</script>

<style></style>
