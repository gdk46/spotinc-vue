<template>
    <section id="musicSearch" >
        <div class="">
            <b-nav-form class="b-nav-form justify-content-md-center">
                <input class="b-form-input" type="text">
                <button class="b-button">
                    <i class='bx bx-search-alt-2'></i>
                </button>
            </b-nav-form>
        </div>
    </section>
</template>

<script>
    export default {
        name: "MusicSearch",
    }
</script>

<style>
#musicSearch {
    padding: var(--padding-y) var(--padding-x);
}

.b-nav-form {
    margin-top: 3rem;
}

@media (min-width: 720px) {
    .b-nav-form {
        margin-top: 7rem;
    }
}

.b-nav-form .b-form-input {
    width: 265px;
    height: 50px;
    padding-right: 10px;
    padding-left: 20px;
    border-radius: 30px;
    border: 1px solid var(--black-light-color);
    margin-right: 10px;
    outline: none;
    background-color: var(--black-light-color);
    color: var(--white-color);
}

@media (min-width: 600px) {
    .b-nav-form .b-form-input {
        width: 450px;
    }
}

@media (min-width: 720px) {
    .b-nav-form .b-form-input {
        width: 550px;
    }
}

.b-nav-form .b-button {
    width: 50px;
    height: 50px;
    padding-top: 2px;
    border-radius: 30px;
    border: 1px solid var(--primary-color);
    background-color: var(--primary-color);
    color: var(--white-color);
    line-height: 1;
    text-rendering: auto;
    display: inline-block;
    text-transform: none;
}

@media (min-width: 720px) {
    .b-nav-form .b-button {
        width: 75px;
        height: 50px;
    }
}

.b-nav-form .b-button i {
    font-size: 30px;
    color: var(--white-color);
}
</style>