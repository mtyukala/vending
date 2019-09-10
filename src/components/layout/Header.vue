<template>
    <header class="header">
        <nav id="nav">
            <router-link to="/">Home</router-link>
            |
            <router-link to="/products">Products</router-link>
            |
            <router-link to="/coins">Coins</router-link>
            |
            <router-link to="/about">About</router-link>
        </nav>
        <h2>Vending Machine Demo</h2>
    </header>
</template>
<script>
    export default {
        name: "Header"
    }
</script>
<style scoped>
    header {
        text-align: center;
    }

    header a {
    }
</style>