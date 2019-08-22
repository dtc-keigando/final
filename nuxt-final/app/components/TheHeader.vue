<template>
  <el-menu mode="horizontal" :router="true">
    <el-menu-item index="1" style="pointer-events:none;">
      Nuxt Diary App
    </el-menu-item>
    <el-menu-item index="2" :route="{ path: '/' }">
      投稿一覧
    </el-menu-item>

    <no-ssr>
      <el-menu-item index="4" style="float: right;">
        <span>学習</span>
      </el-menu-item>
    </no-ssr>
    <el-menu-item index="5" style="float: right" >
      demo
    </el-menu-item>
  </el-menu>
</template>

<script>

</script>
