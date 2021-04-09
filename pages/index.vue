<template>
  <div class="page-wrap rounded-xl container">
    <h1>Starwars Responsive Fan Page</h1>

    <p>While maintaining the heirarchy of importance.</p>

    <article class="main-story">
      <img
        class="hero-image"
        src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.wallpaperup.com%2Fuploads%2Fwallpapers%2F2014%2F11%2F29%2F533542%2Fa37d9fa7a5a62031250fd7b75ec6c880-700.jpg&f=1&nofb=1"
        alt="Sha Ra Rocking"
        width="1000"
        height="400"
      />

      <div class="story-intro">
        <h1>The Millennium Falcon</h1>
        <p>
          Formerly known as the <i>Stellar Envoy</i>.
          <a
            href="https://starwars.fandom.com/wiki/Millennium_Falcon"
            >source.</a
          >
        </p>
      </div>
    </article>

    <section
      id="section-category"
      class="row sub-stories flex justify-center md:flex"
    >
      <article class="sub-story sm:flex-shrink-0">
        <img class="tile-image" src="https://starwars-fan-page.s3.us-east-2.amazonaws.com/cat-starwars-1.jpg" />
        <div class="story-intro">
          <h2>Photoshopped Ewok</h2>
          <p>A picture of an Ewok with a cat head.</p>
        </div>
      </article>

      <article class="sub-story sm:flex-shrink-0">
        <img
          class="tile-image"
          src="https://starwars-fan-page.s3.us-east-2.amazonaws.com/dog-starwars-1.jpg"
        />
        <div class="story-intro">
          <h2>Animal Cosplay</h2>
          <p>A picture of a dog doing StarWars Cosplay.</p>
        </div>
      </article>

      <article class="sub-story sm:flex-shrink-0">
        <img class="tile-image" src="https://starwars-fan-page.s3.us-east-2.amazonaws.com/dog-starwars-2.jpg" />
        <div class="story-intro">
          <h2>Animal Cosplay</h2>
          <p>A picture of a dog doing StarWars Cosplay.</p>
        </div>
      </article>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>
