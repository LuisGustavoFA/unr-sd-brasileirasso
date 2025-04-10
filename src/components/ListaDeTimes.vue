<template>
  <div>
    <h1>Times</h1>
    <BotomTime v-for="time in times" v-key="time" :nomeTime="time"></BotomTime>
  </div>
</template>

<script>
import BotomTime from './BotomTime.vue'
export default {
  name: 'ListaDeTimes',
  components: { BotomTime },
  props: {
    times: Array,
  },
}
</script>

<style></style>
