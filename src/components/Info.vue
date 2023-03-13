<template>
  <div>
    <p v-if="esta_trabalhando">Estou trabalhando no momento.</p>
    <p v-else>Estou em busca de novas oportunidades.</p>
    <p>Utilizo as seguintes tecnologias:</p>
    <ul>
      <li>JavaScript</li>
      <li>Angular</li>
      <li>Vue</li>
    </ul>
    <p v-show="mostrar_email">Mande uma mensagem para: {{ email }}</p>
    <p>
      Para acessar meu portfolio,
      <a v-bind:href="meu_link">basta clickar aqui</a>
    </p>
    <Picture />
  </div>
</template>

<script>
import Picture from "./Picture.vue";
export default {
  name: "Info",
  data() {
    return {
      esta_trabalhando: true,
      mostrar_email: true,
      email: "email@dominio.com",
      meu_link: "https://www.google.com",
    };
  },
  components: {
    Picture,
  },
};
</script>