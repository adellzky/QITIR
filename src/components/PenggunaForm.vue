<template>
  <section class="p-6 bg-gray-100 min-h-screen">
    <h2 class="text-2xl font-bold text-blue-900 mb-6 text-center">Profil Pengguna</h2>
      <form class="grid md:grid-cols-2 gap-6 max-w-5xl mx-auto items-start">
        <!-- Kiri -->
        <div class="flex flex-col gap-4 h-full">
            <div>
                <label class="form-label">Nama</label>
                <input class="input" placeholder="Nama" />
            </div>
            <div class="relative">
                <label class="form-label">Email</label>
                <input class="input pr-10" placeholder="Email" />
                <span class="absolute right-3 top-9 text-gray-400">@</span>
            </div>
            <div>
                <label class="form-label">Alamat</label>
                <textarea class="input  min-h-[105px] resize-none " placeholder="Alamat Domisili"></textarea>
            </div>
        </div>

        <!-- Kanan -->
        <div class="flex flex-col gap-4 h-full">
            <div>
            <label class="form-label">NIK</label>
            <input class="input" placeholder="NIK" />
            </div>
            <div class="relative">
            <label class="form-label">Nomor Handphone</label>
            <input class="input pr-10" placeholder="Nomor Handphone" />
            <span class="absolute right-3 top-9 text-gray-400">📞</span>
            </div>
            <div>
            <label class="form-label">Asal Komunitas/Organisasi/Sekolah/Sanggar</label>
            <input class="input" placeholder="Asal Komunitas/Organisasi/Sekolah/Sanggar" />
            </div>
            <div>
            <label class="form-label">Nama Ketua Komunitas/Organisasi/Sekolah/Sanggar</label>
            <input class="input" placeholder="Nama Ketua Komunitas/Organisasi/Sekolah/Sanggar" />
            </div>
        </div>
      </form>
     <!-- Tombol Simpan -->
    <div class="max-w-5xl mx-auto mt-6 text-right">
      <button class="btn-primary flex items-center gap-2 ml-auto">
        Simpan
        <span>✈️</span>
      </button>
    </div>
  </section>
</template>

<script setup lang="ts">
</script>

<style scoped>

.input {
 @apply w-full p-3 rounded-xl shadow border border-gray-300 focus:outline-none focus:ring-2 focus:ring-blue-500 bg-white text-sm;
}
.btn-primary {
  @apply bg-blue-900 text-white py-2 px-6 rounded-md hover:bg-blue-700 transition text-sm;
}
.form-label {
  @apply text-sm font-semibold text-blue-900 mb-1 block text-left;
}

</style>
