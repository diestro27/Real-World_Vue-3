<template>
  <p>Extra! Extra! Read all about it!</p>
  <ExtraCard :story="story" />
</template>

<script>
  import ExtraCard from '@/components/ExtraCard.vue'

  export default {
    name: 'Extra',
    components: {
      ExtraCard
    },
    data() {
      return {
        story: {
          title: "Solar Panel Sizing Tool 4.4 Released",
          text: `A bug was fixed and partial support for 
            the 60K was added (two simple strings, no Y configurations)`,
        }
      }
    }
  }
</script>
// todo