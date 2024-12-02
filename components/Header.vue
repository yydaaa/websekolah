<!-- <template>
    <div class="navbar navbar-expand-lg ">
      <div class="container">
          SMKN 4 Tasikmalaya
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <NuxtLink to="/" class="nav-link ">Home</NuxtLink>
            </li>
          
            <li class="nav-item">
              <NuxtLink to="/profile" class="nav-link">Profil Skolah</NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink to="/fasilitas" class="nav-link">Ekstrakulikuler</NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink to="/Strukture" class="nav-link">Strukture</NuxtLink>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </template>
  
  <script setup>

  </script>
  
  <style>
  .navbar{
     background-color: rgb(255, 255, 255);
     width: 100%;
     height: 20%;
}
  .navbar-nav .nav-link {
    font-size: 16px;
    padding: 20px 15px;
   ;
  }
  </style>
   -->

   <template>
    <div>
      <!-- Header dengan Logo dan Informasi Sekolah -->
      <div class="row p-3 bg-dark text-white align-items-center">
        <div class="col-lg-1 text-center">
          <img src="" alt="Logo SMKN 4 Tasikmalaya" class="img-fluid rounded">
        </div>
        <div class="col-lg-11">
          <h1 class="mb-0">SMKN 4 Tasikmalaya</h1>
          <address class="mb-0">
            Jl. Depok, Sukamenak, Purbaratu
          </address>
        </div>
      </div>
  
      <!-- Menu Navigasi -->
      <div class="row p-3 bg-secondary text-white">
        <div class="col">

        </div>
        <div class="col-auto">
          <ul class="d-flex list-unstyled mb-0 ms-auto">
            <li class="me-3">
              <NuxtLink to="/" class="nav-link text-white">Home</NuxtLink>
            </li>
            <li class="me-3">
              <NuxtLink to="/profile" class="nav-link text-white">Profil Sekolah</NuxtLink>
            </li>
            <li class="me-3">
              <NuxtLink to="/fasilitas" class="nav-link text-white">Ekstrakurikuler</NuxtLink>
            </li>
            <li class="me-3">
              <NuxtLink to="/Strukture" class="nav-link text-white">Strukture</NuxtLink>
            </li>
            <!-- <li class="me-3">
              
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown" aria-expanded="false">
                  Action
                </button>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Action</a></li>
                  <li><a class="dropdown-item" href="#">Another action</a></li>
                  <li><a class="dropdown-item" href="#">Something else here</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">Separated link</a></li>
                </ul>
            </li> -->
          </ul>
        </div>
      </div>
    </div>
  </template>
  
  


  <style>
</style>
  