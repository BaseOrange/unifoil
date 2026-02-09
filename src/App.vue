<template>
  <el-row>
    <el-col :span="8">
      <div class="hight bkcolor1">111</div>
    </el-col>
    <el-col :span="16">
      <div class="hight bkcolor2">222</div>
    </el-col>
  </el-row>
</template>

<script>
import { ElButton } from "element-plus";

export default {
  components: { ElButton },
};
</script>

<style scoped>
.hight {
  height: 100%;
}
.bkcolor1 {
  background-color: aqua;
}
.bkcolor2 {
  background-color: blue;
}
</style>
