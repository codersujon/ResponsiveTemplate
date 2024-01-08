<template>
    <div>
       <HeaderVue/>
       <InfoSection/>
       <ContentVue />
       <FooterVue />
    </div>
</template>

<script>
import HeaderVue from '@/layouts/Header/HeaderVue'
import InfoSection from '@/components/Info/InfoSection'
import ContentVue from '@/components/Content/ContentVue'
import FooterVue from '@/layouts/Footer/FooterVue'
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