<template>
    <div class="hello">
    <p>
      Welkom op de website, Maak gebruik van onze chatbot
    </p>
    <h3>Chatbot</h3>
    <ul>
     <button>Open Chatbot</button>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'ChatBot',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
