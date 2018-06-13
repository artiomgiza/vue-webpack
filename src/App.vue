<template>
  <div id="app">
    <h1>Let's go somwhere!</h1>
    <p>Finished: academind <a href="https://www.youtube.com/playlist?list=PL55RiY5tL51p-YU-Uw90qQH419BM4Iz07">Vue.js 2 Getting Started course</a></p>
    <hr>
    <router-link to="/">Home</router-link>
    <router-link to="/users/10">Users10</router-link>
    <router-link to="/users/12">Users12</router-link>
    <hr>

    <router-view></router-view>
  </div>
</template>

<script>
export default {
  data () {
    return {

    }
  }
}
</script>

<style>

</style>
