<template>
  <div>
    <p v-if="esta_trabalhando">Estou trabalhando no momento</p>
    <p v-else>Estou em busca de novas oportunidades!</p>
    <p>utilizo as seguintes tecnologias:</p>
    <ul>
      <li>JavaScript</li>
      <li>Php</li>
      <li>Pyhton</li>
    </ul>

    <p>Mande uma mensagem para {{ email }}</p>
    <p>Para acessar meu portifolio <a v-bind:href="meu_link" target="_blank">basta clicar aqui</a></p>
    <Picture />
  </div>
</template>
<script>
import Picture from './Picture.vue'
export default {
  name: 'Info',
  components: {
    Picture
  },
  data() {
    return {
      esta_trabalhando: false,
      mostrar_email: true,
      email: 'g@email.com',
      meu_link: 'https://google.com'
    }
  }
}
</script>
