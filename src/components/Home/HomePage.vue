<template>
    <div>
       <HeaderVue/>
       <InfoSection/>
    </div>
</template>

<script>
import HeaderVue from '@/components/Home/HeaderVue'
import InfoSection from '@/components/Info/InfoSection.vue'
    export default {
        name: 'HomePage',
        components: {
            HeaderVue,
            InfoSection
        }
    }
</script>