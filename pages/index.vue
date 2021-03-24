<template>
  <div class="page-wrap rounded-xl container">
    <h1>Responsive Page</h1>

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
        <h1>Most Important Story</h1>
        <p>
          This article has the most visual weight.
          <a
            href="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.wallpaperup.com%2Fuploads%2Fwallpapers%2F2014%2F11%2F29%2F533542%2Fa37d9fa7a5a62031250fd7b75ec6c880-700.jpg&f=1&nofb=1"
            >image source.</a
          >
        </p>
      </div>
    </article>

    <section class="sub-stories flex justify-center">
      <article class="sub-story">
        <img class="tile-image" src="http://placekitten.com/250/350" />
        <div class="story-intro">
          <h2>Less Important Story</h2>
          <p>This story has less visual weight.</p>
        </div>
      </article>

      <article class="sub-story">
        <img
          class="tile-image"
          src="https://starwars-fan-page.s3.us-east-2.amazonaws.com/dog-starwars-1.jpg"
        />
        <div class="story-intro">
          <h2>Less Important Story</h2>
          <p>This story has less visual weight.</p>
        </div>
      </article>

      <article class="sub-story last">
        <img class="tile-image" src="http://placebear.com/250/350" />
        <div class="story-intro">
          <h2>Less Important Story</h2>
          <p>This story has less visual weight.</p>
        </div>
      </article>
    </section>
    <!-- New Section -->
    <section class="row">
      <div class="col-lg-4">
        <img class="tile-image" src="http://placekitten.com/250/350" />
        <div class="story-intro">
          <h2>Less Important Story</h2>
          <p>This story has less visual weight.</p>
        </div>
      </div>
      <div class="col-lg-4">
        <img
          class="tile-image"
          src="https://starwars-fan-page.s3.us-east-2.amazonaws.com/dog-starwars-1.jpg"
        />
        <div class="story-intro">
          <h2>Less Important Story</h2>
          <p>This story has less visual weight.</p>
        </div>
      </div>
      <div class="col-lg-4">
        <img class="tile-image" src="http://placebear.com/250/350" />
        <div class="story-intro">
          <h2>Less Important Story</h2>
          <p>This story has less visual weight.</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>
