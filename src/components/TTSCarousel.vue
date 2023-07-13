<template>
  <div>
    <b-carousel id="carousel-1" v-model="slide" :interval="4000" controls indicators img-width="1024"
      img-height="480" style="text-shadow: 1px 1px 2px #333;" @sliding-start="onSlideStart" @sliding-end="onSlideEnd">
      <!-- Text slides with image -->
      <b-carousel-slide 
      caption="TuCode CDL Phase 1" 
      text="Have An Idea? You Wonder How You Can Get It Done And Be Implemented Digitaly!"
        style="height: 562px; background-color: transparent;">
        <div class="col-12">
          <card class="border-0" hover shadow body-classes="py-5">
            <icon name="ni ni-check-bold" type="primary" rounded class="mb-4">
            </icon>
            <h6 class="text-primary text-uppercase">Our Three Cs</h6>
            <!-- <p class="description mt-3">Argon is a great free UI package based on Bootstrap 4
              that includes the most important components and features.</p> -->
            <div>
              <badge type="primary" rounded>Contact</badge>
              <badge type="primary" rounded>Consult</badge>
              <badge type="primary" rounded>Command</badge>
            </div>
            <base-button tag="a" href="#" type="primary" class="mt-4">
              Get In Touch
            </base-button>
          </card>
        </div>
      </b-carousel-slide>

      <!-- Slides with custom text -->
      <b-carousel-slide 
      caption="TuCode CDL Phase 2" 
      text="We Document, Design & Develop Together"
        style="height: 562px;">

        <div class="col-lg-12">
          <card class="border-0" hover shadow body-classes="py-5">
            <icon name="ni ni-istanbul" type="success" rounded class="mb-4">
            </icon>
            <h6 class="text-success text-uppercase">Our Three Ds</h6>
            <div>
              <badge type="success" rounded>Document</badge>
              <badge type="success" rounded>Design</badge>
              <badge type="success" rounded>Develop</badge>
            </div>
            <base-button tag="a" href="#" type="success" class="mt-4">
              Progress
            </base-button>
          </card>
        </div>

      </b-carousel-slide>

      <!-- Slides with custom text -->
      <b-carousel-slide 
      caption="TuCode CDL Phase 3" 
      text="As We Document, Develop & Design, We Listen Learn & Implement Before Go-Live to Launch"
      style="height: 562px;">

        <div class="col-lg-12">
          <card class="border-0" hover shadow body-classes="py-5">
            <icon name="ni ni-planet" type="warning" rounded class="mb-4">
            </icon>
            <h6 class="text-warning text-uppercase">Our Three Ls</h6>
            <div>
              <badge type="warning" rounded>Listen</badge>
              <badge type="warning" rounded>Learn</badge>
              <badge type="warning" rounded>Launch</badge>
            </div>
            <base-button tag="a" href="#" type="warning" class="mt-4">
              Projects
            </base-button>
          </card>
        </div>
      </b-carousel-slide>

      <!-- Slides with img slot -->
      <!-- Note the classes .d-block and .img-fluid to prevent browser default image alignment -->
      <!-- <b-carousel-slide>
        <template #img>
          <img
            class="d-block img-fluid w-100"
            src="https://picsum.photos/1024/480/?image=55"
            alt="image slot"
          >
          <div class="col-lg-12">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-planet" type="warning" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-warning text-uppercase">Prepare Launch</h6>
                                    <p class="description mt-3">Argon is a great free UI package based on Bootstrap
                                        4 that includes the most important components and features.</p>
                                    <div>
                                        <badge type="warning" rounded>marketing</badge>
                                        <badge type="warning" rounded>product</badge>
                                        <badge type="warning" rounded>launch</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="warning" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
        </template>
      </b-carousel-slide> -->

      <!-- Slide with blank fluid image to maintain slide aspect ratio -->
      <!-- <b-carousel-slide caption="Blank Image" img-blank img-alt="Blank image">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse eros felis, tincidunt
          a tincidunt eget, convallis vel est. Ut pellentesque ut lacus vel interdum.
        </p>
      </b-carousel-slide> -->
    </b-carousel>

    <!-- <p class="mt-4">
      Slide #: {{ slide }}<br>
      Sliding: {{ sliding }}
    </p> -->
  </div>
</template>

<script>
export default {
  data() {
    return {
      slide: 0,
      sliding: null
    }
  },
  methods: {
    onSlideStart(slide) {
      this.sliding = true
    },
    onSlideEnd(slide) {
      this.sliding = false
    }
  }
}
</script>
<style>
.card {

  background-color: transparent;
}
</style>