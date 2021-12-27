<template>
  <div>
    <b-navbar type="dark" variant="dark">
      <b-navbar-nav>
        <nuxt-link class="nav-item nav-link" to="/">Anime-Jung</nuxt-link>
        <nuxt-link class="nav-item nav-link" to="/posts">Posts</nuxt-link>
        <nuxt-link class="nav-item nav-link" to="/users">Users</nuxt-link>
        <nuxt-link class="nav-item nav-link" to="/admin">Admin</nuxt-link>
      </b-navbar-nav>
    </b-navbar>
    <Nuxt />
  </div>
</template>