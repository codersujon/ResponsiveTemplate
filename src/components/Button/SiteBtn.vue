<template>
    <button type="button" class="btn btn-primary">{{ btnName }}</button>
</template>

<script>
export default {
    name: 'SiteBtn',
    props:{
        btnName:String
    }
}
</script>