<template>
  <section id="section02-wrap" class="pt-5 pb-5">
    <div class="container">
      <div class="row">
        <div class="section-header mb-5 col-md-12">
          <h2 class="font-weight-bold">Our Services</h2>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Placeat ea
            quam laborum, ducimus, laboriosam sint dolorum aspernatur libero.
          </p>
        </div>
        <div class="service-wrap col-md-6 mb-4 col-lg-3 col-sm-12">
          <div class="card o-hidden">
            <div class="card-header p-0 text-center "><img src="../assets/con3_bg1.jpg" class="img-responsive">
            </div>
            <div class="card-body">
              <h3 class="card-title text-capitalize font-weight-bold  ">
                Service One
              </h3>
              <p class="card-text">Lorem ipsum dolor sit amet additional adipiscing elit Aenean commodo ligula</p>
            </div>
            <div class="card-footer pl-3">
              <a href="#" class="btn mr-1">
                <b-icon icon="link" font-scale="2"></b-icon>
              </a>
              <a href="#" class="btn mr-1">
                <b-icon icon="share" font-scale="1"></b-icon>
              </a>
            </div>
          </div>
        </div>
        <div class="service-wrap col-md-6 mb-4 col-lg-3 col-sm-12">
          <div class="card o-hidden">
            <div class="card-header p-0 text-center"><img src="../assets/con3_bg2.jpg" class="img-responsive">
            </div>
            <div class="card-body">
              <h3 class="card-title text-capitalize font-weight-bold  ">
                Service Two
              </h3>
              <p class="card-text">Lorem ipsum dolor sit amet additional adipiscing elit Aenean commodo ligula</p>
            </div>
            <div class="card-footer pl-3">
              <a href="#" class="btn mr-1">
                <b-icon icon="link" font-scale="2"></b-icon>
              </a>
              <a href="#" class="btn mr-1">
                <b-icon icon="share" font-scale="1"></b-icon>
              </a>
            </div>
          </div>
        </div>
        <div class="service-wrap col-md-6 mb-4 col-lg-3 col-sm-12">
          <div class="card o-hidden">
            <div class="card-header p-0 text-center "><img src="../assets/con3_bg3.jpg" class="img-responsive">
            </div>
            <div class="card-body">
              <h3 class="card-title text-capitalize font-weight-bold  ">
                Service Three
              </h3>
              <p class="card-text">Lorem ipsum dolor sit amet additional adipiscing elit Aenean commodo ligula</p>
            </div>
            <div class="card-footer pl-3">
              <a href="#" class="btn mr-1">
                <b-icon icon="link" font-scale="2"></b-icon>
              </a>
              <a href="#" class="btn mr-1">
                <b-icon icon="share" font-scale="1"></b-icon>
              </a>
            </div>
          </div>
        </div>
        <div class="service-wrap col-md-6 mb-4 col-lg-3 col-sm-12">
          <div class="card o-hidden">
            <div class="card-header p-0 text-center "><img src="../assets/con3_bg4.jpg" class="img-responsive">
            </div>
            <div class="card-body">
              <h3 class="card-title text-capitalize font-weight-bold  ">
                Service Four
              </h3>
              <p class="card-text">Lorem ipsum dolor sit amet additional adipiscing elit Aenean commodo ligula</p>
            </div>
            <div class="card-footer pl-3">
              <a href="#" class="btn mr-1">
                <b-icon icon="link" font-scale="2"></b-icon>
              </a>
              <a href="#" class="btn mr-1">
                <b-icon icon="share" font-scale="1"></b-icon>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Section02',
}
</script>

<style scoped>
#section02-wrap{background: #f8f9fa}
.card {
    border-radius: 10px;
    -webkit-box-shadow: 0 1px 15px 1px rgb(0 0 0 / 4%), 0 1px 6px rgb(0 0 0 / 4%);
    box-shadow: 0 1px 15px 1px rgb(0 0 0 / 4%), 0 1px 6px rgb(0 0 0 / 4%);
    border: 0;
    -webkit-transition: all .15s ease-in;
    transition: all .15s ease-in;
    overflow: hidden;}
    .card:hover{
     -webkit-box-shadow:  0 1px 20px 10px rgb(0 0 0 / 8%), 0 1px 6px rgb(0 0 0 / 10%);
    box-shadow: 0 1px 20px 10px rgb(0 0 0 / 8%), 0 1px 6px rgb(0 0 0 / 10%);
    }
    .card-header{border: none;}
    .card-footer {
    padding: .75rem 1.25rem;
    background-color: transparent;
    border-top: 1px solid rgba(0,0,0,.03);
}
.btn{
  color: #616d86;
  font-weight: bold;
  font-size: 0.8rem;
}
img{ width: 100%;}
</style>
