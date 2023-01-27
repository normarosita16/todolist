<template>
    <button
      class="px-8 py-3 rounded-3xl text-white text-lg font-medium add-button"
      @click="clickEvent"
    >
    Add New Activity Card
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
  
  .add-button-activity {
    background: #16abf8;
  }
  </style>
  