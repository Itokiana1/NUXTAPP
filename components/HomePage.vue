<template>
  <header>
    <div class="head-logo">
      <img src="../static/Component 1(2).png" alt="logo">
    </div>
    <div class="head-nav">
      <nav class="link">
        <a href="">Homepage</a>
        <a href="">About us</a>
        <a href="">Traveling</a>
        <a href="">Hotels</a>
      </nav>
      <button>Reserve</button>
    </div>
  </header>
</template>
  
<script>
export default {
  name: 'HomePage',
}
</script>

<style>
* {
  margin: 1px;
}
header {
  display: flex;
  justify-content: space-between;
}
button {
  width: 130px;
  height: auto;
  background: #33BB93;
  padding: 15px;
  border-radius: 6px;
  color: #FFFFFF;
}
.head-nav {
  display: flex;
  justify-content: space-between;
  gap: 60px;
}
.link {
  display: flex;
  gap: 60px;
  margin: auto;
}
</style>

  