<template>
  <div id="app">
    <ul class="nav nav-tabs bg-dark">
      <li class="nav-item">
        <router-link class="nav-link" to="/">Home</router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" to="/privacy">Privacy</router-link>
      </li>
    </ul>
    <router-view style="max-height: calc(100% - 63.42px);"/>
  </div>
</template>

<style>
  #app {
    width: 100%;
    height: 100vh;
  }
</style>
