<template>
  <div>
    <div>{{ htmlString }}</div>
    <h1 v-html="htmlString"></h1>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      htmlString: '<p style="color:red;">Red</p>'
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
