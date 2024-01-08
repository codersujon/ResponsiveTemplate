<template>
    <!-- Start info -->
    <section class="info text-center">
        <div class="container">
            <SectionTitle 
                heading="Feugiat lorem ipsum dolor sed veroeros"
                msg="Donec leo, vivamus fermentum nibh in augue praesent a lacus at uma congue"
            />
            <div class="row">
                <ServiceItem  
                    message="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima, praesentium iure!
                    Harum, delectus officia quas numquam rem voluptatem magni nam. Facilis nam placeat recusandae!
                    Fugiat illo esse numquam iste atque!"
                /> 
                <ServiceItem 
                    message="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima, praesentium iure!
                    Harum, delectus officia quas numquam rem voluptatem magni nam. Facilis nam placeat recusandae!
                    Fugiat illo esse numquam iste atque!"
                />  
                <ServiceItem 
                    message="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima, praesentium iure!
                    Harum, delectus officia quas numquam rem voluptatem magni nam. Facilis nam placeat recusandae!
                    Fugiat illo esse numquam iste atque!"
                />   
            </div>
        </div>
    </section>

    <!--End info-->
</template>

<script>
    import SectionTitle from '@/components/SectionTitle/SectionTitle'
    import ServiceItem from '@/components/Info/ServiceItem'

    export default {
        name: 'InfoSection',
        components: {
            SectionTitle,
            ServiceItem
        }
    }
</script>