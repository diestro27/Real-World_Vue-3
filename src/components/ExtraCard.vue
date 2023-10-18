<template>
  <div class="extra-card">
    <h2>{{ story.title }}</h2>
    <p>{{ story.text }}</p>
  </div>
</template>

<script>
  export default {
    props: {
      story: {
        type: Object,
        required: true
      }
    }
  }
</script>

<style scoped>
  h2 {
    font-size: 18px;
  }
</style>