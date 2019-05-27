<template>
    <div class="progress">
      <div class="progress-bar" role="progressbar" aria-valuenow="70"
           aria-valuemin="0" aria-valuemax="100" style="width:62%">
      </div>
    </div>
</template>

<script>
export default {
}
</script>

<style scoped>
  .progress-bar {
    display: -ms-flexbox;
    display: -webkit-box;
    display: flex;
    -ms-flex-direction: column;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    flex-direction: column;
    -ms-flex-pack: center;
    -webkit-box-pack: center;
    justify-content: center;
    color: #fff;
    text-align: center;
    white-space: nowrap;
    background-color: #ba8cbe;
    -webkit-transition: width 0.6s ease;
    transition: width 0.6s ease;
  }

  .progress {
    display: -ms-flexbox;
    display: -webkit-box;
    display: flex;
    height: 0.5rem;
    overflow: hidden;
    font-size: 0.75rem;
    background-color: #e9ecef;
    border-radius: 0.25rem;
  }
</style>
