<template>
  <option :value="value" class="sf-select__option" tabindex="0">
    <!-- @slot Slot to replace select options -->
    <slot />
  </option>
</template>
<script>
export default {
  name: "SfSelectOption",
  props: {
    value: {
      type: [String, Number, Object],
      default: "",
    },
  },
};
</script>
