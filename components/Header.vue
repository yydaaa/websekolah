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
          <img src="../assets/img/Logo.png" alt="Logo SMKN 4 Tasikmalaya" class="img-fluid rounded">
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
          <!-- Elemen tambahan bisa ditambahkan di sini -->
        </div>
        <div class="col-auto">
          <ul class="d-flex list-unstyled mb-0">
            <li class="me-3">
              <NuxtLink to="/" class="nav-link text-white">Home</NuxtLink>
            </li>
            <li class="me-3 dropdown">
              <button class="btn btn-secondary dropdown-toggle" type="button" id="profilDropdown" data-bs-toggle="dropdown" aria-expanded="false">
                Profil
              </button>
              <ul class="dropdown-menu" aria-labelledby="profilDropdown">
                <li><NuxtLink to="/profile" class="dropdown-item">Profile Sekolah</NuxtLink></li>
                <li><NuxtLink to="/visimisi" class="dropdown-item">Visi & Misi</NuxtLink></li>
                <li><NuxtLink to="/strukture" class="dropdown-item">Struktur</NuxtLink></li>
                <li><NuxtLink to="/berita" class="dropdown-item">Berita</NuxtLink></li>
              </ul>
            </li>
            <li class="me-3 ">
              <NuxtLink to="/strukture" class="nav-link text-white">Struktur</NuxtLink>
            </li>
            <li class="dropdown">
              <button class="btn btn-secondary dropdown-toggle" type="button" id="actionDropdown" data-bs-toggle="dropdown" aria-expanded="false">
                Action
              </button>
              <ul class="dropdown-menu" aria-labelledby="actionDropdown">
                <li><NuxtLink to="/fasilitas" class="dropdown-item">Fasilitas</NuxtLink></li>
              </ul>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </template>
  
  <style>
  /* Menghilangkan margin pada dropdown menu */
  .dropdown-menu {
    margin-top: 0;
    padding: 0;
  }
  
  /* Menjaga elemen dropdown sejajar */
  .d-flex  {
    display: flex;
    align-items: center;
  }
  
  /* Responsif untuk logo */
  img {
    max-width: 100%;
    height: auto;
  }
  
  </style>
  