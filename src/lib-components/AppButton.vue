<template>
  <button class="btn" type="button">{{ text }}</button>
</template>

<script>
export default {
  name: "AppButton",
  props: {
    text: {
      type: String,
      default: "Default Button Text"
    }
  }
};
</script>

<style>
.btn {
  background-color: #fff;
  color: #000;
  display: block;
  padding: 6px 12px;
  font-size: 18px;
  cursor: pointer;
}

.btn:active:hover,
.btn:focus,
.btn:hover {
  background-color: #000;
  color: #fff;
}
</style>
