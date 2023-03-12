<template>
  <PrimeiroComponent />
  <LifeCycle />
  <Pessoa />
</template>

<script>
import PrimeiroComponent from "./components/PrimeiroComponent.vue";
import LifeCycle from "./components/LifeCycle.vue";
import Pessoa from "./components/Pessoa.vue";

export default {
  name: "App",
  components: {
    PrimeiroComponent,
    LifeCycle,
    Pessoa,
  },
};
</script>