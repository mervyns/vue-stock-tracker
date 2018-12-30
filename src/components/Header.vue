<template>
  <b-navbar toggleable="md" type="dark" variant="info">

  <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

  <b-navbar-brand to="/">Stock Trader</b-navbar-brand>

  <b-collapse is-nav id="nav_collapse">

    <b-navbar-nav>
      <b-nav-item to="/portfolio">Portfolio</b-nav-item>
      <b-nav-item to="/stocks">Stocks</b-nav-item>
    </b-navbar-nav>

    <!-- Right aligned nav items -->
    <b-navbar-nav class="ml-auto">

      <ul class="navbar-nav navbar-right">
        <li>
          <a to="#">End Day</a>
        </li>
      </ul>

</b-navbar-nav>
        </b-collapse>
</b-navbar>
</template>
