<template>
  <div>
    <button @click="baidu">baidu</button>
  </div>
</template>

<script>
export default {
  name: "baidu",
  methods:{
    baidu(){
      window.open("https://www.baidu.com/")
    }
  }
}
</script>

<style scoped>

</style>