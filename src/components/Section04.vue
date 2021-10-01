<template>
  <section id="section04-wrap" class="pt-5 pb-5">
    <div class="container">
      <div class="row">
          <div class="section-header mb-5 ">
            <h2 class="font-weight-bold ">Get in Touch With Us !</h2>
            <p>
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Placeat
              ea quam laborum, ducimus, laboriosam sint dolorum aspernatur
              libero
            </p>
          </div>
        <div class="form-wrap mb-4 col-md-6">
          <form role="form" class="row form">
            <div class="form-group mb-4 col-md-6">
              <label for=""><b-icon icon="person"></b-icon></label> 
              <input type="text" name="Name" id="" placeholder="Your Name"></div>
            <div class="form-group mb-4 col-md-6">
              <label for=""><b-icon icon="envelope"></b-icon></label> <input
                type="email" required="required" name="email" placeholder="Your email" aria-describedby="helpId"
                ></div>
            <div class="form-group mb-4 col-md-12">
              <label for=""><b-icon icon="pencil"></b-icon></label> <input
                type="text" required="required" name="subject" placeholder="Your subject here" aria-describedby="helpId"
                ></div>
            <div class="form-group mb-4 col-md-12"><label for=""><b-icon icon="pencil-square"></b-icon></label> <textarea
                placeholder="Your message here" required="required" name="message" rows="5"
                ></textarea></div>
            <div class="form-group  col-md-12"><button type="submit"
                class="btn btn-gradient pt-3 pb-3">
                Send message
              </button></div>
          </form>
        </div>
        <div class="col-md-6 align-items-center">
          <div class="right-contact-wrap ml-5"><img src="../assets/contact2.894aa507.svg" alt="Image"
              class="img-responsive zoom-fade"></div>
        </div>
      </div>
    </div>
    </section>
</template>

<style scoped>
#section04-wrap{
  padding-bottom: 120px;
    position: relative;
    z-index: 1;
}
#section04-wrap:after{
  content: "";
    display: block;
    height: 100%;
    background: url(../assets/bg_01.png) bottom no-repeat;
    position: absolute;
    background-size: cover;
    bottom: -8px;
    left: 0;
    right: 0;
    z-index: -1;
}
label {
    position: absolute;
    z-index: 999;
    left: 40px;
    top: 17px;
    font-size: 20px;
    color: #a6b0bd;
    border-right: 1px solid #c6cdd5;
    padding-right: 10px;
    width: 30px;
}
.form-group {
    position: relative;
}
input, textarea {
    padding: 24px 0;
    padding-left: 65px;
    background: #fff;
    border-radius: 20px;
    box-sizing: border-box;
    width: 100%;
    border: initial;
    outline: initial!important;
    color: #47404f;
    border-radius: 10px;
    -webkit-box-shadow: 0 1px 15px 1px rgb(0 0 0 / 4%), 0 1px 6px rgb(0 0 0 / 4%);
    box-shadow: 0 1px 15px 1px rgb(0 0 0 / 4%), 0 1px 6px rgb(0 0 0 / 4%);
    border: 0;
    -webkit-transition: all .15s ease-in;
    transition: all .15s ease-in;
}

input:focus, textarea:focus{
  -webkit-box-shadow:  0 1px 20px 10px rgb(0 0 0 / 8%), 0 1px 6px rgb(0 0 0 / 10%);
    box-shadow: 0 1px 20px 10px rgb(0 0 0 / 8%), 0 1px 6px rgb(0 0 0 / 10%);

}
.btn-gradient{
  width: 100%;
  background: linear-gradient(
-29deg,#616d86,#1f1c2c)!important;
    border-radius: 3px 15px;
    color: #fff;
}
.btn-gradient:hover{
  color: #fff;
}
img {width: 100%;
    height: 470px;
    padding-bottom: 60px;}
</style>