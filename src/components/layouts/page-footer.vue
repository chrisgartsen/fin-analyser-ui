<template>
  <footer class="footer is-primary">
    <div class="content has-text-centered has-text-white">
      <p>
        <b-button tag="router-link" to="/about" type="is-link">About</b-button>
        <b-button tag="router-link" to="/contact" type="is-link">Contact</b-button>
      </p>
      <p>Bank Analyser© 2019</p>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'page-footer'
}
</script>