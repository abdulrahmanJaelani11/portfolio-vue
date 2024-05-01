<template>
  <div class="home">
    <div class="container">
      <div class="row py-3">
        <div class="col-3">
          <img
            src="../../public/assets/images/profile/user-1.jpg"
            class="img-fluid rounded-circle"
            alt=""
          />
        </div>
        <div class="col-9 text-start d-flex align-items-center">
          <div>
            <h3 class="fw-semibold mb-1">Abdul Rahman Jaelani</h3>
            <span class="d-block">Mahasiswa | Fullstack Web Developer</span>
          </div>
        </div>
        <div class="col-12">
          <hr class="m-0 mt-2 pb-0" />
        </div>
      </div>

      <div class="row">
        <div class="col-12">
          <h4><i class="fa-solid fa-bars-staggered"></i> My Projects</h4>
        </div>
        <div class="col-12 mt-3 d-flex justify-content-around">
          <a
            href="http://ourquran.epizy.com/"
            target="_blank"
            class="text-dark icon"
          >
            <div>
              <i class="p-4 fs-7 rounded shadow fa-solid fa-book-open"></i>
            </div>
            <small>OurQuran</small>
          </a>
          <a
            href="http://bayarkas.vercel.app"
            target="_blank"
            class="text-dark icon"
          >
            <div>
              <i class="p-4 fs-7 rounded shadow fa-solid fa-wallet"></i>
            </div>
            <small>Bayar Kas</small>
          </a>
          <a
            href="https://abdulrahmanjaelani11.github.io/"
            target="_blank"
            class="text-dark icon"
          >
            <div>
              <i class="p-4 fs-7 rounded shadow fa-solid fa-address-card"></i>
            </div>
            <small>Portfolio</small>
          </a>
          <a
            href="https://unduh-video.netlify.app/"
            target="_blank"
            class="text-dark icon"
          >
            <div>
              <i class="p-4 fs-7 rounded shadow fa-solid fa-circle-down"></i>
            </div>
            <small>Unduh video</small>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeView",
};
</script>
