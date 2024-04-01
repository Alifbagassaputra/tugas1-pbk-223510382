<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>PENDIDIKAN</template>

  MEMULAI JENJANG PENDIDIKAN:
  <ul>
  <li><a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/10c4d4c7-2ff5-e011-9a70-ffbc13a59d30" target="_blank" rel="noopener">SDN 132 PEKANBARU</a></li>
  <li><a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/b0499c24-8b18-e111-a4da-052b49722394" target="_blank" rel="noopener">SMPN 5 PEKANBARU</a></li>
  <li><a href="https://sman6pekanbaru.sch.id/" target="_blank" rel="noopener">SMAN 6 PEKANBARU</a></li>
  <li><a href="https://uir.ac.id/profil" target="_blank" rel="noopener">Universitas Islam Riau</a></li>
</ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>JURUSAN</template>

    Saat ini, saya sedang menempuh pendidikan di Universitas Islam Riau jurusan Teknik Informatika S1, pada program studi <a href="https://eng.uir.ac.id/" target="_blank" rel="noopener">Teknik UIR</a>. Saya telah memasuki semester 4 dan sedang aktif belajar untuk mengembangkan pemahaman dan keterampilan dalam bidang ini. 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>TEMPAT LAHIR</template>

    Saya lahir di kota <a href="https://www.pekanbaru.go.id/" target="_blank" rel="noopener">PEKANBARU</a> pada tanggal 31 Mei 2002, Pekanbaru sebuah kota yang terletak di Provinsi Riau, Indonesia. Pekanbaru, yang merupakan ibu kota provinsi, merupakan pusat kegiatan ekonomi dan budaya di wilayah tersebut. Tempat kelahiran saya ini memberikan banyak kenangan indah dan menjadi bagian penting dalam membentuk identitas serta perjalanan hidup saya.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>HOBI</template>
    HOBI YANG SAYA SUKA SEBAGAI BERIKUT:
  <ul>
  <li><a href="https://open.spotify.com/user/212tgtrd3djlj2cgdy6abmwvi?si=d988f15712ad4f00&nd=1&dlsi=d15c98103f3446ac" target="_blank" rel="noopener">Musik</a></li>
  <li>GAME</li>
  <li>STREAMING</li>
</ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>RELATIONSHIP</template>

    Saat ini saya sedang tidak menjalin hubungan apapun dan siapapun alias saya sedang jomblo
  </WelcomeItem>
</template>


<style scoped>
a {
  color: #DAEE01;
}
</style>