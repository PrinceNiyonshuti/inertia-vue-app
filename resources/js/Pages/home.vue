<template>
    <Nav />
    <h1 class="text-4xl font-bold">Hello , {{ name }}</h1>

</template>
<script>
import Nav from "../Shared/Nav";

export default {
    components: {
        Nav,
    },
};
</script>
