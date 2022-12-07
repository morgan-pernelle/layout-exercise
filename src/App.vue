<script setup>

</script>

<!-- ----------------------------------------------------------------------------------------------------------------------------- -->

<template>

  <nav>
    <div id="nav-logo-section" class="nav-section">
      <a href="#">
        <i class="fa-solid fa-dumpster-fire"></i>
      </a>
    </div>
    <div id="nav-link-section" class="nav-section">
      <a href="#">ABOUT</a>
      <a href="#">WORK</a>
    </div>
    <div id="nav-social-section" class="nav-section">
      <a href="#">
        <i class="fa-brands fa-twitter"></i>
      </a>
      <a href="#">
        <i class="fa-brands fa-youtube"></i>
      </a>
      <a href="#">
        <i class="fa-brands fa-codepen"></i>
      </a>
    </div>
    <div id="nav-contact-section" class="nav-section">
      <a href="#">GET IN TOUCH</a>
    </div>
  </nav>

  <main>
    <article>
      <div class="article-image-section article-section"></div>
      <div class="article-description-section article-section">
        <p class="article-description">
          La petite Chihiro accompagne ses parents dans une promenade sylvestre qui doit les conduire vers leur nouvelle maison en banlieue. Alors qu'elle prend un raccourci à travers un tunnel peu emprunté, la petite famille se retrouve soudain en territoire inconnu. Le temps de retrouver leur chemin, ils font une halte dans un gigantesque restaurant en plein air, totalement déserté.
        </p>
      </div>
      <div class="article-title-section article-section">
        <h2 class="article-title">LE VOYAGE DE CHIHIRO</h2>
        <i class="fa-solid fa-plus"></i>
      </div>
      <div class="article-nav-section article-section"></div>
    </article>
    <!-- <article></article> -->
    <!-- <article></article> -->
    <!-- <article></article> -->
  </main>

</template>

<!-- ----------------------------------------------------------------------------------------------------------------------------- -->

<style scoped>

nav {
  display: flex;
  width: 100%;
  border-bottom: 1px solid var(--border-color);
}

nav > .nav-section {
  padding: 3rem 2rem;
  display: flex;
  gap: 1rem;
  border-left: 1px solid var(--border-color);
  align-items: center;
  justify-content: center;
}

#nav-logo-section {
  justify-content: flex-start;
}

#nav-logo-section > a > i {
  font-size: 2.5rem;
}

#nav-logo-section,
#nav-link-section {
  flex-basis: calc(100% / 3);
}

#nav-link-section {
  gap: 6rem;
}

#nav-social-section {
  gap: 3rem;
}

#nav-social-section,
#nav-contact-section {
  flex-grow: 1;
}

main {
  height: 100%;
}

main > article {
  display: grid;
  height: 100vh;
  grid-template-columns: 2fr 1fr;
  grid-template-rows: 2fr 1fr;
}

main > article > .article-section {
  height: 100%;
}

main > article > .article-description-section,
main > article > .article-nav-section {
  border-left: 1px solid var(--border-color);
}

main > article > .article-title-section,
main > article > .article-nav-section {
  border-top: 1px solid var(--border-color);
}

main > article > .article-image-section {
  background-image: url(./assets/images/Chihiro-1.jpg);
  background-size: cover;
  background-position: center;
}

main > article > .article-description-section {
  padding: 3rem 2rem;
  display: flex;
  align-items: flex-end;
  justify-content: flex-end;
}

main > article > .article-description-section > .article-description {
  color: lightgray;
  font-size: 1.1rem;
  text-align: justify;
}

main > article > .article-title-section {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
}

main > article > .article-title-section > .article-title {
  font-size: 4rem;
  font-weight: 700;
  color: lightgray;
  margin-left: 2rem;
}

main > article > .article-title-section > i {
  font-size: 2rem;
  color: lightgray;
  margin: 4.7rem 2rem 0 0;
}

</style>
 