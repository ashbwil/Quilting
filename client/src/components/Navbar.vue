<template>
  <div>
    <b-navbar class = "my-nav" toggleable="lg" :sticky="true">
      <b-navbar-brand href="#" class = "my-navbar-brand" to = "/Home">QuiltWorld</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <br>
  </div>
</template>

<style>
.mynav{
  color: blue;
}
</style>
