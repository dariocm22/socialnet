<template>
    <div class="posts">
        <img src="../assets/img/Logo-qci.svg" alt="qcibook" class="logo">
        <CardComp 
        class="mt-2 mx-auto single-post"
        parrafo="Saludos desde Barcelona" 
        :header="{ name: 'Maikol Yacson', picture: 'https://randomuser.me/api/portraits/men/51.jpg' }"
        :likes="true"
        picture="https://images.pexels.com/photos/13043589/pexels-photo-13043589.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"/>
        <CardComp 
        class="mt-2 mx-auto single-post"
        parrafo="La minerva de Guadalajara B)"
        :header="{ name: 'Enrique Estilos', picture: 'https://randomuser.me/api/portraits/men/61.jpg' }"
        :likes="true"
        picture="https://images.pexels.com/photos/8998769/pexels-photo-8998769.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"/>
    </div>
</template>

<script>
    import CardComp from "../components/CardComp.vue"
    export default {
        name: "PostsView",
        components: {
            CardComp
        }
    }

</script>
    
<style>
  .posts{
    min-height: 60vh;
    max-width: 895px;
    margin: auto;
  }
  .logo {
    max-width: 140px;
    padding: 0.2rem;
  }
  .single-post{
    max-width: 550px;
  }
</style>