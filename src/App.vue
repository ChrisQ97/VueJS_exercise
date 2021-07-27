<template>

  <div id="app">
    <header>
      <span>Christian Antonio Quijivix Presancin.</span>
    </header>
    <main>

      <firstimage></firstimage>
      <firsttema></firsttema>
      <secondtema></secondtema>
      <tercertema></tercertema>
    </main>
  </div>
</template>

<script>
import Hello from './components/Hello'
import Tarjet from  './components/Tarjet'
import Firstimage from './components/Firstimage'
import Second from './components/Second'
import Footern from './components/Footern'
import Firsttema from './components/Firsttema'
import Secondtema from './components/Secondtema'
import Tercertema from './components/Tercertema'


export default {
  name: 'app',
  components: {
    Hello,
    Tarjet,
    Firstimage,
    Second,
    Footern,
    Firsttema,
    Secondtema,
    Tercertema

  }
}
</script>

<style>
body {
  margin: 0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

main {
  text-align: center;
  margin-top: 10px;
}

header {
  margin: 0;
  height: 56px;
  padding: 0 16px 0 24px;
  background-color: #35495E;
  color: #ffffff;
}

header span {
  display: block;
  position: relative;
  font-size: 20px;
  line-height: 1;
  letter-spacing: .02em;
  font-weight: 400;
  box-sizing: border-box;
  padding-top: 16px;
}
</style>
