<template>
  <v-textarea
    hide-details
    filled
    readonly
    dense
    row-height="6"
    rows="1"
    auto-grow
    :label="label"
    :value="value"
  ></v-textarea>
</template>

<script>
export default {
  name: 'CustomTextArea',
  props: {
    label: {default: '',type: String},
    value: {default: '',type: String},
  },
}
</script>