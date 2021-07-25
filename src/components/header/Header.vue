<template>
    <b-navbar class="b-navbar" toggleable="lg">
        <b-navbar-brand class="b-navbar-brand-color" href="#" >SpotInc</b-navbar-brand>
    </b-navbar>
</template>

<script>
    import { BNavbar } from 'bootstrap-vue'

    export default {
        name: "Header",

        components: {
            BNavbar
        }
    }
</script>

<style>
.b-navbar {
    background-color: var(--black-light-color);
    padding: var(--padding-y) var(--padding-x);
}
.b-navbar .b-navbar-brand-color,
.b-navbar .b-navbar-brand-color:hover {
    color: var(--white-color);
}

</style>