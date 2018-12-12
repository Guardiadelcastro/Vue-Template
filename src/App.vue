<template>
  <div class="full-width center-content">
    <HelloComponent
      name="Webpack"
      surname="World"
    />
  </div>
</template>

<script>
import HelloComponent from './components/HelloComponent.vue';

export default {
  components: {
    HelloComponent
  }
};
</script>

<style lang="stylus" scoped>
	.full-width
		width 100%

	.center-content
		display flex
		justify-content center
		align-items center
</style>
