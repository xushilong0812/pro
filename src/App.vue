<template>
  <div id="app">
      <FootberNav/>
      <router-view></router-view>
  </div>
</template>
<script>
import FootberNav from "@/components/FootberNav/FootberNav";
export default {
  components:{
FootberNav,
  }
}
</script>
<style lang="stylus">

</style>
