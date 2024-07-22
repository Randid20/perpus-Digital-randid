<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-tg-12">
        <h2 class="text-center my-4">BUKU</h2>
        <div class="my-3">
          <input type="search" class="form-control rounded-5" placeholder="mau baca apa hari ini?">
        </div>
        <div class="my-3 text-muted">menampilkan 3 dari 3</div>
        <div class="row">
          <div class="col-lg-2">            
         <div class="card mb-3">
          <div class="card-body">
            <img src="/assets/img/ega.jpeg" class="cover" alt ="cover 1">
              
          </div>
        </div>
       </div> 
       <div class="col-lg-2">            
         <div class="card mb-3">
          <div class="card-body">
            <img src="/assets/img/g.jpeg" class="cover" alt ="cover 1">
              
          </div>
        </div>
       </div> 
       <div class="col-lg-2">            
         <div class="card mb-3">
          <div class="card-body">
            <img src="/assets/img/laskar-pelangi.jpg" class="cover" alt ="cover 1">
              
          </div>
        </div>
       </div> 
      </div>
    </div>
  </div>
  </div>
</template>
<style scoped>
.cover {
  width: 100%;
  height: 100%; 
  object-fit: cover;
  object-position: 0 30;
}
.form-control{
  background-color: #A08D8D;
}
</style>