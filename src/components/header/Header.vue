<template>
    <b-navbar class="b-navbar" toggleable="lg">
        <b-navbar-brand class="b-navbar-brand-color" href="#" >SpotInc</b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>

            <b-navbar-nav class="ml-auto">
                <b-nav-item class="b-nav-item" href="#">Log in</b-nav-item>
            </b-navbar-nav>
        </b-collapse>
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
    background-color: var(--primary-color);
    padding: var(--padding-y) var(--padding-x);
}
.b-navbar .b-navbar-brand-color,
.b-navbar .b-navbar-brand-color:hover {
    color: var(--white-color);
}

.b-nav-item,
.b-nav-item:active {
    color: var(--white-light-color);
}
</style>