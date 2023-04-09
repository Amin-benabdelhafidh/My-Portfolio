<template>
    <h1>My Portfolio</h1>
    <h3>Version: <span>1.0.0</span></h3>
    <h6>Developed by&ensp;<a href="https://github.com/Amin-benabdelhafidh">Amin Ben Abdelhafidh</a></h6>
</template>

<script>
    export default{
        name: 'About',
    }
</script>

<style scoped>
    h1 ,h3, h6{
        font-family: "Roboto Condensed";
    }
    h1{
        font-size: 50px;
        color: rgb(14, 111, 175);
    }
    h3{
        font-size: 30px;
        color: black;
    }
    span{
        color: rgb(14, 111, 175);
        font-family: monospace;
        font-size: 35px;
    }
    h6{
        font-size: 15px;
        color: black;
    }
    a{
        text-decoration: none;
        color: rgb(61, 158, 223);
        font-size: 16px;
    }
</style>