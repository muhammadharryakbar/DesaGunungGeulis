<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />

  <main class="flex">
    <Sidebar />

    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        “ TERWUJUDNYA DESA GUNUNG GEULIS YANG MULIA,BERBUDAYA,SERTA BERAKHLAK MULIA ”
      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
          1. Mewujudkan pemerintahan Desa yang jujur dan berwibawa dengan pengambilan keputusan yang cepat dan tepat;
        </li>
        <li>
          2. Meningkatkan Mutu Pelayanan Kesehatan seluruh masyarakat desa secara maksimal;
        </li>
        <li>
          3. Meningkatkan kualitas Pendidikan baik Akademis maupun Non Akademis,serta mengapresiasi seluruh warga yang berprestasi melalui program Desa Cerdas;
        </li>
        <li>
          4. Mendukung dan memfasilitasi seluruh kegiatan Keagamaan,Kesenian,Kebudayaan dan Olahraga;
        </li>
        <li>
          5. Mambantu menyalurkan lapangan pekerjaan bagi warga terhadap perusahaan yang berada di Desa Gunung Geulis;
        </li>
        <li>
          6. Meningkatkan kualitas lingkungan hidup;
        </li>
        <li>
          7. Memperkuat tata kelola Pemerintahan Desa yang Transparan,Akuntable,dan Berorientasi pada Pelayanan Publik;
        </li>
        
      </ul>
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
