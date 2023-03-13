<template>
  <Header />
  <PrimeiroComponent />
  <LifeCycle />
  <Pessoa />
</template>

<script>
import PrimeiroComponent from "./components/PrimeiroComponent.vue";
import Header from "./components/Header.vue";
import LifeCycle from "./components/LifeCycle.vue";
import Pessoa from "./components/Pessoa.vue";

export default {
  name: "App",
  components: {
    PrimeiroComponent,
    LifeCycle,
    Pessoa,
    Header,
  },
};
</script>

<style>
body {
  background-color: #333;
  color: #fff;
}
</style>