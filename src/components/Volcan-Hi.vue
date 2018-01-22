<template>
    <div class="hi">
        <h1>{{msg}}</h1>
    </div>
</template>

<script>
export default {
  name: 'Volcan-H1',
  data () {
    return {
      msg: 'Volcan vous dit bonjour!'
    }
  }
}
</script>

<style scoped>
h1 {
  color: #ef7d0b;
}

</style>
