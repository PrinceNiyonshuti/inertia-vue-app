<template>
    <Nav />
    <h1>Hello , {{ name }}</h1>
    <p>In this series we will use :</p>
    <ul>
        <li v-for="framework of frameworks" v-text="framework"></li>
    </ul>
</template>
<script>
import Nav from "../Shared/Nav";

export default {
    components: {
        Nav,
    },
    props: {
        name: String,
        frameworks: Array,
    },
};
</script>
