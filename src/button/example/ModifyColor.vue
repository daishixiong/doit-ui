<template>
  <do-button color="#03A9F4">do-it-ui</do-button>
</template>

<script>
import Button from '../Button'

export default {
  name: 'ModifyColor',
  components: {
    [Button.name]: Button
  }
}
</script>
