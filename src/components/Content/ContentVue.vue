<template>
    <!-- start content -->
    <section class="content text-center">
        <div class="container">
            <p>Fusce ultrices fringilla metus Donece leo, vivamus fermentum nibh in augue praesent a lacus at urna
                congue This is assembly, a free, fully standards-compliant CSS template designed by <a
                    href="#">TEMPLATED</a> The photos in this template are from <a href="#">Fotograph</a>. This free
                template is released under the "Creative Commons Attribution" licence, so you're pretty much free to do
                whatever you want with it (even use it commercially) provided you give us credit for it. Have a fun:)
            </p>
            <SiteBtn btnName="Etiam posuere" />
        </div>
    </section>
    <!-- end content -->
</template>
<script>
import SiteBtn from '../Button/SiteBtn.vue';

    export default {
        name: 'ContentVue',
        components:{
            SiteBtn
        }
    }
</script>