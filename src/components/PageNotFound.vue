<template>
  <div class="col-full text-center">
    <h1>{{ heading }}</h1>
    <router-link :to="{ name: 'Home' }">Read some cool threads instead</router-link>
  </div>
</template>

<script>
export default {
  props: {
    heading: {
      type: String,
      default: 'Page Not Found'
    }
  }
}
</script>

<style></style>
