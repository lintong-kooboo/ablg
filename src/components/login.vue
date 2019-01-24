<template>
  <div name='login' class="login-form">
    <form>
      <div class="login-username">
        <input type="text" placeholder="用户名">
      </div>
      <div class="login-password">
        <input type="password" placeholder="密码">
      </div>
      <button class="login-button" v-on:click="goPosts()" type="submit">登录</button>
      <span class="to-register" v-on:click="goRegister()">没有账号？去注册</span>
    </form>
  </div>
</template>

<script>
import '../assets/scss/_login.scss'
export default {
  name: 'b-login',
  methods: {
    goRegister () {
      this.$router.push({
        path: '/register'
      })
    }
  }
}
</script>
