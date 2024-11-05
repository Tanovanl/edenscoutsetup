<template>
  <nav>
    <div id="brand">
      <img src="../assets/logo.png" alt="Edenscouts logo" />
      <h1>Edenscouts</h1>
    </div>
    <div id="navigation"></div>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/deployments">Deployments</RouterLink>
  </nav>
</template>

<script>
import { RouterLink, RouterView } from 'vue-router'

</script>

<style>
  nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem;
    border-bottom: 1px solid var(--orange-primary-color);
    max-height: 7vh;
  }

  #brand {
    display: flex;
    align-items: center;
  }

  #navigation {
    display: flex;
    gap: 1rem;
  }

  nav a {
    display: inline-block;
    padding: 0 1rem;
    text-decoration: none;
  }


</style>