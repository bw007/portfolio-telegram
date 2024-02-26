<template>
  <aside class="list">
    <header-part />
    <el-scrollbar height="calc(100% - 64px)">
      <list-item v-for="(item, index) in 15" :key="index" />
    </el-scrollbar>
  </aside>
</template>

<script>
import ListItem from './list-item.vue';
import HeaderPart from './header-part.vue';

export default {
  components: { 
    ListItem, 
    HeaderPart 
  }
}
</script>

<style lang="css">
.list {
  max-width: 364px;
  min-width: 300px;
  background-color: white;
  height: 100%;
}
</style>