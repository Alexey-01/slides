<template>
  <div class="app-content">
    <div class="app-child-1">
      <div class="head">МЦД1</div>
    </div>
    <div class="app-child-2">
      <div class="head"><h1>Trololo</h1></div>
      <div class="route-line"></div>
      <div class="point">
        <RoutePoint/>
      </div>
    </div>
    <div class="app-child-3">
      <div class="head"><h1>Trololo</h1></div>
    </div>
    <div class="app-child-4">
      <div class="head"><h1>Trololo</h1></div>
    </div>
    <div class="app-child-5">
      <div class="head"><h1>Trololo</h1></div>
    </div>
    <div class="app-child-6">
      <div class="head"><h1>Trololo</h1></div>
    </div>
    <div class="app-child-7">
      <div class="head"><h1>Trololo</h1></div>
    </div>
    <div class="app-child-8">
      <div class="head"><h1>Trololo</h1></div>
    </div>
  </div>
</template>

<script>
import RoutePoint from './RoutePoint'
export default {
  components: {
    RoutePoint
  }
}
</script>

<style scoped>
  .app-content{
    display: flex;
  }
  .point{
    position: relative;
    top: -11px;
  }
  .head{
    height: 140px;
    width: 100%;
  }
  .route-line{
    height: 4px;
    background-color: white;
    border-top: 3px solid #ba8cbe;
    border-bottom: 3px solid #ba8cbe;
    margin-top: 5px;
    width: 100%;
  }
  .app-child-1{
    width: 117px;
    height: 282px;
    flex: none;
  }
  .app-child-2{
    width: 380px;
    height: 282px;
  }
  .app-child-3{
    height: 282px;
    flex: 1 0 auto;
  }
  .app-child-4{
    height: 282px;
    flex: 1 0 auto;
  }
  .app-child-5{
    height: 282px;
    flex: 1 0 auto;
  }
  .app-child-6{
    height: 282px;
    flex: 1 0 auto;
  }
  .app-child-7{
    height: 282px;
    flex: 1 0 auto;
  }
  .app-child-8{
    height: 282px;
    flex: 1 0 auto;
  }
</style>
