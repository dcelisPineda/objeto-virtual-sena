<template>
  <router-view />
</template>
<script>
// Para usar el store en sus componentes, vistas primero importamos el vuex
export default {
  // components: { Menu },
  setup() {
    // Y luego le asignamos a una variable el store
    // const store = useStore()
  },
};
</script>
<style lang="scss">
@import "@/styles/variables.scss";
html {
  font-family: "Poppins", sans-serif;
  scroll-behavior: smooth;
}
body {
  margin: 0;
  background-color: $tertyary-color;
}

.cite {
  color: $cite;
  text-decoration: none;
}
</style>
