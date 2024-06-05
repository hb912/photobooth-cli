<template>
  <header>
    <div class="header">
      <div class="logo">
        Photo Booth
      </div>
      <div class="icon">
        <i class="fa fa-bell"/>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'MainHeader'
}
</script>

<style lang="scss" scoped>
@import "@/style/fonts.scss";

.header {
  display: flex;
  align-items: center;
  height: 20px;
  background-color: $main-color;
  color: white;
  padding: 13px 20px;
  justify-content: space-between;

}

.logo {
  font-size: 1.5rem;
  //font-weight: bold;
  font-family: 'Kaushan Script', sans-serif;
}

.icon {
  font-size: 1.3rem;
}

</style>
