<template>
  <head-line />
  <search />
  <movie-list />
</template>

<script>
import HeadLine from "../components/Headline.vue"
import Search from "../components/Search.vue"
import MovieList from "../components/MovieList.vue"

export default {
  components: {
    HeadLine,
    Search,
    MovieList
  }
}
</script>