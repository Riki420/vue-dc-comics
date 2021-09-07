<template>
    <header>
        <div class="header-top"></div>
        <div class="container">
            <div class="header-bottom">
                <figure>
                    <img src="../assets/img/dc-logo.png" alt="DC-logo">
                </figure>
                <ul class="main-nav">
                    <li 
                    v-for="(item, index) in menu" 
                    :key="index">
                        <a href="link.url" 
                        :class="{'active' : item.current}">
                            {{ item.text }}
                        </a>
                     </li>
                </ul>
            </div>
        </div>
        
    </header>
</template>

<script>
export default {
    name: "Header",
    data(){
        return{
            menu: [
                {
                    text: 'Characters',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Comics',
                    url: '#',
                    current: true,
                },
                {
                    text: 'Movies',
                    url: '#',
                    current: false,
                },
                {
                    text: 'TV',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Games',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Collectibles',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Videos',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Fans',
                    url: '#',
                    current: false,
                },
                {
                    text: 'News',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Shop',
                    url: '#',
                    current: false,
                },
]

        }
    }
}
</script>

<style lang="scss">
    
</style>