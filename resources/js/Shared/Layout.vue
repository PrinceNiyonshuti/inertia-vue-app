<template>
    <header class="flex">
        <h1 class="font-bold text-lg">My App</h1>
        <Nav />
    </header>
    <slot />
</template>
<script>
import Nav from "../Shared/Nav";
import Nav from "./Nav.vue";

export default {
    components: {
        Nav,

        Nav,
    },
};
</script>
