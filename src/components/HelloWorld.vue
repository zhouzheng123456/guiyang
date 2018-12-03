<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2 @click="admin">机构人员</h2>
    <h2 @click="everyman">残疾人员</h2>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to guiyang App'
    }
  },
  methods: {
    admin: function () {
      console.log('admin')
    },
    everyman: function () {
      console.log('everyman')
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
