<template>
  <a
    :style="{
      padding: '10px',
      ...style,
    }"
    v-bind="$props"
  >
    <slot />
  </a>
</template>

<script>
export default {
  name: "button",

  props: ["style", "props"],
};
</script>
