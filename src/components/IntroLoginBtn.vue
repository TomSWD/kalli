<template>
  <a class="login" href="#">Login</a>
</template>

<script>
export default {
  name: "IntroLoginBtn",
};
</script>

<style scoped>
  .login {
    text-transform: uppercase;
    font-size: 12px;
    font-weight: 500;
    letter-spacing: 1px;
    text-decoration: none;
    color: #222;
    border: 2px solid #aaa;
    padding: 14px 18px;
    line-height: 14.4px;
    margin-right: 30px;
  }

  .login:hover {
    background-color: #aaa;
    transition: 0.2s;
  }
</style>