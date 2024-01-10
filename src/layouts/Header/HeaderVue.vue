<template>
    <header>
        <div class="container">
            <nav class="navbar navbar-expand-lg navbar-light bg-light"
                uk-sticky="top: 90; animation: uk-animation-slide-top; bottom: #sticky-on-scroll-up">
                <div class="container-fluid">
                    <a class="navbar-brand" href="#">Assembly</a>
                    <button class="navbar-toggler" type="button" data-toggle="collapse"
                        data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                        aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarSupportedContent">
                        <ul class="navbar-nav mx-auto">
                            <li class="nav-item active"><a class="nav-link" href="#">HOMEPAGE <span
                                        class="sr-only">(current)</span></a></li>
                            <li class="nav-item"><a class="nav-link" href="#">OUR CLIENTS</a></li>
                            <li class="nav-item"><a class="nav-link" href="#">ABOUT US</a></li>
                            <li class="nav-item"><a class="nav-link" href="#">CAREERS</a></li>
                            <li class="nav-item"><a class="nav-link" href="#">CONTACT US</a></li>
                        </ul>
                    </div>
                </div>
            </nav>
        </div>
        <div class="head-info text-center text-white">
            <h1 v-if="show">{{ ifHeading }}</h1>
            <h1 v-else>{{ elseHeding }}</h1>
            <p>Donec pulvinar ullamcorper metus</p>
            <button class="btn btn-lg btn-primary" v-on:click="display">Get Mor Info</button>
            <!-- <SiteBtn btnName="Pulvinar mollis"/> -->
        </div>
    </header>
</template>

<script>
// import SiteBtn from '@/components/Button/SiteBtn'
    export default {
       name: 'HeaderVue',
       components:{
        // SiteBtn
       },
       data (){
        return {
            show: true,
            ifHeading: "Ismail Khondokar",
            elseHeding: "Not Sell Product"
        }
       },
       methods:{
           display(){
                this.show=!this.show
           }
       }
    }
</script>