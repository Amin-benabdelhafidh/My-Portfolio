<template>
    <div v-for="project in projects" class="project container">
      <div id="carouselExampleAutoplaying" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="img4.png" class="d-block w-100" alt="#">
          </div>
        <div class="carousel-item active">
          <img src="img1.png" class="d-block w-100" alt="#">
        </div>
        <div class="carousel-item active">
          <img src="img2.png" class="d-block w-100" alt="#">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
      
      <h3>{{project.title}}</h3>
      <p>{{ project.description }}</p>
    </div>
</template>

<script>
    export default{
        name: 'Projects',
        data(){
    return{
      projects: [],
    }
  },
  created(){
   this.projects = [
    {
      id:1,
      title: 'Wiki',
      description: 'A wikipedia-like website made with python using the Django framework.',
    },
    {
      id:2,
      title: 'Commerce',
      description: 'An e-commerce website made with python using the Django framework.',
    },
    {
      id:2,
      title: 'Social Network',
      description: 'A social network website made with python using the Django framework.',
    },
  ]
  }
    }
</script>