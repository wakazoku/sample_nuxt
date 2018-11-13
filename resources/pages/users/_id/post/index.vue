<template>
  <div>
    <p>
      /users/_id/post/index.vue<br>
      User ID: {{ userId }}
    </p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      userId: this.$route.params.id
    }
  }
}
</script>
