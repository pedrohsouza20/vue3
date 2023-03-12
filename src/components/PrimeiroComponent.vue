<template>
  <section>
    <h1>Olá Vue!</h1>
    <p>Meu nome é {{ personName }}, e atuo como {{ profission }}</p>
  </section>
</template>

<script>
export default {
  name: "PrimeiroComponent",
  data() {
    return {
      personName: "Pedro",
      profission: "Programador de Sistemas",
    };
  },
};
</script>