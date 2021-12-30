<template>
  <q-page padding>
      <div class="row q-mb-md col-gutter-md">
      <div class="col-md-12 col-xs-12 col-lg-12">
        <div class="row">
          <div class="col-auto">
            <div class="left blue"></div>
          </div>
          <div class="col">
            <q-banner inline-actions class="text-blue-grey-14">
              <div class="text-h6">Apotik Sederhana</div>
              <div>Dibuat Oleh</div>
            </q-banner>
          </div>
        </div>
      </div>
    </div>
    <q-card flat bordered>
      <q-item>
        <q-item-section avatar>
          <q-avatar>
            <img src="statics/eriko.jpg">
          </q-avatar>
        </q-item-section>
        <q-item-section>
          <q-item-label>Eriko Zakaria</q-item-label>
          <q-item-label caption>
            18421003
          </q-item-label>
        </q-item-section>
      </q-item>
      <q-separator />
      <q-card-section horizontal>
        <q-card-section>
          {{ info }}
        </q-card-section>
        <q-separator vertical />
        <q-card-section class="col-4">
          <q-item-label>Ig : erikozakaria</q-item-label>
          <q-item-label>WA : 0895606009940 </q-item-label>
        </q-card-section>
      </q-card-section>
    </q-card>
    <div class="row q-mb-md col-gutter-md">
      <div class="col-md-12 col-xs-12 col-lg-12">
        <div class="row">
          <div class="col-auto">
            <div class="left blue"></div>
          </div>
          <div class="col">
          </div>
        </div>
      </div>
    </div>
    <q-card flat bordered>
      <q-item>
        <q-item-section avatar>
          <q-avatar>
            <img src="statics/kasino.jpeg">
          </q-avatar>
        </q-item-section>
        <q-item-section>
          <q-item-label>Ahmad Rofiq Zulkarnain </q-item-label>
          <q-item-label caption>
            18421064
          </q-item-label>
        </q-item-section>
      </q-item>
      <q-separator />
      <q-card-section horizontal>
        <q-card-section>
          {{ info }}
        </q-card-section>
        <q-separator vertical />
        <q-card-section class="col-4">
          <q-item-label>Ig : ahmadrofiqzulkarnain </q-item-label>
          <q-item-label>WA : 082306839842 </q-item-label>
        </q-card-section>
      </q-card-section>
    </q-card>
  </q-page>
</template>
<script>
export default {
  data () {
    return {
      info: 'Mahasiswa Fakultas Ilmu Komputer Universitas Bandar Lampung 2018'
    }
  }
}
</script>
<style lang="sass" scoped>
</style>
<style scoped>
  .left {
    width: 5px;
    height: 100%;
    background: pink;
  }
</style>
