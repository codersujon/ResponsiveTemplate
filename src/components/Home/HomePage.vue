<template>
    <div>
       <HeaderVue/>
       <InfoSection/>
       <ContentVue />
       <FooterVue />
    </div>
</template>

<script>
import HeaderVue from '@/components/Home/HeaderVue'
import InfoSection from '@/components/Info/InfoSection'
import ContentVue from '@/components/Content/ContentVue'
import FooterVue from '@/components/Footer/FooterVue'
    export default {
        name: 'HomePage',
        components: {
            HeaderVue,
            InfoSection,
            ContentVue,
            FooterVue
        }
    }
</script>