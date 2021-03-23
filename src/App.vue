<template>
  <Nav />
  <main>
    <Header title="Carrusel" />
    <Container />
    <Footer />
  </main>
</template>

<script>
import Nav from "./components/Nav";
import Header from "./components/Header";
import Container from "./components/Container";
import Footer from "./components/Footer";

export default {
  components: {
    Nav,
    Header,
    Container,
    Footer,
  }
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');
*{
  font-family: 'Montserrat', sans-serif;
  font-size: 14px;
  font-style: normal;
  font-weight: 300;
}

.bd-placeholder-img {
  font-size: 1.125rem;
  text-anchor: middle;
  -webkit-user-select: none;
  -moz-user-select: none;
  user-select: none;
}

@media (min-width: 768px) {
  .bd-placeholder-img-lg {
    font-size: 3.5rem;
  }
}
</style>
