<script setup>
import WelcomeItem from './WelcomeItem.vue'
import IconAlamat from './icons/IconAlamat.vue'
import IconPengalaman from './icons/IconPengalaman.vue'
import IconPendidikan from './icons/IconPendidikan.vue'
import IconKontak from './icons/IconKontak.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <IconAlamat />
    </template>
    <template #heading>Alamat</template>
    Gang Jian RT 05 RW 09 Sukamaju Baru, Kec. Tapos, Kota Depok, Jawa Barat 16455
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <IconPengalaman />
    </template>
    <template #heading>Pengalaman</template>
    <ul>
      <li>Project Web Design</li>
      <li>Project Web Layout</li>
      <li>Design UI UX</li>
      <li>Design Landing Page</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <IconPendidikan />
    </template>
    <template #heading>Pendidikan</template>
    2020 - 2023 <br> SMK Taruna Bhakti <br> Jurusan Rekayasa Perangkat Lunak
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <IconKontak />
    </template>
    <template #heading>Kontak</template>
    0857-7016-7519 <br>
    nazranh18@gmail.com <br>
    @zrn.hisym <br>
    https://github.com/NazranHisyami
  </WelcomeItem>
</template>
