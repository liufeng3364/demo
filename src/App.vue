<template>
  <div id="app">
    <el-row>
      <el-col :span="24">
        <el-container>
          login
        </el-container>
      </el-col>
    </el-row>
  </div>
</template>

<script>

export default {
  name: 'app',
  components: {
    
  }
}
</script>

<style>
#app {
  width: 1200px;
  margin: 0 auto;

}
.el-container{
  width: 700px;
  height: 500px;
  margin: 100px auto;
  background: #409EFF;

}

</style>
