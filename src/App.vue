<template>
  <div id="app">
    <nav class="navbar navbar-light bg-light">
      <a class="navbar-brand" href="#">
        <img src="./assets/logo.png" width="30" height="30" class="d-inline-block align-top" alt="">
        三国趣闻
      </a>
      <ul id="nav" class="nav justify-content-center">
        <li class="nav-item">
          <router-link class="nav-link" to="/">首页</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/about">关于</router-link>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">友链</a>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">描述</a>
        </li>
      </ul>
    </nav>
    <router-view/>
  </div>
</template>

<style>
  #nav a {
    color: #504b4d;
  }

  #nav a.router-link-exact-active {
    color: #42b983;
  }
</style>
