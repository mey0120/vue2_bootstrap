<template>
  <section id="intro-wrap" class="text-white  text-center">
    
    <div class="container">
      <div class="row">
        <div class="col-sm-12">
          <div class="intro-subtitle">
            <h3 class="font-weight-bold mb-3 text-white">
              Vue Js & Bootstrap
            </h3>
          </div>
          <h1 class="intro-Title font-weight-bold text-42 t-shadow mb-3 text-white">
            Lorem ipsum dolor sit amet
          </h1>
          <div class=" intro-Description text-16">
            <p class="mb-4">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam ducimus error sunt a. Nesciunt,<br>
               eos facere repellat numquam magni nemo animi non nulla alias, 
            </p>
          </div>
          <div class="intro-Buttons mb-5">
            <form class="d-flex align-items-center justify-content-center subscription_form m-auto">
              <div class="form-group subscription-input-wrap"><input type="email" required="required" name="email" id=""
                  aria-describedby="emailHelpId" placeholder="" class="email_field"> <button type="submit"
                  class="btn btn-submit btn-gradient">
                  Subscribe
                </button></div>
            </form>
          </div>
        </div>
      </div>
    </div>
    <div class="overlay"></div>
  </section>
</template>

<script>
export default {
  name: 'Intro',
}
</script>

<style scoped>
#intro-wrap {
    background: url(../assets/teamwork.jpg)center/cover no-repeat;
    padding: 250px 0 250px 0;
    color: #fff;
    overflow: hidden;
    position: relative;
    z-index: 99;
}
.container {
    width: 100%;
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;
}
.row {
    margin-right: -15px;
    margin-left: -15px;
}
.form-group.subscription-input-wrap {
    display: inline-flex;
    box-shadow: 0 1px 15px 1px rgb(0 0 0 / 4%), 0 1px 6px rgb(0 0 0 / 4%);
    padding: 10px;
    border-radius: 50px;
    overflow: hidden;
    background: #fff;}
input {
    border: none;
    outline: none;
    background: #fff;
    color: #47404f;
    padding: 5px;
}
.overlay {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    height: 100%;
    width: 100%;
    z-index: -1;
    opacity: .9;
        background: linear-gradient(
-29deg,#616d86,#1f1c2c)!important;

}
#intro-wrap:after {
    content: "";
    display: block;
    height: 100%;
    background: url(../assets/bg.png) bottom no-repeat;
    background-size: cover;
    position: absolute;
    bottom: -8px;
    left: 0;
    right: 0;
    z-index: -1;
}
.btn-submit{
  padding: 0 24px!important;
    font-size: 18px!important;
    height: 44px;
    border-radius: 25px!important;
}
.btn-gradient{
      color: #fff;
    border: 0 solid rgba(193,15,65,.8);
    background: linear-gradient(
-29deg,#616d86,#1f1c2c)!important;
}
.btn:hover{
  color: #fff;
}
</style>