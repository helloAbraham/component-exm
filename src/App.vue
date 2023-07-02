<template>
  <div>
    <InputFile v-model="name" />
  </div>
</template>

<script>
import InputFile from './components/InputFile';
export default {
  name: 'App',
  
  components: {
    InputFile
  },
  data(){
   return {
       name: '',
    }
  },
  methods:{ }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
