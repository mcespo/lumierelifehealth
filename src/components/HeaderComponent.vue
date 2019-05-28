<template>
  <header class="header navbar has-shadow is-spaced">
    <div class="container">
      <nav class="navbar-menu">
        <g-link class="navbar-start" to="/"><g-image src="~/uploads/images/lumiere-health_logo.png" width="150" fit="contain" /></g-link>
        <div class="navbar-end">
          <g-link class="navbar-item" to="/">Home</g-link>
          <g-link class="navbar-item" to="/about">About</g-link>
          <g-link class="navbar-item" to="/fitness-events">Fitness Events</g-link>
          <g-link class="navbar-item" to="/private-training">Private Training</g-link>
        </div>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: 'HeaderComponent'
}
</script>

<style lang="scss">
</style>
