<template>
  <div name='register'>
    <form class="register-form">
      <div class="register-avatar">
        <input type="file">
      </div>
      <div class="register-username">
        <input type="text" placeholder="用户名">
      </div>
      <div class="register-password">
        <input type="password" placeholder="密码">
      </div>
      <div class="register-repassword">
        <input type="password" placeholder="重复密码">
      </div>
      <input class="register-button" type="submit" value="注册">
    </form>
  </div>
</template>

<script>
import '../assets/scss/_register.scss'
export default {
  name: 'b-register',
  props: {
    isregister: {
      type: Boolean,
      default: false
    }
  }
}
</script>
