<template>
  <button type="button" :class="buttonType">
    <a target="_blank" :href="linkTo">
      {{ text }}
    </a>
  </button>
</template>

<script>
export default {
  props: {
    text: {
      type: String,
      default: "Minutentag Button",
    },
    buttonType: {
      type: String,
      default: "btn btn-primary",
    },
    linkTo: {
      type: String,
      default: "/",
    },
  },
};
</script>

<style scoped>
a {
  color: inherit;
  text-decoration: none;
}
</style>
