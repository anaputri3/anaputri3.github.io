<template>
<div class="grid-container">

  <figure class="grid-item">
    <img class="grid-img" src="src\assets\1.jpg" alt="" />
  </figure>
</div>
  <div class="about">
    
    <p>Nama : Ana Putri <br>
      E-mail : anaputri@upi.edu <br>
      Telepon : 082319082055 <br>
      Pesan : Lakukan apa yang bisa kita lakukan semaksimal mungkin, ketika tidak bisa baru meminta bantuan orang lain. 
    </p>
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
