<template>
  <footer class="bg-gray-200 text-gray-600 p-4 mt-10">
    <div class="container mx-auto flex justify-between">
      <div>
        <h5 class="font-bold mb-2">Tentang Kami</h5>
        <p>Web Sekolah adalah platform untuk melihat informasi seputar smkn4 </p>
      </div>
      <div>
        <h5 class="font-bold mb-2">Link Cepat</h5>
        <ul>
          <li class="mb-2">
            <Nuxt Link to="/">Beranda</Nuxt>
          </li>
          <li class="mb-2">
            <Nuxt Link to="/profil">Profil sekolah</Nuxt>
          </li>
          <li>
            <Nuxt Link to="/ekskul">Ekstrakulikuler</Nuxt>
          </li>
        </ul>
      </div>
      <div>
        <h5 class="font-bold mb-2">Hubungi Kami</h5>
        <p>Alamat: Jl. Depok </p>
        <p>Telp: +62265312059 </p>
        <p>Email: info@smkn4-tsm.sch.id </p>
      </div>
    </div>
    <div class="text-center mt-4">
      &copy; {{ tahun }} Web Sekolah. All rights reserved.
    </div>
  </footer>
</template>


# Script

<script>
export default {
  data() {
    return {
      tahun: new Date().getFullYear(),
    };
  },
};
</script>