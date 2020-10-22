<template>
  <div>
    <b-navbar class = "my-nav" toggleable="lg" :sticky="true">
      <b-navbar-brand href="#" class = "my-navbar-brand" to = "/Home">QuiltWorld</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item-dropdown class="my-nav-item" text="Locations" right>
            <b-dropdown-item href="#" to = "/Ada">ADA</b-dropdown-item>
            <b-dropdown-item href="#" to = "/Duncan">DUNCAN</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-nav-item class="my-nav-item" to = "/Products" href="#">Products</b-nav-item>

          <b-nav-item class="my-nav-item" to = "/FAQ" href="#">FAQ</b-nav-item>

          <b-nav-item  class="my-nav-item" to = "/Safety" href="#">Safety</b-nav-item>

          <b-nav-item  class="my-nav-item" to = "/Links" href="#">Links</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <br>
  </div>
</template>
