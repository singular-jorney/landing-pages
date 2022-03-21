<template>
  <section class="container-introducao">
    <div class="introducao">
      <h2>Querido.a amante da língua francesa,</h2>
      <br />
      <br />
      <h3>
        Se você quer falar francês em 2022, mas não tem ideia de por onde
        começar...
        <br />
        <br />
        Se você está cansado.a de procrastinar seus estudos por falta de rotina
        ou de uma mentora que te guie...
        <br />
        <br />
        Se você quer aprender a se expressar em francês com a pronúncia correta
        e seguindo um método claro, leve, dinâmico e prático...
        <br />
        <br />
        <i>Então você chegou ao lugar certo!</i>
        <br />
        <br />
        No curso <b>Francês em 3 Meses</b> eu vou te ensinar o método mão na
        massa para você aprender a se comunicar em francês com uma boa
        pronúncia, mesmo que você nunca tenha estudado ou ache uma língua
        difícil. ue
      </h3>
    </div>
  </section>
</template>

<script>
export default {
  name: "IntroducaoView",
};
</script>

<style>
.container-introducao {
  background-color: #f7f8f9;
}
.introducao {
  max-width: 960px;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  text-align: center;
  margin: auto;
  flex-direction: column;
}
.introducao h3 {
  color: #212529cc;
  font-family: "Lato", Sans-serif;
  font-size: 1em;
  font-weight: 400;
  line-height: 28px;
  letter-spacing: 0.6px;
}

.introducao h2 {
  color: #141414;
  font-family: "Poppins", Sans-serif;
  font-size: 1.5em;
  font-weight: 800;
  letter-spacing: 0.4px;
}
</style>