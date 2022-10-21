<script>
import BaseCard from "@/components/Base/CardComp.vue";

export default {
  name: "HomePage",
  components: {
    BaseCard,
  },
};
</script>
<template>
<h1>Hi Namaku <br> Ana Putri</h1>

<p>Aku merupakan mahasiswa semester 7 jurusan Pendidikan Teknik Elektro di Universitas Pendidikan Indonesia.
Kegiatanku saat ini adalah kuliah dan mengikuti program Studi Independen-Kampus Merdeka di PT. Stechoq Robotika.</p>
<p>Berhubung saya bukan dari jurusan IT, maka ini adalah pengalaman pertama saya membuat website dan saya tidak 
  mempunyai list project yang pernah dilakukan. Adapun project yang pernah saya lakukan di kampus berhubungan dengan
  elektro, yaitu project kelompok membuat sistem penyiraman otomatis dengan menggunakan WSN.
</p> 
<div class="grid-container">
<BaseCard />
</div>
</template> 

<style lang="scss">
.grid-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1rem;

  .grid-item {
    width: 100%;
    overflow: hidden;
    border: 1px solid;
    border-radius: 1rem;
  }

  .grid-img {
    width: 100%;
  }
}
</style>
