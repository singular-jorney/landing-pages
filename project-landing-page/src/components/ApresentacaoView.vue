<template>
  <section>
    <div class="container-apresentacao">
      <div class="apresentacao">
        <div>
          <div class="nano">
            <h2>
              Bonjour, eu sou <b>Fabiana Nanô</b>
              <p>
                Professora de francês, amante da França, de arte, livros e
                vinhos
              </p>
            </h2>
            Sou brasileira, moro em São Paulo e ensino francês desde 2008.
            Comecei a dar aulas assim que voltei da França. Lá, realizei um
            intercâmbio universitário em Lyon, uma cidade maravilhosa conhecida
            por sua gastronomia e belas paisagens. Voltei para o Brasil, e desde
            então descobri a minha grande paixão: ensinar esta língua que eu amo
            tanto. Ao longo desses anos, tive contato com centenas de alunos e
            pude perceber o que funciona de verdade para eles falarem francês de
            forma fluída e prazerosa. Reuni neste curso as principais técnicas
            para você dar os primeiros passos nesta língua charmosa e conseguir
            se comunicar em francês
          </div>

          de forma satisfatória.
        </div>
        <div>
          <img
            class="fotoNano"
            src="https://fabiananano.com/wp-content/uploads/2022/02/Fabiana-nano-min-min.webp"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ApresentacaoView",
};
</script>

<style>
.nano {
  font-family: "Poppins", Sans-serif;
  font-weight: 500;
  letter-spacing: 0.4px;
  max-width: 480px;
}
h2 {
  font-size: 1.5em;
  margin-block-start: 0.83em;
  margin-block-end: 0.83em;
  margin-inline-start: 0px;
  margin-inline-end: 0px;
}

p {
  display: block;
  margin-block-start: 1em;
  margin-block-end: 1em;
  margin-inline-start: 0px;
  margin-inline-end: 0px;
}
.container-apresentacao {
  background-color: #f2f2f2;
}
.apresentacao {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  max-width: 960px;
  justify-content: center;
  margin: 0 auto;
}
.fotoNano {
  max-width: 360px;
}
</style>