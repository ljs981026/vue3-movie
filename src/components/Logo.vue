<template>
  <RouterLink 
    to="/"
    class="logo"> 
    <span>방구석</span> 시네마
  </RouterLink>
</template>

<style lang="scss" scoped>
@import "~/scss/main";

.logo {
  font-family: 'Black Han Sans', sans-serif;
  font-size: 30px;
  color: $black;
  text-decoration: none;
  &:hover {
    color: $black;
  }
  span {
    color: $primary;
  }
}
</style>