<template>
  <div id="app">
    <input v-model="message" placeholder="入力してください：">
    <p>入力したメッセージ：{{ message }}</p>
  </div>
</template>

<script>
export default({
  el:'#app',
  data(){
    return {
    message :''
    };   
  }
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
}
</style>