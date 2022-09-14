<template>
  <h1>Meu nome é: {{ nome }}</h1>
</template>

<script>
export default {
  name: 'LifeCycle',
  data() {
    return {
      nome: 'ainda não sei'
    }
  },
  created() {
    setTimeout(() => {
      this.nome = 'Matheus'
    }, 1000)
    this.nome = 'Matheus'
  },
  mounted() {
    setTimeout(() => {
      this.nome = 'Pedro'
    }, 2000)
    this.nome = 'joão'
  }
}
</script>
