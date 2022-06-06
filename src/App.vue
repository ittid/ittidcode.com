<template lang="pug">
  main(id="app" class="container grid-wrap")
    Header
    router-view
    Footer
</template>

<script>
import Footer from "@/components/global/Footer";
import Header from "@/components/global/Header";

export default {
  name: "APP",
  components: {
    Header,
    Footer,
  },
};
</script>
<style scoped lang="scss">
.grid-wrap {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  grid-row-gap: 1em;
}
</style>
