<template>
  <el-container class="layout-default">
    <el-header>
      <mt-header />
    </el-header>
    <el-main>
      <nuxt />
    </el-main>
    <el-footer>footer</el-footer>
  </el-container>
</template>

<script>
import MtHeader from '@/components/public/header/index.vue'

export default {
  components: {
    MtHeader
  }
}
</script>
