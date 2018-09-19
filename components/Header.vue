<template>
  <header>
    <div>
      Logo
    </div>
    <nav>
      <ul>
        <li><div><a href="#">Home</a></div></li>
        <li><div><a href="#"> Web</a></div></li>
        <li><div><a href="#">Blog</a></div></li>
        <li><div><a href="#">Contact</a></div></li>
      </ul>
    </nav>
  </header>
</template>
<script>
import AppLogo from '@/components/AppLogo.vue';

export default {
  components: {
    AppLogo
  }
}
</script>
<style lang="scss" scoped>
header {
  height: 60px;
  background: #000;
  color: #ffffff;
  display: flex;
  justify-content: space-between;
}
nav {
  height: 60px;
  width: 100%;
}
nav ul {
  display: flex;
  flex-direction: row;
  list-style: none;
  justify-content: space-between;
}
li a{
  color: #ffffff;
}
</style>
