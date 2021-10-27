<template>
  <div class="alert alert-info">
    <h2 style="color:red">{{ title }}</h2>
    <p>{{ message }}</p>
    <p class="text-primary">{{ comment }}</p>
  </div>
</template>

<script>
export default {
  name: 'GoodBye',
  props: {
    title: String,
    message: String,
    comment: String,
  }
}
</script>