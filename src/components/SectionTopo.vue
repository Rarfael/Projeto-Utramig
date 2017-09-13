<template lang="html">
  <section  id="home-section" >
      <div class="dark-overlay">
        <div class="home-inner">
          <div class="row pb-5">
            <div class="col-lg-12 text-center">
              <img src="../assets/pc-computer-with-monitor.jpg" class="img-rounded img-fluid" alt="Responsive image">
            </div>
          </div>
            <div class="row">
              <div class="col-lg-12 text-center pb-5">
                <h1 class="display-5">Encontraremos o melhor técnico a disposição!</h1>
              </div>
            </div>
          <div class="row">
              <div class="col-lg-12 text-center">
                <button type="button" name="button" class="btn btn-primary btn-lg">{{$route.params.name}}</button>
              </div>
          </div>
      </div>
  </div>

  </section>
</template>

<script>
export default {
}
</script>

<style >
.img-rounded{
  width: 100px;
  height: 100px;
  border-radius: 50%;
}
.dark-overlay {
  background-color: rgba(0, 0, 0, 0.7);
  position: absolute;
  top: 0;
  width: 100%;
  min-height: 600px; }

  #home-section {
  background-image: url("../assets/circuito.jpeg");
  min-height: 960px;
  width: 100%;
  background-size: cover;
  background-attachment: fixed;
}

#home-section .home-inner {
padding-top: 333px;
padding-bottom: 333px;
}

</style>
