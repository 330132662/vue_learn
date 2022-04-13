<template>
    <div class="navbar navbar-default topnav">
        <div class="container">
            <div class="navbar-header">
                <a href="/" class="navbar-brand">
                    <span class="title">{{ logo.title }}</span>
                    <img :src="logo.src" :alt="logo.title">
                </a>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'TheHeader',
        data() {
            return {
                logo: {
                    src: `${this.uploadsUrl}/2022/03/20220319072818311.jpg`,
                    title: 'Learnku Vue.js'
                }
            }
        },
        beforeCreate() {
            this.uploadsUrl = 'https://oss.52car.xyz/'
        }
    }
</script>

<style scoped>
    .title { display: none;}
</style>