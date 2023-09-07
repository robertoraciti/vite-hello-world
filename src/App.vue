<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

export default {
  data() {
    return {
      title: "",
    };
  },

  components: {
    AppTitle,
    AppHero,
  },
};
</script>

<template>
  <AppTitle />
  <AppHero />
</template>

<style scoped></style>
