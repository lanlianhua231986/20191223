<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    用户名:<input type="text" v-model="user.username"> <br>
    密码:<input type="password" v-model="user.password"> <br>
    <input type="submit">
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '登陆页面',
      user:{
        username:'',
        password:''
      }
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
