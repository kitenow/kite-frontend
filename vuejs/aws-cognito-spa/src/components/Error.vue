<template>
  <div class="alert alert-danger">
    {{ message }}
  </div>
</template>

<script>

alert("Error.vue")

export default {
  data: function () {
    return {
      message: "",
    };
  },
  mounted() {
    this.message = this.$route.query.message;
  },
};
</script>