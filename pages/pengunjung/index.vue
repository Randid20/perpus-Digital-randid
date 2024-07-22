<template>
  <div class="container-fluid">
    <div class="col-lg-12">
      <h2 class="text-center my-4">RIWAYAT KUNJUNGAN</h2>
      <div class="my-3">
        <input type="search" class="form-control from-control-lg rounded-5" placeholder="Filter...">
      </div>
      <div class="my-3 text-muted">menampilkan 3 dari 3</div>
      <table class="table">
        <thead>
          <tr>
            <td>#</td>
            <td>NAMA</td>
            <td>KEANGGOTAAN</td>
            <td>WAKTU</td>
            <td>KEPERLUAN</td>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>1.</td>
            <td>Randid Delvin</td>
            <td>Siswa</td>
            <td>27 February 2024, 23.31.00</td>
            <td>Baca</td>
          </tr>
        </tbody>
      </table>
      <nuxt-link to="/">
          <button type="submit" class="btn btn-dark btn-lg rounded-5 px-5">Kembali</button>
        </nuxt-link>
    </div>
  </div>
</template>