<template>
  <TopoView />

  <IntroducaoView />

  <ApresentacaoView />

  <LaLune />
</template>

<script>
import TopoView from "../components/TopoView.vue";
import IntroducaoView from "../components/IntroducaoView.vue";
import ApresentacaoView from "../components/ApresentacaoView.vue";
import LaLune from "../components/LaLune.vue";
export default {
  name: "HomeView",
  components: {
    TopoView,
    IntroducaoView,
    ApresentacaoView,
    LaLune,
  },
};
</script>

<style>
</style>