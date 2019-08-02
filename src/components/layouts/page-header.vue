<template>
    <nav class="navbar is-primary" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <router-link to="/" class="navbar-item is-size-2">Bank Analyser</router-link>

        <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>

  <div id="navbarBasicExample" class="navbar-menu">
    <div class="navbar-start">
      <router-link to="/login" class="navbar-item">An action</router-link>

    </div>

    <div class="navbar-end">
      <div class="navbar-item">
        <div class="buttons">
          <b-button type="is-primary" to="/login">Login</b-button>
        </div>
      </div>
    </div>
  </div>
</nav>
</template>

<script>
export default {
  name: 'page-header'
}
</script>