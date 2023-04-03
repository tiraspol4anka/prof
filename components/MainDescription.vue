<template>
  <div class="columns">
    <div class="column title_item">
      <img :src="imageUrl" />
      {{ title }}
      <div class="column text">
      {{ description }}
      </div>
    </div>
  </div>
</template>


<script>
export default {
  props: {
    imageUrl: {
      type: String,
      required: true,
    },
    title: {
      type: String,
      required: true,
    },
    description: {
      type: String,
      required: true,
    },
  },
};
</script>

<style scoped>
.title_item {
  font-size: 26px;
  padding-top: 20px;
  padding-left: 54px;
}

.text {
  font-size: 20px;
}
</style>