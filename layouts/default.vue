<template>
  <div>
    <div class="hero">
      <Nuxt />
    </div>
    <footer class="footer">
      <div class="content has-text-centered">
        <p><NuxtLink to="/grow">GROW</NuxtLink></p>
        <p>Copyright &copy; 2023 Spero Autem LLC. All Rights Reserved.</p>
        <a href="https://twitter.com/PwrfulQuestions"
          ><b-icon icon="twitter" size="is-large" type="is-dark"
        /></a>
        <p><NuxtLink to="/privacy">Privacy Policy</NuxtLink></p>
        <p><NuxtLink to="/about">About</NuxtLink></p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "defaultLayout",
};
</script>
