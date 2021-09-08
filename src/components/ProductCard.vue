<template>
    <div class="card mt-2">
        <img :src="comic.thumb" alt="comic.series">
        <h4>{{ comic.series }}</h4>
        <p>{{ comic.price }}</p>
    </div> 
</template>

<script>

export default {
    name: "ProductCard",
    props: ['comic']
    
}
</script>

<style>

</style>
