<template>
  <PrimeiroComponent />
  <LifeCycle />
</template>

<script>
import PrimeiroComponent from "./components/PrimeiroComponent.vue";
import LifeCycle from "./components/LifeCycle.vue";

export default {
  name: "App",
  components: {
    PrimeiroComponent,
    LifeCycle,
  },
};
</script>