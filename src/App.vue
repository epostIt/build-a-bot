<template>
  <div id="app">
    <header>
      <nav>
        <ul>
          <li class="nav-item">
            <img class="logo" src="./assets/build-a-bot-logo.png">
            Build-a-bot
          </li>
        </ul>
      </nav>
    </header>
    <main>
      <HomePage />
      <RobotBuilder />
    </main>
  </div>
</template>

<script>
import HomePage from './components/HomePage.vue';
import RobotBuilder from './components/RobotBuilder.vue';

export default {
  name: 'App',
  components: {
    HomePage,
    RobotBuilder,
  },
};
</script>

<style>
header {
  background-color: #999;
  width: 1084px;
  margin: 0 auto;
}

ul {
  padding: 3px;
  display: flex;
}
.nav-item {
  display: inline-block;
  padding: 5px 10px;
  font-size: 22px;
  border-right: 1px solid #bbb;
}
.logo {
  vertical-align: middle;
  height: 30px;
}
</style>
