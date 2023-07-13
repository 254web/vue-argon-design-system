<template>
    <div>
        <div class="position-relative">
            <!-- shape Hero -->
            <section class="section-shaped my-0">
                <div class="shape shape-style-1 shape-default shape-skew shape-color">
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <!-- <TTSCarousel/> -->
                </div>
                <div class="container shape-container d-flex">
                    <div class="col px-0">
                        <div class="row">
                            <div class="col-lg-6">
                                <TTSCarousel/>
                                <!-- <h1 class="display-3  text-white">A beautiful Design System
                                    <span>completed with examples</span>
                                </h1>
                                <p class="lead  text-white">The design system comes with four pre-built pages to help
                                    you get started faster. You can change the text and images and you're good to
                                    go.</p>
                                <div class="btn-wrapper">
                                    <base-button tag="a"
                                        href="https://demos.creative-tim.com/argon-design-system/docs/components/alerts.html"
                                        class="mb-3 mb-sm-0" type="info" icon="fa fa-code">
                                        Components
                                    </base-button>
                                    <base-button tag="a" href="https://www.creative-tim.com/product/argon-design-system"
                                        class="mb-3 mb-sm-0" type="white" icon="ni ni-cloud-download-95">
                                        Download HTML
                                    </base-button>
                                </div> -->
                            </div>
                            <div class="col-lg-6">
                                <!-- <TTSCarousel/> -->
                                <h1 class="display-3  text-white">A beautiful Design System
                                    <span>completed with examples</span>
                                </h1>
                                <p class="lead  text-white">The design system comes with four pre-built pages to help
                                    you get started faster. You can change the text and images and you're good to
                                    go.</p>
                                <div class="btn-wrapper">
                                    <base-button tag="a"
                                        href="https://demos.creative-tim.com/argon-design-system/docs/components/alerts.html"
                                        class="mb-3 mb-sm-0" type="info" icon="fa fa-code">
                                        Components
                                    </base-button>
                                    <base-button tag="a" href="https://www.creative-tim.com/product/argon-design-system"
                                        class="mb-3 mb-sm-0" type="white" icon="ni ni-cloud-download-95">
                                        Download HTML
                                    </base-button>
                                </div>
                            </div>

                        </div>
                    </div>
                </div>
            </section>
            <!-- 1st Hero Variation -->
        </div>
        <section class="section section-lg mt--300">
            <div class="container">
                <div class="row justify-content-center text-center mb-lg">
                    <div class="col-lg-8">
                        <h2 class="display-3">The amazing Team</h2>
                        <p class="lead text-muted">According to the National Oceanic and Atmospheric Administration,
                            Ted, Scambos, NSIDClead scentist, puts the potentially record maximum.</p>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-1-800x800.jpg'"
                                class="rounded-circle img-center img-fluid shadow shadow-lg--hover" style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">Ryan Tompson</span>
                                    <small class="h6 text-muted">Web Developer</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="#" type="warning" icon="fa fa-twitter" rounded
                                        icon-only></base-button>
                                    <base-button tag="a" href="#" type="warning" icon="fa fa-facebook" rounded
                                        icon-only></base-button>
                                    <base-button tag="a" href="#" type="warning" icon="fa fa-dribbble" rounded
                                        icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-2-800x800.jpg'"
                                class="rounded-circle img-center img-fluid shadow shadow-lg--hover" style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">Romina Hadid</span>
                                    <small class="h6 text-muted">Marketing Strategist</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="#" type="primary" icon="fa fa-twitter" rounded
                                        icon-only></base-button>
                                    <base-button tag="a" href="#" type="primary" icon="fa fa-facebook" rounded
                                        icon-only></base-button>
                                    <base-button tag="a" href="#" type="primary" icon="fa fa-dribbble" rounded
                                        icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-3-800x800.jpg'"
                                class="rounded-circle img-center img-fluid shadow shadow-lg--hover" style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">Alexander Smith</span>
                                    <small class="h6 text-muted">UI/UX Designer</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="#" type="info" icon="fa fa-twitter" rounded
                                        icon-only></base-button>
                                    <base-button tag="a" href="#" type="info" icon="fa fa-facebook" rounded
                                        icon-only></base-button>
                                    <base-button tag="a" href="#" type="info" icon="fa fa-dribbble" rounded
                                        icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-4-800x800.jpg'"
                                class="rounded-circle img-center img-fluid shadow shadow-lg--hover" style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">John Doe</span>
                                    <small class="h6 text-muted">Founder and CEO</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="#" type="success" icon="fa fa-twitter" rounded
                                        icon-only></base-button>
                                    <base-button tag="a" href="#" type="success" icon="fa fa-facebook" rounded
                                        icon-only></base-button>
                                    <base-button tag="a" href="#" type="success" icon="fa fa-dribbble" rounded
                                        icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
import TTSCarousel from "@/components/TTSCarousel"
export default {
    name: "home",
    components: {
        TTSCarousel
    }
};
</script>
<style>
.shape-color{
    /* background-color: aqua; */
}
</style>
