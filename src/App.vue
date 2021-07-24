<template>
  <TheHeader />
  <main>
    <router-view></router-view>
  </main>
  <TheFooter />
</template>

<script>
import TheHeader from "@/components/TheHeader.vue";
import TheFooter from "@/components/TheFooter.vue";
export default {
  components: {
    TheHeader,
    TheFooter,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

p,
h1,
h2,
ul,
li,
body {
  margin: 0;
  padding: 0;
}

body {
  background: url("./assets/pattern.svg") no-repeat top;
}

ul {
  list-style: none;
}

a {
  text-decoration: none;
}

.btn {
  display: block;
  padding: 10px 30px;
  color: #fff;
  font-size: 1rem;
  padding: 10px 30px;
  background: #87f;
  border-radius: 4px;
  border: none;
  cursor: pointer;
  transition: all 0.2s ease-in-out;
  text-align: center;
}

.btn:hover {
  background: #65d;
  transform: scale(1.1);
}

#app {
  display: flex;
  min-height: 100vh;
  flex-direction: column;
}

main {
  flex: 1;
}
</style>
