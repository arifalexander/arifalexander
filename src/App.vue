<template>
  <nav class="navbar fixed-top navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">Arif Alexander</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav ms-auto">
          <b><a class="nav-link active" aria-current="page" href="/">Home</a></b>
          <b><a class="nav-link active" href="/about">About</a></b>
          <b><a class="nav-link active" href="/experience">Experience</a></b>
          <b><a class="nav-link active" href="/gear">Gear</a></b>
          <b><a class="nav-link active" href="/contact">Contact</a></b>
        </div>
      </div>
    </div>
  </nav>

  <footer class="text-center bg-body-tertiary fixed-bottom mt-4">
    <!-- Copyright -->
    <div class="text-center p-2" style="background-color: rgba(0, 0, 0, 0.05);">
      <h6>KafeinArts Interactive Copyright - 2024 </h6>
    </div>
    <!-- Copyright -->
  </footer>

  <router-view />
</template>
