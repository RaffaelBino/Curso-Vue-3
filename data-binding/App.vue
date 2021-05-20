<template>
  <div>
    <h1 :style="{ textDecoration: decoration}">Hello {{ name }}!</h1>
    <input type="text" v-model="name">
    <br>

    <a :href="link">Link para o perfil</a>
  </div>
</template>

<script>
export default {
  data: () => ({
    name: 'Raffael',
    link: 'https://raffaelbino.github.io',
    decoration: 'underline'
  }),
};
</script>

<style></style>
