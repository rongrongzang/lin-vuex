<!-- lin-vue -->
<template>
  <div>

    <h1 style="text-align:center">linronglang-vue</h1>
    <button @click='add()'>add</button>
      {{count}}
  </div>
</template>

<script>
import { mapMutations, mapState } from "vuex";
export default {
  data() {
    return {};
  },

  //组件
  components: {},

  //计算属性
  computed: mapState(["count"]),
  //方法
  methods: mapMutations(["add"]),

  //组件创建完毕
  created() {},

  //挂载完毕
  mounted() {},

  //销毁完成
  destroyed() {}
};
</script>

<style scoped>

</style>