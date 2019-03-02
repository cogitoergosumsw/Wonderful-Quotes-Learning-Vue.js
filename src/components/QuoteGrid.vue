<template lang="html">
  <div class="row">
    <app-quote v-for="quote in quotes">{{ quote }}</app-quote>
  </div>
</template>

<script>
export default {
  import Quote from './Quote.vue';
  props: ["quotes"],
  components: {
    appQuote: Quote
  }
};
</script>

<style lang="css" scoped></style>
