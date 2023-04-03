<template>
  <div class="columns text">
    <div class="column double_text_item">
      {{ text_item_first }}
    </div>
    <div class="column double_text_item">
      {{ text_item_second }}
    </div>
  </div>
</template>

<script>
export default {
  props: {
    text_item_first: {
      type: String,
      required: true,
    },
    text_item_second: {
      type: String,
      required: true,
    },
  },
};
</script>

<style scoped>
.text {
  font-size: 20px;
  padding-left: 54px;
  padding-right: 10px;
}

.double_text_item::before {
  content: "";
  display: inline-block;
  vertical-align: middle;
  background-color: #cf1f00;
  width: 5%;
  height: 4px;
  position: relative;
  top: -1px;
}
</style>>

