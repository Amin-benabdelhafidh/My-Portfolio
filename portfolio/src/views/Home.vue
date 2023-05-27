<template>
  <div class="page">
    <div class="container">
      <div class="typed-out">Hello, World!</div>
    </div>
    <h2>I'm <a href="https://github.com/Amin-benabdelhafidh">Amin Benabdelhafidh</a> and this is my portfolio website.</h2>
  </div> 

</template>

<script>
    export default{
        name: 'Home',
      
    }
</script>

<style scoped>
  h1{
    font-family: monospace;
    color: rgb(14, 111, 175);
  }
  .container{
      display: inline-block;
      width: auto;
      margin: 5px;
      margin-bottom: 5vh !important;
      
    }
    .page{
      width: 100%;
      font-family: monospace;
    }
    h2{
      margin: 5px;
    }
    .typed-out{
      
      overflow: hidden;
      font-size: 40px;
      border-right: .15em solid rgb(61, 158, 223);
      white-space: nowrap;
      animation: 
      typing 1.5s steps(20, end) forwards;
      width: 0;
    }
    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }
    a{
        text-decoration: none;
        color: rgb(61, 158, 223) !important;
        
    }
</style>