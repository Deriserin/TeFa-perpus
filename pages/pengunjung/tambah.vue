<template>
  <div class="container-fluid"></div>
      <div class="row">
      <div class="col-lg-12">
          <h2 class="text-center my-4">ISI BUKU KUNJUNGAN</h2>
          <form>
              <div class="mb-3">
                  <input type="text" class="form-control form-control-lg rounded-5" placeholder="NAMA...">
              </div>
              <div class="mb-3">
                  <select class="form-control form-control-lg form-select rounded-5">
                      <option value="">KEANGGOTAAN</option>
                      <option value="Siswa">Siswa</option>
                      <option value="Guru">Guru</option>
                      <option value="Staf">Staf</option>
                      <option value="Umum">Umum</option>
                  </select>
              </div>
              <div class="mb-3">
                  <div class="row">
                      <div class="col-md-4">
                          <select class="form-control form-control-lg form-select rounded-5 mb-2">
                              <option value="">TINGKAT</option>
                              <option value="X">X</option>
                              <option value="XI">XI</option>
                              <option value="XII">XII</option>
                          </select>
                      </div>
                      <div class="coll-md-4">
                          <select class="form-control form-control-lg form-select rounded-5 mb-2">
                              <option value="">JURUSAN</option>
                              <option value="RPL">RPL</option>
                              <option value="TKJ">TKJ</option>
                              <option value="TBSM">TBSM</option>
                              <option value="DKV">DKV</option>
                              <option value="TOI">TOI</option>
                          </select>
                      </div>
                      <div class="col-md-4">
                          <select class="form-control form-control-lg form-select rounded-5 mb-2">
                              <option value="">KELAS</option>
                              <option value="1">1</option>
                              <option value="2">2</option>
                              <option value="3">3</option>
                          </select>
                      </div>
                  </div>
              </div>
                  <div class="mb-3">
                  <select class="form-control form-control-lg form-select rounded-5">
                      <option value="">KEPERLUAN</option>
                              <option value="Baca Buku">Baca buku</option>
                              <option value="Pinjam Buku">Pinjam buku</option>
                              <option value="Kembalikan Buku">Kembalikan buku</option>
                  </select>
                  </div>
                  <button type="submit" class="btn btn-dark btn-lg rounded-5 px-5">KIRIM</button>
          </form>
      </div>
  </div>
</template>