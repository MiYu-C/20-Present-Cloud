<template>
  <div>
    <nav-menu></nav-menu>
    <el-breadcrumb></el-breadcrumb>
    <router-view/>
  </div>
</template>

<script>
import NavMenu from './common/NavMenu'
import Breadcrumb from './Common/Breadcrumb'
export default {
  name: 'Home',
  components: {NavMenu, Breadcrumb}
}
</script>

<style scoped>

</style>
