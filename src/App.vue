<template>
  <h1>Olá mundo</h1>
  <div>
    <PrimeiroComponente />
    <p>O estatus é: {{ status }}</p>
    <LifeCycle />
    <Pessoa />
  </div>
</template>

<script>
import PrimeiroComponente from './components/PrimeiroComponente.vue'
import LifeCycle from './components/LifeCycle.vue'
import Pessoa from './components/Pessoa.vue'
export default {
  name: 'App',
  components: {
    PrimeiroComponente,
    LifeCycle,
    Pessoa
  },
  data() {
    return {
      status: 'trabalhando'
    }
  }
}
</script>
