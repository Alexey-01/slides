<template>
  <div class="route-app">
    <AppBar/>
    <AppBody/>
  </div>
</template>

<script>
import AppBar from './AppBar'
import AppBody from './AppBody'
export default {
  components: {
    AppBar,
    AppBody
  }
}
</script>

<style scoped>
  .route-app{
    background-image: url("../../assets/images/dver1.png");
    height: 335px;
    width: 100%;
  }
</style>
