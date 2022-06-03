<script setup>
import HeaderComp from "@/components/template/HeaderComp.vue";
</script>
<template>
<HeaderComp/>
 <RouterView />
 <footer>Rodapé</footer>
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: calc(100-1.5rem);
  margin: 0 auto;
  font-weight: normal;
  height: 100vh;
}
a{
  color: inherit;
  text-decoration: none;
}

header,
footer {
  background-color: rgb(45, 70, 117);
  height: 15%;
  font-size: 1.3rem;
  color: white;
  display: flex;
  align-items: center;
  padding-left: 1.5rem;
  justify-content: space-between;
}

main {
  min-height: 70%;
}

header span {
  padding: 0 10px;
}
</style>
