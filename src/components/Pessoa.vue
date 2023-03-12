<template>
  <section>
    <h2>Esta é a descrição da pessoa: {{ nome }}</h2>
    <Info />
    <Formc />
  </section>
</template>

<script>
import Info from "./Info.vue";
import Formc from "./Formc.vue";

export default {
  name: "Pessoa",
  components: {
    Info,
    Formc,
  },
  data() {
    return {
      nome: "Pedro",
    };
  },
};
</script>