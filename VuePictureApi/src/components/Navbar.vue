<script setup>
</script>
<template>
<nav class="navbar navbar-expand-lg bg-dark navbar-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">
          <img alt="logo yoga" class="logo" src="@/assets/avatar.png" width="30" />
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        
        <li class="nav-item">
          <RouterLink class="nav-link" href="#" to="/">Home</RouterLink>
        </li>
        <li class="nav-item">
          <RouterLink class="nav-link" href="#" to="/admin">Admin</RouterLink>
        </li>
          <li class="nav-item">
          <RouterLink class="nav-link" href="#" to="/create">Create</RouterLink>
        </li>
           <li class="nav-item">
          <RouterLink class="nav-link" href="#" to="/update">Show gallery</RouterLink>
        </li>
         <li class="nav-item">
          <RouterLink class="nav-link" href="#" to="/update">Update gallery</RouterLink>
        </li>
         <li class="nav-item">
          <RouterLink class="nav-link" href="#" to="/delete">Delete gallery</RouterLink>
        </li>
       
      </ul>
    </div>
  </div>
</nav>
</template>
<style></style>