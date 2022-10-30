<template>
  <div class="hello">
    <img src="../assets/flyapi.gif" class="img-fluid" style="pointer-events: none; -moz-user-select: none; -webkit-user-select: none; -ms-user-select: none; user-select: none;" alt="Api bee" />
    
    <h1>Добро пожаловать!</h1>
    <p>
      В настоящее время сайт находится в разработке, 
      но уже очень скоро будет открыт для всех! :)
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
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
