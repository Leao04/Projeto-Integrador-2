<template>
  <div>
    <div class="container">
      <div class="TextoChamada">
        <h3>Em nosso site você encontrara os jogos recém lançados e sua avaliações além dos próximos eventos geek.</h3>
      </div>
      <div class="video1">
        <iframe
          width="100%"
          height="415"
          src="https://www.youtube.com/embed/73kSvsQ_kkA"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>

      <div class="TextoCards">
        <h4>Os jogos mais bem avalidado de 2020</h4>
      </div>

      <div class="Cardss">
        <div class="uk-child-width-1-3@m uk-grid-small uk-grid-match" uk-grid>
          <div>
            <div class="uk-card uk-card-default uk-card-body card3">
              <h3 class="uk-card-title">
               <!-- <img
                  src="./src/componentes/img/logo.jpg"
                  width="100%"
                  height="200px"
                  alt=""
                  srcset=""
                > -->
              </h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
            </div>
          </div>
          <div>
            <div class="uk-card uk-card-default uk-card-body card3">
              <h3 class="uk-card-title">
              <!--  <img
                  src="./src/componentes/img/cards/logo.png"
                  width="100%"
                  height="200px"
                  alt=""
                  srcset=""
                >-->
              </h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.Lorem ipsum dolor sit amet, consectetur adipisicing elit.Lorem ipsum dolor sit amet, consectetur adipisicing elit.Lorem ipsum dolor sit amet, consectetur adipisicing elit.Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
            </div>
          </div>
          <div>
            <div class="uk-card uk-card-default uk-card-body card3">
              <h3 class="uk-card-title">
             <!--   <img
                  src="./src/componentes/img/logo.jpg"
                  width="100%"
                  height="200px"
                  alt=""
                  srcset=""
                > -->
              </h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                <br>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
              </p>
            </div>
          </div>
          <div class="BannerBGS"></div>
        </div>
      </div>
      <div class="TextoBGS">
        <h4>Evento - Brasil Game Show 2021</h4>
      </div>

      <div class="BannerBGS">
        <div class="ContainerBGS">
          <div class="FotoBGS">
            <!--<img src="./src/componentes/img/cards/god-of-war.png" width="100%" height="800px" alt srcset>-->
          </div>
          <div class="InfoBGS">
            <p>A Brasil Game Show é uma feira anual de videogames organizada pelo empresário Marcelo Tavares, atualmente realizada em São Paulo, Brasil. A feira é considerada a maior conferência do gênero em toda a América Latina.</p>
          </div>
          <div class="PrecosBGS">
            <p>Super ingresso individual R$78,00
              <br>Passaporte de R$237,00
              <br>Super ingresso R$395,00
            </p>
          </div>
        </div>
      </div>

      <div class="TextoLancamentos">
        <h4>PS5 Showcase Event Livestream</h4>
      </div>
      <div class="ProximosLancamentos">
        <iframe
          width="100%"
          height="415"
          src="https://www.youtube.com/embed/iG0G44G6RI8"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>
    </div>
  </div>
</template>

<script>
import Header from "../src/componentes/header";
export default {
  name: "home",
  components:{
      Header
  }

};
</script>
<style>
.container {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-gap: 10px;
  grid-auto-rows: repeat(30, auto);
}
.TextoChamada {
  grid-column: 1/5;
  grid-row: 1/1;
}
.video1 {
  grid-column: 1/5;
  grid-row: 2/4;
}
.TextoCards {
  grid-column: 1/5;
  grid-row: 4/6;
}
.Cardss {
  grid-column: 1/5;
  grid-row: 6/9;
}
.card3 {
  color: black;
  background-color: #c50000e7;
}

.TextoBGS {
  grid-column: 1/5;
  grid-row: 9/9;
}

.BannerBGS {
  grid-column: 1/5;
  grid-row: 10/12;
  background-color: #c50000e7;
}

.ContainerBGS {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 10px;
  grid-auto-rows: repeat(4, auto);
}

.FotoBGS {
  grid-column: 1/1;
  grid-row: 1/1;
  padding: 10px;
}

.InfoBGS {
  display: flex;
  grid-column: 2/2;
  grid-row: 1/1;
  text-align: center;
  align-items: center;
  color: black;
}

.PrecosBGS {
  padding-top: 80px;
  grid-column: 3/3;
  grid-row: 1/1;
  text-align: center;
  align-items: center;
  color: black;
}
.TextoLancamentos {
  grid-column: 1/5;
  grid-row: 13/13;
}
.ProximosLancamentos {
  grid-column: 1/5;
  grid-row: 14/16;
}

@media (max-width: 959px) {
  .BannerBGS {
    grid-column: 1/5;
    grid-row: 10/14;
  }

  .ContainerBGS {
    display: grid;
    grid-template-columns: repeat(1, 1fr);
    grid-gap: 10px;
    grid-auto-rows: repeat(3, auto);
  }

  .FotoBGS {
    grid-column: 1/1;
    grid-row: 1/1;
  }

  .InfoBGS {
    grid-column: 1/1;
    grid-row: 2/2;
  }

  .PrecosBGS {
    grid-column: 1/1;
    grid-row: 3/3;
    text-align: center;
    align-items: center;
  }

  .TextoLancamentos {
  grid-column: 1/5;
  grid-row: 14/14;
}
.ProximosLancamentos {
  grid-column: 1/5;
  grid-row: 15/17;
}
}
</style>