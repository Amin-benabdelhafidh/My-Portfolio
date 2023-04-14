<template>
    <footer>
        <h6>Copyright &copy; 2023</h6>
    </footer>
</template>

<script>
    export default{
        name: 'Footer',
    }
</script>

<style scoped>
    footer{
        height: 5vh;
        position: fixed;
        left: 0;
        bottom: 0;
        width: 100%;
        background-color: rgba(207, 207, 207, 0.616);
    }
    h6{
        margin-top: 1vh;
    }
</style>