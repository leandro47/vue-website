<template>
  <section>
      <div class="container">
          <HcodeSectionNewsIndividual 
          img-name="news1.jpg"
          img-info="Noticia 1"
          news-title="Começa os treinos para a nova temporada"
          news-content="Lorem ipsum dolor, sit amet consectetur adipisicing elit. Minus deserunt
          quibusdam iusto, dignissimos dolore officiis libero voluptates eum non
          velit veritatis maiores fugit nobis, magnam molestias in quod labore
          alias? Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsa
          aperiam soluta expedita molestiae neque doloribus ad deleniti libero
          cupiditate, iusto dolore. Expedita ad blanditiis officiis culpa
          quibusdam laudantium facere fuga?"
          news-date="01/01/2021"
          />
          <HcodeSectionNewsIndividual 
          img-name="news2.jpg"
          img-info="Noticia 2"
          news-title="jogo de quarta-feira termina empatado"
          news-content="Lorem ipsum dolor, sit amet consectetur adipisicing elit. Minus deserunt
          quibusdam iusto, dignissimos dolore officiis libero voluptates eum non
          velit veritatis maiores fugit nobis, magnam molestias in quod labore
          alias? Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsa
          aperiam soluta expedita molestiae neque doloribus ad deleniti libero
          cupiditate, iusto dolore. Expedita ad blanditiis officiis culpa
          quibusdam laudantium facere fuga?"
          news-date="07/01/2021"
          />
          <HcodeSectionNewsIndividual 
          img-name="news3.jpg"
          img-info="Noticia 3"
          news-title="A inauguração do novo estadio sera na semana que vem"
          news-content="Lorem ipsum dolor, sit amet consectetur adipisicing elit. Minus deserunt
          quibusdam iusto, dignissimos dolore officiis libero voluptates eum non
          velit veritatis maiores fugit nobis, magnam molestias in quod labore
          alias? Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsa
          aperiam soluta expedita molestiae neque doloribus ad deleniti libero
          cupiditate, iusto dolore. Expedita ad blanditiis officiis culpa
          quibusdam laudantium facere fuga?"
          news-date="20/01/2021"
          />
      </div>
  </section>
</template>

<script>

import HcodeSectionNewsIndividual from "./HcodeSectionNewsIndividual";
export default {
  components: {
    HcodeSectionNewsIndividual,
  }
}

</script>

<style scoped>
section {
    padding: 50px 0;
    margin-top: 25px;
    background-color: #F37520
}
</style>