<template>
  <button
    class="rounded text-white text-lg font-medium add-button"
    @click="clickEvent"
  >
    <span class="icon-plus"></span>
  </button>
</template>

<script>
export default {
  name: "AddButton",
  props: {
    clickEvent: Function,
  },
};
</script>

<style lang="scss">
@import "@/assets/icons/icons";

.add-button {
  background: #16abf8;
}
</style>
