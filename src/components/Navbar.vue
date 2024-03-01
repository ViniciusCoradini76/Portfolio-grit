<template>
  <div id="navbar">
      <img
    src="/home/vinicius/projetoVUE/PortfolioProfissional/public/icone.ico"
    alt="LOGO"/>
    <router-link to="">Portfólio</router-link>
    <router-link to="">Serviços</router-link>
    <router-link to="">Contatos</router-link>
    <p></p>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
div {
  display: flex;
  justify-content: flex-end;
  background-color: transparent;
  padding: 20px;
  align-items: center;
   position: fixed;
  top: 0;
  width: 98%; /* Garante que a navbar se estenda por toda a largura */
  z-index: 10; /* Define um z-index mais alto para garantir que fique na frente */
}

 div img {
  height: 48px;
  width: 48px;
  margin: auto;
  margin-left: 0;

}

div a {
  margin-left: 20px;
  text-decoration: none;
  color: white;
  transition: 0.5s; 
}

div a:hover{
 border: 2px solid white;
   padding: 3px;
}
</style>
