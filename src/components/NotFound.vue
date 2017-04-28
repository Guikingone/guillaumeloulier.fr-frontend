<template>
  <div>
    <p>
      Oops, looks like something is going wrong, this page isn't available on the server
    </p>
    <router-link to="/">Retourner à l'accueil</router-link>
  </div>
</template>

<script>
export default {
  name: 'NotFound',
  data () {
    return {
    }
  }
}
</script>

<style scoped>
  p {
    text-align: center;
    font-family: "Agency FB";
    font-size: 35px;
  }
</style>
