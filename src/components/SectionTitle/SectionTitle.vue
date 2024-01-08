<template>
    <div class="details">
        <h2>{{ heading }}</h2>
        <p>{{ msg }}</p>
    </div>
</template>

<script>
export default {
    name: "SectionTitle",
    props:{
        heading: String,
        msg: String
    }
}
</script>

