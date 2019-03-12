<template>
  <div class="lead">
    Lead: {{title}} {{date}}<hr/>
    Details | Comments | Vetters
  </div>
</template>

<script>
export default {
  name: 'Lead',
  props: {
    title: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.lead{
  font-weight: bold;
}
</style>
