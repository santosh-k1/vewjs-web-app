<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
     <app-aboutus></app-aboutus>
  </div>
</template>
<script>
import header from '@/components/header/index'
export default {
  name: 'About',
  components: {
    'app-aboutus': header
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
