<template>
  <TheHeader />
  <main></main>
  <footer></footer>
</template>

<script>
import TheHeader from "@/components/TheHeader.vue";
export default {
  components: {
    TheHeader,
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
  background: url("./assets/pattern.svg") no-repeat top;
}

ul {
  list-style: none;
}

.btn {
  color: #fff;
  font-size: 1rem;
  padding: 10px 30px;
  background: #87f;
  border-radius: 4px;
  border: none;
  cursor: pointer;
  transition: all 0.2s ease-in-out;
}

.btn:hover {
  background: #65d;
  transform: scale(1.1);
}
</style>
