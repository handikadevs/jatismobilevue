<template>
    <header class="header-global">
        <base-nav class="navbar-main" transparent type="" effect="light" expand>
            <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
                <strong> Jatis Mobile</strong> 
            </router-link>

            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
                    <a slot="title" href="#about" class="nav-link" role="button" data-toggle="collapse">
                        <span class="nav-link-inner--text">About us</span>
                    </a>
                    <a slot="title" href="#product" class="nav-link" role="button">
                        <span class="nav-link-inner--text">Product</span>
                    </a>
                    <a slot="title" href="#service" class="nav-link" role="button">
                        <span class="nav-link-inner--text">Service</span>
                    </a>
                    <a slot="title" href="#event" class="nav-link" role="button">
                        <span class="nav-link-inner--text">Event</span>
                    </a>
                    <a slot="title" href="#partner" class="nav-link" role="button">
                        <span class="nav-link-inner--text">Partner</span>
                    </a>
                    <a slot="title" href="#join" class="nav-link" role="button">
                        <span class="nav-link-inner--text">Careers</span>
                    </a>
                    <a slot="title" href="#contact" class="nav-link" role="button">
                        <span class="nav-link-inner--text">Contact us</span>
                    </a>
            </ul>
            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="#" target="_blank" rel="noopener"
                       data-toggle="tooltip" title="Like us on Facebook">
                        <i class="fa fa-facebook-square"></i>
                        <span class="nav-link-inner--text d-lg-none">Facebook</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="#"
                       target="_blank" rel="noopener" data-toggle="tooltip" title="Follow us on Instagram">
                        <i class="fa fa-instagram"></i>
                        <span class="nav-link-inner--text d-lg-none">Instagram</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="#" target="_blank" rel="noopener"
                       data-toggle="tooltip" title="Follow us on Twitter">
                        <i class="fa fa-twitter-square"></i>
                        <span class="nav-link-inner--text d-lg-none">Twitter</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="#"
                       target="_blank" rel="noopener" data-toggle="tooltip" title="Visit us on LinkedIn">
                        <i class="fa fa-linkedin"></i>
                        <span class="nav-link-inner--text d-lg-none">Linkedin</span>
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
</style>
