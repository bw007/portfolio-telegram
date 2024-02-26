<template>
  <main class="wrapper">
    <chat-list />
  </main>
</template>

<script>
import chatList from '@/components/chat-list.vue'

export default {
  components: {
    chatList
  },
  data() {
    return {
      
    }
  },
}

</script>

<style lang="css">
  .wrapper {
    background-color: #a0cfff;
    height: 100vh;
    overflow-y: hidden;
  }
</style>