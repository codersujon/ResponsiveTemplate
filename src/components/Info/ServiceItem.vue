<template>
    <div class="col-lg-4">
        <i class="fa fa-cogs"></i>
        <p class="text">{{ message }}</p>
        <SiteBtn btnName="More Info"/>
    </div>
</template>

<script>
import SiteBtn from '@/components/Button/SiteBtn'
    export default {
        name: "ServiceItem",
        props:{
            message: String
        },
        components:{
            SiteBtn
        }
    }
</script>