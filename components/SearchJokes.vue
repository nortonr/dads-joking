<template>
  <form @submit.prevent="onSubmit">
    <input v-model="text" type="text" placeholder="Search Jokes">
    <input type="submit" value="Serach Jokes">
  </form>
</template>

<script>
export default {
  data () {
    return {
      text: ''
    }
  },
  methods: {
    onSubmit () {
      this.$emit('search-text', this.text)
      this.text = ''
    }
  }
}
</script>

<style>

</style>
