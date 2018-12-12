<template>
  <h1>Hello {{ fullName }}!</h1>
</template>

<script>
export default {
  props: {
    name: {
      type: String,
      required: true
    },
    surname: {
      type: String,
      required: true
    }
  },
  computed: {
    fullName() {
      return `${this.name} ${this.surname}`;
    }
  }
};
</script>

<style lang="stylus" scoped>
	h1
		color orange
</style>
