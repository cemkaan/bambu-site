<template>
  <div class="col-md-8 py-5 px-3 mx-auto">
    <header class="pb-3 mb-5 border-bottom">
      <h1 class="h4">
        <a
          href="/"
          class="d-flex align-items-center text-dark text-decoration-none"
        >
          <img height="150" src="~/assets/img/bambu.png" alt="bambu" />
        </a>
      </h1>
    </header>

    <h1>RePlay</h1>

    <div class="row py-3">
      <div class="col-sm">
        <div class="col-lg-8 px-0">
          <p class="lead">
            Oyunda amacımız kullanıcının hareket etmesi. Oyunda kayıt edilmiş
            konuma geldiğinde oyuncuya hediye veriyor.
          </p>
        </div>
        <div class="col-lg-8 p-2 bg-light">
          <p class="lead">
            Kardelen Okulu Kardebot gurubu karakteri.
            <span class="border">Panda Rolly</span> ve Bambu macerası.
          </p>
        </div>
        <div class="row py-3">
          <a
            href="https://gitlab.com/kaanguru/bambu"
            target="_blank"
            type="button"
            class="btn btn-primary"
            >Oyun Kodları</a
          >
          <a
            href="/bambu-0115.apk"
            target="_blank"
            type="button"
            class="btn btn-secondary ml-4"
            >Android için indir</a
          >
        </div>
      </div>

      <div class="col-sm">
        <img
          src="~/assets/img/4.gif"
          class="img-fluid mx-auto"
          alt="map"
          style="width: 500px"
        />
      </div>
    </div>
    <div class="row"></div>
    <div class="row">
      <img src="~/assets/img/map.png" class="img-fluid py-3" alt="map" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>
