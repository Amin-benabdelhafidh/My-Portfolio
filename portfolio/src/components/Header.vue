<template>
    <header>
        <h1>Amin Benabdelhafidh</h1>
        <ul id="buttons">
            <li class="li"><LinkButton link="/" text="Home" class="button"/></li>
            <li class="li"><LinkButton link="/projects" text="Projects" class="button"/></li>
            <li class="li"><LinkButton link="/about" text="About" class="button"/></li>
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
        width: 100%;
        min-height: 50px;
        margin:0;
        padding: 0;
        justify-content: space-between;
        align-items: center;
        align-content: center;
        background-color: rgb(14, 111, 175);
    }
    #buttons{
        display: flex;
        margin: 0;
        list-style: none; 
        margin-bottom: 0;
        height: 100%;

    }
    .li{
        height: 100%;
        width: 27%;
    }

    @media screen and (max-width: 600px) {
        h1 {
            font-size: 20px;
        }
        .buttons{
            font-size: 15px;
        }
    }
    .button{
        height: 100%;
    }
    h1{
        font-family: "Roboto Condensed";
        margin-left: 4%;
        color: whitesmoke;
        white-space: nowrap;
    }
</style>