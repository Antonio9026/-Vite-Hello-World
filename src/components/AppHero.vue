<script>
export default {
    name: "AppHero",
    Data() {

    },
    methods: {

    },
}
</script>


<template>
    <div class="heroContainer">
        <div class="jumbotron">
            <h1>Junbotron title</h1>
            <p><strong>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis animi aspernatur ipsam accusantium, amet id dolorem totam? Nam saepe rerum numquam eos blanditiis minima suscipit illo, totam, reiciendis, fuga ipsam?</strong></p>
            <button>submit</button>
        </div>
    </div>
</template>

<style>
.heroContainer{
  
    background-image: url(https://theinformant.co.nz/wp-content/uploads/2021/02/Vitejs-a-quick-builder-of-Vuejs-forge.jpeg);
    background-position:center;
   background-repeat: no-repeat;
    background-size:cover;
   
   
}
.jumbotron{
     width: 80%;
     margin: 0 auto; 
}

button{
    margin-bottom: 20px;
}
</style>
