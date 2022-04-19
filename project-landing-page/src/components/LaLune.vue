<template>
  <section class="container-la-lune">
    <div class="circulo">
      <div class="texto-la-lune">
        <h2>Você também ama a língua francesa?</h2>
        <h2>
          Já se imaginou viajando, morando ou estudando na França <br />e
          conseguindo se comunicar sem dificuldade neste país lindo
        </h2>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "LaLune",
};
</script>

<style>
.container-la-lune {
  display: flex;
  align-items: center;
  width: 100%;
  height: 380px;
  background: url("@/assets/paris.jpg") no-repeat center;
  background-size: cover;
}

.circulo {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 50em;
  height: 10em;
  background-color: white;
  opacity: 70%;
  margin: 0 auto;
}
.texto-la-lune {
  color: black;
  font-family: "Poppins", Sans-serif;
  font-size: 1vw;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  flex-wrap: wrap;
}
@media (max-width: 800px) {
  .texto-la-lune {
    font-size: 2vw;
  }
}
</style>

