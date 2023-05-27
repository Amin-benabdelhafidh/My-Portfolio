<template>
    <header>
        <h1>Amin Benabdelhafidh</h1>
        <ul>
            <li><LinkButton link="/" text="Home" class="button nav-link"/></li>
        
            <li><LinkButton link="/projects" text="Projects" class="button nav-link"/></li>          
        
            <li><LinkButton link="/about" text="About" class="button nav-link"/></li>          
        </ul>
    </header>      

</template>

<script>
    import LinkButton from './LinkButton'

    export default {
        name: 'Header',
        components: {
            LinkButton,
        }
    }
</script>

<style scoped>
    header{
        display: flex;
        height: 15vh;
        max-width: 100%;
        margin:0;
        padding: 0;
        align-items: center;
        align-content: center;
        background-color: rgb(14, 111, 175);
    }
    ul{
        display: flex;
        margin: 0;
        list-style: none; 
        width: auto;
        height: 100%;

    }
    .li{
        height: 100%;
    }
    h1{
        font-family: "Roboto Condensed";
        margin-left: 4%;
        color: whitesmoke;
        white-space: wrap;
        font-size: 30px;
    }
    @media screen and (max-width: 520px) {
        
    }
    @media screen and (max-width: 800px) {
        h1{
            font-size: 25px;
        }

    }
    
    
</style>