<template>
  <div id="app" class="container">
    <nav class="navbar navbar-expand-lg">
      <router-link to="/">
        <a href="/" class="navbar-brand">Jake's ToDo App</a>
      </router-link>
      <!-- hamburger collapse -->
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#nav-links" aria-controls="nav-links" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <!-- Nav Links -->
      <div class="collapse navbar-collapse">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link to="/about">
              <a href="" class="nav-link">About</a>
            </router-link>
            
          </li>
          <li class="nav-item">
            <router-link to="/contact">
              <a href="" class="nav-link">Contact</a>
            </router-link>
            
          </li>
        </ul>
      </div>
    </nav>
    <router-view/>
  </div>
</template>

<style>
  body {
    background-color: #cdffeb;
    color: #009f9d;
  }

  ul {
    margin-left: auto;
  }

  .navbar-brand {
    font-family: "Ubuntu";
  }

  .nav-link {
    font-family: "Montserrat";
    font-weight: 100;
    margin-left: 40px;
  }

  .navbar {
    padding-top: 20px;
  }
</style>
