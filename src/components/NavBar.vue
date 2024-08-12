<template>
  <div class="navbar container rounded">
    <div class="row" style="width: 100%">
      <div class="col-4" style="text-align: left">
        <button class="rounded-circle ms-2">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="16"
            width="12"
            viewBox="0 0 384 512"
          >
            <path
              d="M380.6 81.7c7.9 15.8 1.5 35-14.3 42.9L103.6 256 366.3 387.4c15.8 7.9 22.2 27.1 14.3 42.9s-27.1 22.2-42.9 14.3l-320-160C6.8 279.2 0 268.1 0 256s6.8-23.2 17.7-28.6l320-160c15.8-7.9 35-1.5 42.9 14.3z"
            />
          </svg>
        </button>
        <button class="rounded-circle ms-2">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="16"
            width="12"
            viewBox="0 0 384 512"
          >
            <path
              d="M3.4 81.7c-7.9 15.8-1.5 35 14.3 42.9L280.5 256 17.7 387.4C1.9 395.3-4.5 414.5 3.4 430.3s27.1 22.2 42.9 14.3l320-160c10.8-5.4 17.7-16.5 17.7-28.6s-6.8-23.2-17.7-28.6l-320-160c-15.8-7.9-35-1.5-42.9 14.3z"
            />
          </svg>
        </button>
      </div>
      <div class="col-8" style="text-align: right">
        <button class="rounded-pill ms-2 mt-2">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="16"
            width="16"
            viewBox="0 0 512 512"
          >
            <path
              d="M288 32c0-17.7-14.3-32-32-32s-32 14.3-32 32V274.7l-73.4-73.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3l128 128c12.5 12.5 32.8 12.5 45.3 0l128-128c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L288 274.7V32zM64 352c-35.3 0-64 28.7-64 64v32c0 35.3 28.7 64 64 64H448c35.3 0 64-28.7 64-64V416c0-35.3-28.7-64-64-64H346.5l-45.3 45.3c-25 25-65.5 25-90.5 0L165.5 352H64zm368 56a24 24 0 1 1 0 48 24 24 0 1 1 0-48z"
            />
          </svg>
          Install App
        </button>
        <button class="rounded-circle ms-2" aria-placeholder="What's">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="16"
            width="14"
            viewBox="0 0 448 512"
          >
            <path
              d="M224 0c-17.7 0-32 14.3-32 32V51.2C119 66 64 130.6 64 208v18.8c0 47-17.3 92.4-48.5 127.6l-7.4 8.3c-8.4 9.4-10.4 22.9-5.3 34.4S19.4 416 32 416H416c12.6 0 24-7.4 29.2-18.9s3.1-25-5.3-34.4l-7.4-8.3C401.3 319.2 384 273.9 384 226.8V208c0-77.4-55-142-128-156.8V32c0-17.7-14.3-32-32-32zm45.3 493.3c12-12 18.7-28.3 18.7-45.3H224 160c0 17 6.7 33.3 18.7 45.3s28.3 18.7 45.3 18.7s33.3-6.7 45.3-18.7z"
            />
            Install App
          </svg>
        </button>
        <!-- Profile Dropdown Menu -->
        <div class="btn-group">        
          <button type="button" class="btn dropdown-toggle rounded-pill ms-2" data-bs-toggle="dropdown">
            <img
              src="https://picsum.photos/id/237/50/50"
              alt=""
              class="rounded-pill ms-2"
            />
          </button>
          <ul class="dropdown-menu dropdown-menu-dark dropdown-menu-lg-end">
            <li><a class="dropdown-item" href="#">Hesap</a></li>
            <li><a class="dropdown-item" href="#">Aile planını ayarla</a></li>
            <li><a class="dropdown-item" href="#">Profil</a></li>
            <li><a class="dropdown-item" href="#">Gizli oturum</a></li>
            <li><a class="dropdown-item" href="#">Ayarlar</a></li>
            <li><hr class="dropdown-divider" /></li>
            <li><a class="dropdown-item" href="#">Spotify'ı güncelle</a></li>
            <li><a class="dropdown-item" href="#">Oturumu kapat</a></li>
          </ul>
        </div>
      </div>
    </div>
    <br />
    <div class="row">
      <div>
        <button class="rounded-pill ms-2 my-2">All</button>
        <button class="rounded-pill ms-2">Music</button>
        <button class="rounded-pill ms-2">Podcast</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  background-color: rgb(13, 13, 81);
  border: none;
  width: 74%;
  position: fixed;
  z-index: 3;
}
button {
  background-color: rgba(232, 232, 232, 0.2);
}

.rightNavSide {
  text-align: right;
}
</style>
