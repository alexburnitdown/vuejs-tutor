<template>
    <nav>
        <div class="nav-wrapper">
        <router-link to="/" class="brand-logo">Tasks</router-link>
        <ul class="right">
            <router-link tag="li" to="/" exact active-class="active">
                <a href="#">Create</a>
            </router-link>
            <router-link tag="li" to="/list" active-class="active">
                <a href="#">List</a>
            </router-link>
            
        </ul>
        </div>
    </nav>
</template>

<script>
export default {

}
</script>

<style>

</style>