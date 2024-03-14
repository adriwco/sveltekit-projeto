<script>
  import imgHome from '../assets/musculacao.jpg';
</script>

<section class="intro" style="background-image: url({imgHome})">
  <div class="intro__wrapper wrap">
    <h1>Você está pronto para o desafio?</h1>
    <p>
      Academia Local está pronta para te ajudar a chegar mais longe e alcançar
      sua melhor performance.
    </p>
    <a class="btn" href="/sobre">Modalidades</a>
  </div>
</section>

<style>
  .intro {
    min-height: 360px;
    background-size: cover;
    background-position: center;
    position: relative;
    z-index: 0;
  }
  .intro::after {
    content: '';
    position: absolute;
    inset: 0;
    background-color: rgba(0, 0, 0, 0.55);
    z-index: -1;
  }
  .intro__wrapper {
    z-index: 1;
    padding-top: 60px;
  }
  .intro__wrapper h1 {
    max-width: 300px;
    margin-bottom: 20px;
  }
  .intro__wrapper p {
    max-width: 450px;
    margin-bottom: 24px;
  }
</style>
