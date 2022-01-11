<template>
  <div class="container">
    <div class="inner"></div>
    <movie-item 
    v-for="movie in movies" 
    :key="movie.imdbID" />
  </div>
</template>

<script>
import MovieItem from '~/components/MovieItem'
export default {
  components: {
    MovieItem
  },
  data: () => ({
    movies: []
  })
}
</script>