<template>
    <div class="container">
        <app-header></app-header>
        <hr>
        <div class="row">
            <app-Server></app-Server>
            <app-ServerDetails></app-ServerDetails>
        </div>
        <hr>
        <app-Footer></app-Footer>
    </div>
</template>

<script>
    import Header from './components/shared/Header.vue';
    import Footer from './components/shared/Footer.vue';
    import Server from './components/Server/Server.vue';
    import ServerDetails from './components/Server/ServerDetails.vue';

    export default {
        components: {
            'app-header': Header,
            'app-Footer': Footer,
            'app-Server': Server,
            'app-ServerDetails': ServerDetails
        }
    }
</script>

<style>

</style>
