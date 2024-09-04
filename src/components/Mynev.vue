<template lang="">
    <div>
        <ul>
        <li><img src="https://www.16personalities.com/static/images/system/logo.svg"></li>
        <li><a href="#news">News</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="#about">About</a></li>
        </ul>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
img{
  width: 250px;
  margin-top: 1rem;
  margin-left: 10px;
}
  ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #55b155;
  font-size: 22px;
  border-radius: 1rem;
  height: 80px;
}
li {
  margin: auto;
  float: left;
}

li a {
  margin-top: 1rem;
  margin-left: 10px;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #a2d8a2;
}
</style>