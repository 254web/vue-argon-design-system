<template>
    <header class="header-global header-fixed">
        <base-nav class="navbar-main" transparent type="" effect="light" expand>
            <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
                <img src="https://avatars.githubusercontent.com/u/52626265?s=200&v=4" alt="logo">
            </router-link>

            <div class="row" slot="content-header" slot-scope="{closeMenu}">
                <!-- <div class="col-6 collapse-brand">
                    <a href="https://demos.creative-tim.com/vue-argon-design-system/documentation/">
                        <img src="img/brand/blue.png">
                    </a>
                </div> -->
                <div class="col-12 collapse-close">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>

            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
                <!-- <base-dropdown class="nav-item" tag="li" menu-classes="dropdown-menu-xl">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="ni ni-ui-04 d-lg-none"></i>
                        <span class="nav-link-inner--text">Components</span>
                    </a>
                    <div class="dropdown-menu-inner">
                        <a href="https://demos.creative-tim.com/vue-argon-design-system/documentation/"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-primary rounded-circle text-white">
                                <i class="ni ni-spaceship"></i>
                            </div>
                            <div class="media-body ml-3">
                                <h6 class="heading text-primary mb-md-1">Getting started</h6>
                                <p class="description d-none d-md-inline-block mb-0">Get started with Bootstrap, the
                                    world's most popular framework for building responsive sites.</p>
                            </div>
                        </a>
                        <a href="https://demos.creative-tim.com/vue-argon-design-system/documentation/"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-warning rounded-circle text-white">
                                <i class="ni ni-ui-04"></i>
                            </div>
                            <div class="media-body ml-3">
                                <h5 class="heading text-warning mb-md-1">Components</h5>
                                <p class="description d-none d-md-inline-block mb-0">Learn how to use Argon
                                    compiling Scss, change brand colors and more.</p>
                            </div>
                        </a>
                    </div>
                </base-dropdown> -->
                <base-dropdown tag="li">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="ni ni-collection d-lg-none"></i>
                        <span class="nav-link-inner--text">Enterprise Solutions</span>
                    </a>
                </base-dropdown>
                <base-dropdown tag="li">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="ni ni-collection d-lg-none"></i>
                        <span class="nav-link-inner--text">Business Solutions</span>
                    </a>
                </base-dropdown>

                <base-dropdown class="nav-item">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="ni ni-collection d-lg-none"></i>
                        <span class="nav-link-inner--text">Our Company</span>
                    </a>
                    <router-link to="/" class="dropdown-item">About Us</router-link>
                    <router-link to="/" class="dropdown-item">Team</router-link>
                    <router-link to="/" class="dropdown-item">Projects</router-link>
                    <router-link to="/" class="dropdown-item">Contact Us</router-link>
                </base-dropdown>
            </ul>
            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="#" rel="noopener" data-toggle="tooltip"
                        title="Like us on Facebook">
                        <i class="fa fa-facebook-square"></i>
                        <span class="nav-link-inner--text d-lg-none">Facebook</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="#" rel="noopener" data-toggle="tooltip"
                        title="Follow us on Instagram">
                        <i class="fa fa-instagram"></i>
                        <span class="nav-link-inner--text d-lg-none">Instagram</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="#" rel="noopener" data-toggle="tooltip"
                        title="Follow us on Twitter">
                        <i class="fa fa-twitter-square"></i>
                        <span class="nav-link-inner--text d-lg-none">Twitter</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="#" rel="noopener" data-toggle="tooltip"
                        title="Star us on Github">
                        <i class="fa fa-github"></i>
                        <span class="nav-link-inner--text d-lg-none">Github</span>
                    </a>
                </li>
                <li class="nav-item d-lg-block ml-lg-4">
                    <a href="#" rel="noopener" class="btn btn-neutral btn-icon">
                        <span class="btn-inner--icon">
                            <i class="fa fa-calendar mr-2"></i>
                        </span>
                        <span class="nav-link-inner--text">Schedule Contact</span>
                    </a>
                </li>
            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
    components: {
        BaseNav,
        CloseButton,
        BaseDropdown
    }
};
</script>
<style>
.header-fixed {
    position: fixed;
    /* fixing the position takescoordinates */
    left: 0;
    /* top left corner should start at leftmost spot */
    top: 0;
    /* top left corner should start at topmost spot */
    width: 100vw;
    /* take up the full browser width */
    z-index: 200;
    /* high z index so other content scrolls underneath */
    height: 100px;
    background-color: cornflowerblue;
    /* define height for content */
}</style>
