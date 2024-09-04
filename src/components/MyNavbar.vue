<script></script>

<template>
<ul>
  <li><a class="active" href="#home">Home</a></li>
  <li><a href="#news">News</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#about">About</a></li>
</ul>
</template>

<style>
* {
    margin: 0;
    padding: 0;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #ffb303;
  box-shadow: 0 8px 10px 0 rgba(0,0,0,0.2);
  display: flex;
  justify-content: center; /* Center the navbar items */
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover:not(.active) {
  background-color: #b90e0a;
}

.active {
  background-color: #a91b0d;
}
</style>