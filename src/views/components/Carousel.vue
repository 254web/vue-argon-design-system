<template>
    <section class="section section-lg section-shaped overflow-hidden my-0">
        <div class="shape shape-style-1 shape-default shape-skew">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
        </div>
        <div class="container py-0 pb-lg">
            <div class="row justify-content-between align-items-center">
                <div class="col-lg-4 mb-5 mb-lg-0">
                    <h1 class="text-white font-weight-light">About Us</h1>
                    <a href="#" class="btn btn-white mt-4">Contact Us</a>
                </div>
                <div class="col-lg-8 mb-lg-auto">
                    <div class="rounded shadow-lg overflow-hidden transform-perspective-right">
                        <b-carousel id="carousel1" controls indicators>
                            <!-- Text slides with image -->
                            <b-carousel-slide img-src="img/theme/img-1-1200x1000.jpg" style="height: 500px;"></b-carousel-slide>
                            <b-carousel-slide img-src="img/theme/img-2-1200x1000.jpg" style="height: 500px;"></b-carousel-slide>
                            <b-carousel-slide>
                                caption="TuCode CDL Phase 1"
                                text="Have An Idea? You Wonder How You Can Get It Done And Be Implemented Digitaly!"
                                style="height: 562px; background-color: transparent;">
                                <div class="col-12">
                                    <card class="border-0" hover shadow body-classes="py-5">
                                        <icon name="ni ni-check-bold" type="primary" rounded class="mb-4">
                                        </icon>
                                        <h6 class="text-primary text-uppercase">Our Three Cs</h6>
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
                        </b-carousel>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";

export default {
    components: {
        BCarousel,
        BCarouselSlide
    }
};
</script>
<style></style>
