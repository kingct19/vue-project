<template>
    <header class="header">
        <nav class="navbar">
       
            <div class="logo">
            <router-link to="/" class="logo-link">Your Name</router-link>
            </div>
            
            <ul class="nav-menu">
                <li class="nav-item">
                    <router-link to="/" class="nav-link">Home</router-link>
                </li>

                <li class="nav-item">
                    <router-link to="/about" class="nav-link">About</router-link>
                </li>

                <li class="nav-item">
                    <router-link to="/projects" class="nav-link">Projects</router-link>
                </li>

                <li class="nav-item">
                    <router-link to="/contact" class="nav-link">Contact</router-link>
                </li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style scoped>
header {
    background-color: #333;
    color: white;
    padding: 1rem 2rem;
}



</style>