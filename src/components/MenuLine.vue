<template>
  <svg :class="item.id" :width="size" viewBox="0 0 27 27">
    <polygon
      :fill="color"
      :id="item.id"
      :points="item.morph.begin"
      ref="poly"
    ></polygon>
  </svg>
</template>

<script>
export default {
  props: ["item", "color", "size"]
};
</script>

<style></style>
