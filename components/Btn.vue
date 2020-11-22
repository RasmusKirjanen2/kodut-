<template>
<button class="button" :class="{
  'is-primary': primary,
  'is-info': info,
  'is-link': link,
  'is-success': success,
  'is-warning': warning,
  'is-danger': danger


}"><slot></slot></button>
</template>

<script>
export default {
name: "Btn",
  props: {
    primary: Boolean,
    info: Boolean,
    link: Boolean,
    success: Boolean,
    warning: Boolean,
    danger: Boolean
  }
}
</script>

<style scoped>

</style>