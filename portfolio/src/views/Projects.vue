<template>
    <div v-for="project in projects" class="project container">
      <img src="" class="img-fluid" alt="#">
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