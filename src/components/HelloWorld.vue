<script>
export default {
  data() {
    return {
      msg: "Sono il componente figlio!"
    }
  }
}
</script>

<template>
  HelloWorld dice: {{ msg }}
</template>