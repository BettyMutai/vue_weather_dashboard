<template>
  <div>
    <p>This child components of COntent.vue are:</p>
    <ul>
      <li v-for="child in childComponents">{{ child }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      childComponents: ['TempVarChart.vue', 'Highlights.vue']
    }
  },
  methods: {

  },
  computed: {

  },
}
</script>

<style scoped>

</style>
