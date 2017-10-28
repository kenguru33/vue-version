<template>
  <div class="version">
    You are using Vue {{version}}
  </div>
</template>
<script type="text/javascript">
import Vue from 'vue'
export default {
  name: 'vue-version',
  computed: {
    version () {
      return Vue.version
    }
  }
}
</script>
<style>
.version {
  font-weight: bold;
  font-family: tahoma;
}
</style>