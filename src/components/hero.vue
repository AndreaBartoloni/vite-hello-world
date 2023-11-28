<script>

</script>

<template>
    <div class="hero">
        <div class="overlay">
            <h1>La mia prima app con Vite!</h1>
        </div>
        
    </div>
    
    
</template>

<style scoped>
.hero{
    background-image: url(17670.jpg);
    height: calc(100vh - 40px);
    background-position: center;
    background-size: cover;

}
.overlay{
    background-color: rgba(0,0,0,0.5);
    height: calc(100vh - 40px);
    width: 100%;
    display:flex;
    align-items: center;
    justify-content: center;
}
h1{
    margin: 0;
}
</style>