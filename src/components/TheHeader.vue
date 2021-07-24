<template>
  <header>
    <nav>
      <router-link to="/" class="logo">
        <img src="@/assets/ranek.svg" alt="" />
      </router-link>
      <router-link
        onclick="alert('Sinto muito, eu ainda não faço nada!')"
        class="btn"
        to="/"
      >
        Vender / Login
      </router-link>
    </nav>
  </header>
</template>

<script>
export default {
  name: "TheHeader",
};
</script>

<style scoped>
nav {
  padding: 15px 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  box-shadow: 0 2px 4px rgba(30, 60, 90, 0.1);
}
.logo img {
  width: 90px;
}

.logo {
  padding: 10px 0;
}
</style>
