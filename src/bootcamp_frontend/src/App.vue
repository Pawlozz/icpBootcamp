<template lang="html">
  <div>
    <img src="/logo2.svg" alt="DFINITY logo" />
    <h2>Cześć!</h2>
    <button @click="increase">Zwiększ licznik</button>
    <p>Licznik: {{ licznik }}</p>
  </div>
</template>
<script>
export default {
  data(){
    return{
      licznik: 0
    }
  },
  methods: {
    increase(){
      this.licznik++
    }
  }
}
</script>
<style lang="css">
  h2{
    color: #5d2684;
  }
  button{
    border-radius: .4rem;
    border: 2px solid #5d2684;
    background: none;
    padding: 1rem 2em;
  }
</style>
