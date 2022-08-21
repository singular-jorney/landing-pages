<template>
  <section class="home">
    <h1>Fale francês em três meses</h1>
    <div>
      <blockquote class="quote-externo">
        <p>Mesmo que você não saiba nada ou ache uma língua difícil.</p>
      </blockquote>
    </div>
  </section>
</template>

<script>
export default {
  name: "TopoView",
};
</script>

<style>
* {
  box-sizing: border-box;
}

body,
h1,
h2,
p,
ul,
li,
a {
  margin: 0px;
  padding: 0px;
}
.home h1 {
  font-size: 3em;
  color: white;
  font-weight: bold;
  text-transform: uppercase;
}

.quote-externo {
  max-width: 500px;
  margin: 0 auto;
  color: white;
}

.quote-externo p:before,
.quote-externo p:after {
  content: "";
  display: block;
  width: 3em;
  height: 0.3em;
  background: white;
  margin: 10px auto;
}

.home {
  text-align: center;
  width: 100%;
  height: 380px;
  background: url("@/assets/2.jpg") no-repeat center;
  background-size: cover;
  opacity: 90%;
}

.home h1 {
  color: #ffffff;
  font-family: "Poppins", Sans-serif;
  font-size: 3vw;
  font-weight: 700;
  letter-spacing: 1.1px;
  padding-top: 150px;
}

@media (max-width: 767px) {
  .home {
    text-align: center;
    width: 100%;
    height: 200px;
    background: url("@/assets/2.jpg") no-repeat center;
    background-size: contain;
  }
  .home h1 {
    color: #ffffff;
    font-family: "Poppins", Sans-serif;
    font-size: 3vw;
    font-weight: 700;
    letter-spacing: 1.1px;
    padding-top: 150px;
  }
}
</style>