<template>
  <img :src="avatar" :alt="descriçao" />
</template>
<script>
export default {
  name: 'picture',
  data() {
    return {
      avatar: '/img/avatar.png',
      descriçao: 'faça seu pedido'
    }
  }
}
</script>
