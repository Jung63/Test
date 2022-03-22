<template>
  <h2>登入頁面</h2>
  <button type="button" class="btn btn-primary" @click="login">登入</button>
</template>

<script>
export default {
  methods: {
    login () {
      this.$router.push('/admin')
    }
  }
}
</script>
