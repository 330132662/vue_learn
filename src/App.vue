<template>
    <div class="container">
        <TheHeader/>
        <div class="jumbotron">
            <div class="container">
                <h1>Welcome from Bootstrap</h1>
                <p>This is a simple hero unit, a simple jumbotron-style component for calling extra attention to
                    featured content or information.</p>
                <p><a class="btn btn-primary btn-lg" href="http://www.bootcss.com/" role="button" target="_blank">Learn
                    more <span class="glyphicon glyphicon-hand-right" aria-hidden="true"></span></a></p>
            </div>
        </div>
    </div>
</template>

<script>
    import TheHeader from "@/components/TheHeader";

    export default {
        name: 'App',
        components: {TheHeader},
    }
</script>

<style lang="scss">
    @import "./styles/main";
    @import "./styles/extra";

    body > .container {
        margin-top: 15px;
    }

    $container-large-desktop: 1200px;
    $btn-primary-bg: #00b5ad;
    $btn-primary-border: #00b5ad;
    $label-primary-bg: #00b5ad;
    $pagination-active-bg: #00b5ad;
    $pagination-active-border: #00b5ad;
    $pagination-color: #00b5ad;
    $input-border-focus: #00b5ad;
    $link-color: #12c4c5;
    $link-hover-color: #22ddde;
    $icon-font-path: "~bootstrap-sass/assets/fonts/bootstrap/";
    $fa-font-path: "~font-awesome/fonts/";
     /*@import "~bootstrap-sass/assets/stylesheets/_bootstrap";*/
     @import "~font-awesome/scss/font-awesome";
</style>