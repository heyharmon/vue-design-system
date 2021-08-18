<template>
  <input class="input" type="text" :placeholder="placeholder"/>
</template>

<script>
export default {
  name: "AppInput",
  props: {
    placeholder: {
      type: String,
      default: "Default Input Placeholder"
    }
  }
};
</script>

<style>
.input {
  background-color: #fff;
  color: #000;
  display: block;
  padding: 6px 12px;
  font-size: 18px;
}
</style>
