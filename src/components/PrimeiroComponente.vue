<template>
  <h1>Olá vue!</h1>
  <p>Meu nome é: {{ nome }}</p>
  e trabalho como {{ profissão }}
  <div>
    <h2>Esta é a descrição da pessoa: {{}}</h2>
  </div>
</template>

<script>
export default {
  name: 'PrimeiroComponente',
  data() {
    return {
      nome: 'joão',
      profissão: 'programador'
    }
  }
}
</script>
