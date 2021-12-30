<template>
  <section class="container">
    <Counter></Counter>
    <hr>
    <Counter></Counter>
    <hr>
    <Counter></Counter>
  </section>
</template>


<script>
import Counter from '~/components/Counter.vue'

export default {
  components: {
    Counter
  }
}
</script>
