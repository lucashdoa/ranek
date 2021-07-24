<template>
  <header>
    <nav>
      <img class="logo" src="@/assets/ranek.svg" alt="" />
      <button
        onclick="alert('Sinto muito, eu ainda não faço nada!')"
        class="btn"
      >
        Vender / Login
      </button>
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
  justify-content: space-between;
  box-shadow: 0 2px 4px rgba(30, 60, 90, 0.1);
}
.logo {
  width: 90px;
}
</style>
