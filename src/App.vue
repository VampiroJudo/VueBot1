<template>
  <div id="app">
    <header>
      <nav>
        <ul>
          <li class="nav-item">
            <!-- <img class="logo" src="./assets/build-a-bot-logo.png"/> -->
            Build-a-Bot
          </li>
        </ul>
      </nav>
    </header>
      <main>
        <RobotBuilder />
      </main>
  </div>
</template>

<script>
// import HomePage from './home/HomePage.vue';
import RobotBuilder from './build/RobotBuilder.vue';

export default {
  name: 'app',
  components: {
    // HomePage,
    RobotBuilder,
  },
};
</script>

<style>
body {
  background: linear-gradient(to bottom, #555, #999);
  background-attachment: fixed;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
}

li {
  margin: 0 auto;
  padding: 30px;
  background-color: white;
  width:1024px;
  min-height: 300px;
}

</style>
