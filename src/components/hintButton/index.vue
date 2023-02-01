<template>
  <div>
      <a :title="tip">
          <el-button  v-bind="$attrs" v-on="$listeners"></el-button>
      </a>
  </div>
</template>

<script>
export default {
  name: 'hintButton',
  props:['tip'],
  mounted(){
    console.log(this.$attrs);
    console.log(this.$listeners);
  }

}
</script>

<style scoped>

</style>
