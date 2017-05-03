<template>
  <div>
    <nav class="nav">
      <div class="nav-left">
        <div class="nav-item">
          <a href="#">
            <img src="http://bulma.io/images/bulma-logo.png" alt="Bulma: a modern CSS framework based on Flexbox">
          </a>
        </div>
      </div>
      <div class="nav-center">

      </div>
      <span v-on:click="setActive" v-bind:class="{ 'is-active' : isActive }" class="nav-toggle">
        <span></span>
        <span></span>
        <span></span>
      </span>
      <div v-bind:class="{ 'is-active' : isActive }" class="nav-right nav-menu">
        <a class="nav-item"href="#">Home</a>
        <a class="nav-item"href="#">Clubber</a>
        <a class="nav-item"href="#">Events</a>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'nav-bar',
  data: function () {
    return {
      isActive: false
    }
  },
  methods: {
    setActive: function () {
      this.isActive = !this.isActive;
    }
  }
}
</script>
