<template>
  <header class="header">
    <span class="menu-icon">
      <img src="@/assets/img/Bar3.svg">
    </span>
    <div class="search">
      <img src="@/assets/img/search.svg">
      <input type="text" placeholder="Search" />
    </div>
  </header>
</template>
<script>
export default {

}
</script>
<style lang="css" scoped>
.header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 12px;
  padding: 12px 16px;
}
.menu-icon {
  display: block;
  width: 40px;
  height: 40px;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  border-radius: 4px;
}
.menu-icon:hover {
  background-color: #f8f8f8;
}

.search {
  padding: 8px 16px;
  display: flex;
  align-items: center;
  background-color: #f8f8f8;
  border-radius: 22px;
}
.search img {
  width: 16px;
  height: 16px;
  margin-right: 10px;
}
.search input {
  border: none;
  outline: none;
  font-size: 16px;
  line-height: 20px;
  background-color: transparent;
  color: #707991;
}
</style>