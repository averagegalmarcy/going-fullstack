<template>
  <div class="app">
    <header>
      <nav>
        <RouterLink to="/"> Home </RouterLink>
        <RouterLink to="/dogs"> Dogs </RouterLink>
        <RouterLink to="/dogSize"> Dog Size </RouterLink>
      </nav>
    </header>

    <main> 
      <RouterView></RouterView>
    </main>
  </div>
</template>

<script>
export default {

};
</script>

<style scoped>
header {
  height: 75px;
  background: lightgray; 
  display: flex;
  align-items: center;
  justify-content: center;
}
header img {
  height: 100%;
}
nav a {
  text-decoration: none;
  color: black;
  margin: 3px;
  padding: 3px;
  border: 1px solid black;
  position: relative;
}
nav a:hover {
  color:white;
  background:lightblue;
   -webkit-text-stroke: 1px black;
}
main {
  padding: 8px;
}
</style>
