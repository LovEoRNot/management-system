<template>
  <div id="component-index">
    <Banner></Banner>
    <Search></Search>
  </div>
</template>

<script>
import Banner from './Banner.vue'
import Search from './Search.vue'
export default {
  name: 'app',
  components: {
      Banner,
      Search
  }
}
</script>
