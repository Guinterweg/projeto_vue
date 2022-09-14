<template>
  <h2>Meu formulário</h2>
  <form action="">
    <div>
      <input type="text" v-model="name" />
    </div>
    <div>
      <input type="text" v-model="name" />
    </div>

    <input type="Submit" value=" Enviar" />
  </form>
</template>
<script>
export default {
  name: 'Form'
}
</script>
