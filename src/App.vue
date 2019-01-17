<template>
  <div id="app">
    <div class="wrapper">
      <div id="nav">
        <div id="logo">
          <h3>Movies</h3>
          <h6>Trailer</h6>
        </div>

        <div id="order">
          <button>order a ticket</button>
        </div>
      </div>
      <div class="content">
      <movie-details></movie-details>
      <related></related>
      </div>
    </div>
  </div>
</template>

<script>
import movieDetails from '../src/components/movie-details.vue'
import related from '../src/components/related.vue'
export default {
  components:{
    'movieDetails': movieDetails,
    'related': related
  }
}
</script>


<style lang="sass">
@import "../src/sass/main.sass"
</style>
