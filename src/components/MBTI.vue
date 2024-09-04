<template lang="">
    <div class="content">
        <img :src="img" alt="photo" style="width:100%">
        <div class="container">
          <h1><b>{{ mbtitype }}</b></h1>
          <h2><b><p>{{ name }}</p></b></h2>
          <h4><p>{{ nature }}</p></h4>
          <h2>อาชีพที่เหมาะ</h2><b><p>{{ career }}</p></b>
        </div>
    </div>
</template>
<script>
export default {
    props: ['mbtitype','name','nature','career','img']
}
</script>
<style scoped>
.content{
    color: white;
    padding: 3rem;
    display: table;
    display: table-cell;
    margin: auto;
}
img{
    padding-top: 2rem;
    padding-bottom: 3rem;
    cursor: pointer;
}
.container{
    padding: 5px;
    text-indent: 15px;
    background-color: #4f8f4f;
    border-radius: 2rem;
    width: 390px;
    height: 470px;
}
</style>