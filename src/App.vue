<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  components: {
    HelloWorld
  },
  data() {
    return {
      nomeApplicazione: "VitEsempio 0.1"
    }
  },
  methods: {
    //vanno qui, al solito
  },
  mounted() {
    console.log("App montata");
  }
}
</script>

<template>
  <h1>Benvenuto in {{ nomeApplicazione }}!</h1>
  <HelloWorld />
</template>