<template>
  <div class="menu-bar">
    <ul>
      <li><a class="menu-bar-link active" href="/">Portfolio</a></li>
      <li><a class="menu-bar-link" href="/">About</a></li>
      <li><a class="menu-bar-link" href="/">Contact</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Menu",
};
</script>

<style scoped>    
  .menu-bar li {
    display: inline;
    transition: opacity .2s;
  }

  .menu-bar ul li a {
    color: #fff;
    text-decoration: none;
    position: relative;
  }

  .menu-bar-link {
    transition: opacity .2s;
    margin: 0 14px;
  }

  .menu-bar-link.active:after {
    content: "";
    height: 5px;
    width: 5px;
    border-radius: 50%;
    display: inline-block;
    background-color: white;
    position: absolute;
    left: calc(50% - 2.5px);
    bottom: -10px;
  }
  
  .menu-bar-link:hover {
    opacity: .6;
  }
</style>