<template>
  <section id="section01-wrap" class="pt-5 pb-5">
    <div class="container">
      <div class="row">
        <div class="section-header mb-5 col-md-12">
          <h2 class="font-weight-bold">Bootstrap Icons</h2>
          <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Placeat ea quam laborum, ducimus, laboriosam sint
            dolorum aspernatur libero.</p>
        </div>
        <div class="mb-4 mb-lg-0 col-sm-12 col-md-6 col-lg-6">
          <div class="row">
            <div class="mb-4 col-sm-6 col-md-6 col-lg-4">
              <div class="card text-center">
                <div class="card-body">
                  <b-icon icon="exclamation-triangle" font-scale="3"></b-icon>
                  <p class="card-title pt-3">icon</p>
                </div>
              </div>
            </div>
            <div class="mb-4 col-sm-6 col-md-6 col-lg-4">
              <div class="card text-center">
                <div class="card-body">
                  <b-icon icon="exclamation-triangle-fill" font-scale="3"></b-icon>
                  <p class="card-title pt-3">fill icon</p>
                </div>
              </div>
            </div>
            <div class="mb-4 col-sm-6 col-md-6 col-lg-4">
              <div class="card text-center">
                <div class="card-body">
                  <b-icon icon="arrow-clockwise" animation="spin" font-scale="3"></b-icon>
                  <p class="card-title pt-3">spin icon</p>
                </div>
              </div>
            </div>
            <div class="mb-4 col-sm-6 col-md-6 col-lg-4">
              <div class="card text-center">
                <div class="card-body">
                  <b-icon icon="star-fill" animation="fade" font-scale="3"></b-icon>
                  <p class="card-title pt-3">fade icon</p>
                </div>
              </div>
            </div>
            <div class="mb-4 col-sm-6 col-md-6 col-lg-4">
              <div class="card text-center">
                <div class="card-body">
                  <b-icon icon="clock-fill" animation="throb" font-scale="3"></b-icon>
                  <p class="card-title pt-3">throb icon</p>
                </div>
              </div>
            </div>
            <div class="mb-4 col-sm-6 col-md-6 col-lg-4">
              <div class="card text-center">
                <div class="card-body">
                  <b-iconstack font-scale="3">
                      <b-icon stacked icon="square"></b-icon>
                      <b-icon stacked icon="check"></b-icon>
                  </b-iconstack>
                  <p class="card-title pt-3">stacked icon</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="offset-lg-1 d-flex align-items-center col-sm-12 col-md-6 col-lg-5"><img
            src="../assets/slider2.94d23c4e.svg" alt="" class="img-responsive w-100"></div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Section01',
}
</script>

<style scoped>
svg{
  color: #616d86;
}
.card {
    border-radius: 10px;
    -webkit-box-shadow: 0 1px 15px 1px rgb(0 0 0 / 4%), 0 1px 6px rgb(0 0 0 / 4%);
    box-shadow: 0 1px 15px 1px rgb(0 0 0 / 4%), 0 1px 6px rgb(0 0 0 / 4%);
    border: 0;
    -webkit-transition: all .15s ease-in;
    transition: all .15s ease-in;}
    .card:hover{
      -webkit-box-shadow:  0 1px 20px 10px rgb(0 0 0 / 8%), 0 1px 6px rgb(0 0 0 / 10%);
    box-shadow: 0 1px 20px 10px rgb(0 0 0 / 8%), 0 1px 6px rgb(0 0 0 / 10%);
    }
.card-body{
  height: 150px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.card-body p{
  font-size: 18px;
}
</style>