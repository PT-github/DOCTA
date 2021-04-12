<!--
 * @Author: PT
 * @Date: 2020-06-04 10:04:33
 * @LastEditors: PT
 * @LastEditTime: 2021-04-12 10:10:58
 * @Description: 测试文件
--> 
<template>
  <div
    class="test"
    style="height: 100%"
  >
      AAA
  </div>
</template>

<script>
export default {
  name: 'Test',
  data () {
    return {
    }
  },

  components: {},

  computed: {},

  mounted () {},

  methods: {},

  watch: {}
}
</script>
<style lang='scss' scoped>
.test {
  border: 1px solid red;
  color: $color;
}
</style>
<style lang='less' scoped>
.test {
  .h2 {
    color: @color;
  }
}
</style>