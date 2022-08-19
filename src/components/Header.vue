<template>
    <div id="headerWrap" style="margin-top: 0px;">
      <header id="header">
        <a href="#">link</a>
      </header>
    </div>
</template>

<script>
export default {
  name: "siteHeader",
}
</script>

<!-- "scoped" attribute to limit CSS to this component only -->
<style scoped>

#headerWrap {
  background-image: none;
  background-color: rgb(44, 48, 50);
  border-bottom-color: rgba(140, 130, 115, 0.1);
  width: 100%;
  min-height: 55px;
  z-index: 999;
  top: 0;
  left: 0;
  transition: all .3s ease-in-out;
  box-sizing: border-box;
  position: fixed;
}

a {
  color: red
}
</style>
