<template>
  <div id="app">
    <nav-bar></nav-bar>
    <div class="columns">
      <add-people></add-people>
      <list-people></list-people>
    </div>
  </div>
</template>

<script>
import AddPeople from './components/AddPeople'
import Event from './components/Event'
import ListPeople from './components/ListPeople'
import NavBar from './components/NavBar'

export default {
  name: 'app',
  components: {
    AddPeople, Event, ListPeople, NavBar
  }
}
</script>

<style>
</style>
