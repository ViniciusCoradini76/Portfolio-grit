<template>
  <body>
    <h1 class="animacaoScroll" id="titulo-portfolio"><u>PORTFOLIO</u></h1>
    <div class="container">
      <div class="animacaoScroll" ><img src="/img/tunelDesenho.jpg" alt="Contracultura" /></div>
      <div>
        <h1 class="animacaoScroll">Contracultura</h1>
        <br />
        <p class="animacaoScroll">
          Este álbum de fotografia foi criado para A margem.<br />O álbum
          apresenta uma seleção de fotos que capturam a beleza<br />e a essência
          do tema. As fotos foram cuidadosamente selecionadas<br />
          e editadas para criar um álbum coeso e visualmente atraente. O álbum
          está disponível em formato físico e digital.
        </p>
      </div>
    </div>
    <div class="container">
      <div>
        <h1 class="animacaoScroll">A Busca pela Luz</h1>
        <br />
        <p class="animacaoScroll">
          Cada imagem é uma narrativa em si mesma, tecendo uma tapeçaria de
          solidão, introspecção e esperança. A luz e a sombra se entrelaçam em
          um delicado equilíbrio, criando uma atmosfera de quietude
          contemplativa que convida o espectador a se conectar com a sua própria
          interioridade.
        </p>
      </div>
      <div class="imagem-direita" ><img src="/img/PessoaEscuro.jpg" alt="Contracultura" /></div>
    </div>
    <div class="container">
      <div><img class="animacaoScroll" src="/img/metro.jpg" alt="Contracultura" /></div>
      <div>
        <h1 class="animacaoScroll">Monocromia</h1>
        <br />
        <p class="animacaoScroll">
          A primeira foto nos leva para dentro de uma estação vazia, banhada por
          uma luz artificial que cria longas sombras e formas geométricas. A
          ausência de cor intensifica a sensação de quietude e introspecção,
          convidando o espectador a se conectar com a própria interioridade.
        </p>
      </div>
    </div>
    <div class="container">
      <div>
        <h1 class="animacaoScroll">Para os Galhos</h1>
        <br />
        <p class="animacaoScroll">
          A primeira foto nos leva para dentro de uma floresta, onde um único
          galho se estende em direção ao céu. A textura áspera da casca e os nós
          proeminentes contam histórias de anos de crescimento e resistência. A
          simplicidade da imagem é ao mesmo tempo poderosa e evocativa.
        </p>
      </div>
      <div class="imagem-direita"><img src="/img/galhos.jpg" alt="Contracultura" /></div>
    </div>
  </body>
</template>


<script>

ScrollReveal().reveal( '.animacaoScroll' )

export default {
  name: "Portfolio",
};
</script>

<style scoped>
body {
  margin-left: 15%;
  margin-right: 15%;
  margin-top: 50px;
}

#titulo-portfolio {
  text-align: center;
  margin: 100px;
}

img {
  width: 400px;
  height: 228px;
  border: 5px solid #262625;
}

div img  {
  margin-bottom: 80px;
}

.imagem-direita {
text-align: right;}



</style>
