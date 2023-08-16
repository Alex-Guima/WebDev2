<script setup lang="ts">
    /*const props = defineProps({
        
    })
    */
</script>

<template>
    <nav class="navbar">
        <div class="container">

            <ul>
                <li class="logo">
                    <h2>Valorant</h2>
                </li>

                <div class="other-pages">

                    <li class="about">About</li>
                    
                    <li class="login">Login</li>

                </div>
            </ul>
        </div>    
    </nav>
</template>

<style scoped>
    
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100;300;400;500;600;700;800;900&display=swap');

    * {
        margin: 0;
        padding: 0;
        font-family: 'Montserrat', sans-serif;
    }

    .navbar {
        display: flex;
        position: absolute;
        
    }

    .logo {
        display: inline;
        position: relative;
        float: left;
        
    }

</style>

