<template>
    <header>
        <h1>My Portfolio</h1>
        <ul id="buttons">
            <li><LinkButton link="/" text="Home"/></li>
            <li><LinkButton link="/projects" text="Projects"/></li>
            <li><LinkButton link="/about" text="About"/></li>
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
        min-height: 50px;
        justify-content: space-between;
        align-items: center;
        background-color: rgb(14, 111, 175);
    }
    #buttons{
        display: flex;
        margin-right: 4vw;
        list-style: none;
        height: 100%;
    }
    h1{
        font-family: "Roboto Condensed";
        margin-left: 4vw;
        color: whitesmoke;
    }
</style>