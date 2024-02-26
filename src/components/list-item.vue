<template>
  <div class="list-item">
    <img class="avatar" src="@/assets/img/Avatar.svg">
    <div class="inner">
      <h3 class="user">Greg James</h3>
      <p class="msg">I got a job at SpaceX</p>
    </div>
    <div class="notif">
      <span class="date">19:48</span>
      <span class="new-msg">2</span>
    </div>
  </div>
</template>
<script>
export default {
  
}
</script>
<style lang="css" scoped>
  .list-item {
    padding: 12px 16px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 16px;
    cursor: pointer;
    transition: background-color 0.3s linear;
  }
  .list-item:hover {
    background-color: #f8f8f8;
  }
  .inner {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 4px;
    margin-right: auto;
  }
  .inner .user {
    font-size: 16px;
    line-height: 20px;
    color: #011627;
  }
  .inner .msg {
    font-size: 14px;
    line-height: 18px;
    color: #707991;
  }
  .notif {
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    gap: 8px;
  }
  .notif .date {
    font-size: 12px;
    line-height: 16px;
    color: #707991;
  }
  .notif .new-msg {
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 12px;
    line-height: 16px;
    background-color: #78E378;
    color: #FFF;
    width: 18px;
    height: 18px;
    border-radius: 10px;
  }
</style>