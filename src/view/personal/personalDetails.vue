<template>
  <div>
    <h3>{{ id }}的个人信息</h3>
    <p>姓名：曹水明</p>
    <p>年龄：23</p>
    <p>籍贯：湖南</p>
    <p>个人简介：这个人很懒，什么都没有留下哦。</p>
  </div>
</template>

<script>
export default {
  name: "personalDetails",
  props: ["id"]
}
</script>

<style scoped>

</style>