<template>
  <div class='header-main-container'>
    <div class="header container">
      <Logo class="header__logo"/>
      <Menu/>
      <HeaderIcon/>
    </div>
  </div>
</template>

<script>
  import Logo from './Logo.vue'
  import HeaderIcon from './HeaderIcon.vue'
  import Menu from './Menu.vue'

  export default {
    name: 'Header',
    components: {
      Logo,
      HeaderIcon,
      Menu,
    }
  }
</script>

<style scoped>
  .header-main-container {
    width: 1349px;
    height: 150px;
    position: absolute;
    z-index: 30;
    background-color: transparent;
    padding-top: 24px;
  }
  .header {
    display: flex;
    justify-content: space-between;
    height: 116px;
    align-items: center;
    
  }
</style>