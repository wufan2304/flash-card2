<template>
  <div class="container">
    <h1>{{msg}}</h1>
    <input type="text" id="account">
    <input type="text" id="password">
    <button>login</button>
      
  </div>
</template>

<script>
export default {
  name: 'login',
  data () {
    return {
      msg: 'this is login'
    }
  }
}
</script>
