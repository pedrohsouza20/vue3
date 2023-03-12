<template>
  <h1>Meu nome é: {{ personName }}</h1>
</template>

<script>
export default {
  name: "LifeCycle",
  data() {
    return {
      personName: "Carlos",
    };
  },
  created() {
    setTimeout(() => {
      this.personName = "André";
    }, 1000);
  },
  mounted() {
    setTimeout(() => {
      this.personName = "Pedro";
    }, 2000);
  },
};
</script>