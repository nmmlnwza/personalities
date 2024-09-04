<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
import Mynev from './components/Mynev.vue'
import MBTI from './components/MBTI.vue'
import items from './mbti.json'
</script>

<template>
  <header>
    <Mynev/>
    <h1>12Personalities</h1>
  </header>

  <main>
    <div className="grid-container">
          <MBTI v-bind="items[0]"/>
          <MBTI v-bind="items[1]"/>
          <MBTI v-bind="items[2]"/>
          <MBTI v-bind="items[3]"/>
          <MBTI v-bind="items[4]"/>
          <MBTI v-bind="items[5]"/>
          <MBTI v-bind="items[6]"/>
          <MBTI v-bind="items[7]"/>
          <MBTI v-bind="items[8]"/>
          <MBTI v-bind="items[9]"/>
          <MBTI v-bind="items[10]"/>
          <MBTI v-bind="items[11]"/>

    </div>
  </main>
</template>

<style scoped>
h1{
  text-indent: 10px;
  text-align: center;
  color: #55b155;
}
.grid-container {
  display: grid;
  grid-column-gap: 0.5rem;
  grid-row-gap: 0.5rem;
}
@media (min-width: 576px) {
  .grid-container { grid-template-columns: repeat(1, 1fr); }
  
}
@media (min-width: 992px) {
  .grid-container { grid-template-columns: repeat(3, 1fr); }
}




/* header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
} */
</style>