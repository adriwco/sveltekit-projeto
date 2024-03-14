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
    display: grid;
    align-content: center;
    justify-content: start;
    position: relative;
  }
  .intro::after {
    content: '';
    position: absolute;
    inset: 0;
    background-color: rgba(0, 0, 0, 0.55);
  }
  .intro__wrapper {
    z-index: 1;
  }
  .intro__wrapper h1 {
    max-width: 300px;
  }
  .intro__wrapper p {
    max-width: 450px;
  }
  .btn {
    margin-top: 24px;
  }
</style>
