<template>
  <div class="phone">
    <a href="tel: 89686413187"> {{ phone_num }}</a>
  </div>
</template>

<script>
export default {
  props: {
    phone_num: {
      type: String,
      required: true
    }
  }
}
</script>