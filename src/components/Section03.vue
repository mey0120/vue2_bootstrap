<template>
<section id="section03-wrap" class="pt-5 pb-5">
  <div class="container">
    <div class="row">
      <div class="section-header col-md-12 mb-5">
        <h2 class="font-weight-bold">Our Works</h2>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Placeat ea
          quam laborum, ducimus, laboriosam sint dolorum aspernatur libero.
        </p>
      </div>
      <div class="accordion col-md-6 col-sm-12" role="tablist">
    <b-card no-body class="mb-1">
      <b-card-header header-tag="header" class="p-1" role="tab">
        <b-button block v-b-toggle.accordion-1 variant="info">Accordion 1</b-button>
      </b-card-header>
      <b-collapse id="accordion-1" visible accordion="my-accordion" role="tabpanel">
        <b-card-body>
          <b-card-text>I start opened because <code>visible</code> is <code>true</code></b-card-text>
          <b-card-text>{{ text }}</b-card-text>
        </b-card-body>
      </b-collapse>
    </b-card>

    <b-card no-body class="mb-1">
      <b-card-header header-tag="header" class="p-1" role="tab">
        <b-button block v-b-toggle.accordion-2 variant="info">Accordion 2</b-button>
      </b-card-header>
      <b-collapse id="accordion-2" accordion="my-accordion" role="tabpanel">
        <b-card-body>
          <b-card-text>{{ text }}</b-card-text>
        </b-card-body>
      </b-collapse>
    </b-card>

    <b-card no-body class="mb-1">
      <b-card-header header-tag="header" class="p-1" role="tab">
        <b-button block v-b-toggle.accordion-3 variant="info">Accordion 3</b-button>
      </b-card-header>
      <b-collapse id="accordion-3" accordion="my-accordion" role="tabpanel">
        <b-card-body>
          <b-card-text>{{ text }}</b-card-text>
        </b-card-body>
      </b-collapse>
    </b-card>
  </div>
      <div class="col-md-6 col-sm-12">

        <b-carousel id="carousel-1" v-model="slide" :interval="0" controls background="#fff">
          <b-carousel-slide caption="First slide" text="Nulla vitae elit libero, a pharetra augue mollis interdum."
            img-src="https://picsum.photos/1024/480/?image=52"></b-carousel-slide>
          <b-carousel-slide caption="2 slide" text="Nulla vitae elit libero, a pharetra augue mollis interdum."
            img-src="https://picsum.photos/1024/480/?image=52"></b-carousel-slide>
        </b-carousel>

      </div>

    </div>
  </div>


</section>
</template>

<script>
export default {
  name: 'Section03'
  
}
</script>