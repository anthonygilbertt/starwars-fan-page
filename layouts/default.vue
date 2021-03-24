<template>
  <div>
    <Nuxt />
    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.0.4/tailwind.min.css"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.5.0/css/bootstrap.min.css"
    />
  </div>
</template>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

* {
  box-sizing: border-box;
}
body {
  background-image: url("https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.pixelstalk.net%2Fwp-content%2Fuploads%2F2016%2F04%2FStars-wallpaper-HD-desktop.jpg&f=1&nofb=1");
  color: #08e8de !important;
}

.page-wrap {
  width: 800px;
  margin: 20px auto;
  border-color: #08e8de;
  border-width: 2px;
}

.main-story {
  position: relative;
  margin: 0 0 25px 0;
}

img {
  display: block;
}

a {
  color: lightblue;
}

.story-intro {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  background: rgba(0, 0, 0, 0.75);
  padding: 20px;
  color: white;
}

h1 {
  font-size: 4em;
}
h1,
h2 {
  margin: 0 0 10px 0;
}

.story-intro h1 {
  font-size: 2.5em;
}
.story-intro p {
  margin: 0;
}

.sub-stories {
  overflow: hidden;
  margin: 0 0 25px 0;
}

.sub-story {
  float: left;
  width: 250px;
  margin-right: 25px;
  position: relative;
  font-size: 80%;
}
.hero-image {
  min-width: 100%;
}

.last {
  margin-right: 0;
}

/* ----------- iPhone 4 and 4S ----------- */

/* Portrait and Landscape */
@media only screen and (min-device-width: 320px) and (max-device-width: 480px) and (-webkit-min-device-pixel-ratio: 2) {
  .col-lg-4,
  .story-intro {
    width: 70%;
    background: rgba(0, 0, 0, 0.75);
    padding: 20px;
    color: white;
    padding-right: calc(var(--bs-gutter-x) / 2);
    padding-left: calc(var(--bs-gutter-x) / 2);
    margin-top: var(--bs-gutter-y);
  }
  .story-intro h1 {
    font-size: xx-large !important;
  }
}

/* Portrait */
@media only screen and (min-device-width: 320px) and (max-device-width: 480px) and (-webkit-min-device-pixel-ratio: 2) and (orientation: portrait) {
  .col-lg-4,
  .story-intro {
    width: 70%;
    background: rgba(0, 0, 0, 0.75);
    padding: 20px;
    color: white;
    padding-right: calc(var(--bs-gutter-x) / 2);
    padding-left: calc(var(--bs-gutter-x) / 2);
    margin-top: var(--bs-gutter-y);
  }
  .story-intro h1 {
    font-size: xx-large !important;
  }
}

/* Landscape */
@media only screen and (min-device-width: 320px) and (max-device-width: 480px) and (-webkit-min-device-pixel-ratio: 2) and (orientation: landscape) {
  .col-lg-4,
  .story-intro {
    width: 70%;
    background: rgba(0, 0, 0, 0.75);
    padding: 20px;
    color: white;
    padding-right: calc(var(--bs-gutter-x) / 2);
    padding-left: calc(var(--bs-gutter-x) / 2);
    margin-top: var(--bs-gutter-y);
  }
  .story-intro h1 {
    font-size: xx-large !important;
  }
}

/* ----------- iPhone 5, 5S, 5C and 5SE ----------- */

/* Portrait and Landscape */
@media only screen and (min-device-width: 320px) and (max-device-width: 568px) and (-webkit-min-device-pixel-ratio: 2) {
  .col-lg-4,
  .story-intro {
    width: 70%;
    background: rgba(0, 0, 0, 0.75);
    padding: 20px;
    color: white;
    padding-right: calc(var(--bs-gutter-x) / 2);
    padding-left: calc(var(--bs-gutter-x) / 2);
    margin-top: var(--bs-gutter-y);
  }
  .story-intro h1 {
    font-size: xx-large !important;
  }
}

/* Portrait */
@media only screen and (min-device-width: 320px) and (max-device-width: 568px) and (-webkit-min-device-pixel-ratio: 2) and (orientation: portrait) {
  .col-lg-4,
  .story-intro {
    width: 70%;
    background: rgba(0, 0, 0, 0.75);
    padding: 20px;
    color: white;
    padding-right: calc(var(--bs-gutter-x) / 2);
    padding-left: calc(var(--bs-gutter-x) / 2);
    margin-top: var(--bs-gutter-y);
  }
  .story-intro h1 {
    font-size: xx-large !important;
  }
}

/* Landscape */
@media only screen and (min-device-width: 320px) and (max-device-width: 568px) and (-webkit-min-device-pixel-ratio: 2) and (orientation: landscape) {
  .col-lg-4,
  .story-intro {
    width: 70%;
    background: rgba(0, 0, 0, 0.75);
    padding: 20px;
    color: white;
    padding-right: calc(var(--bs-gutter-x) / 2);
    padding-left: calc(var(--bs-gutter-x) / 2);
    margin-top: var(--bs-gutter-y);
  }
  .story-intro h1 {
    font-size: xx-large !important;
  }
}

/* ----------- iPhone 6, 6S, 7 and 8 ----------- */

/* Portrait and Landscape */
@media only screen and (min-device-width: 375px) and (max-device-width: 667px) and (-webkit-min-device-pixel-ratio: 2) {
  .col-lg-4,
  .story-intro {
    width: 70%;
    background: rgba(0, 0, 0, 0.75);
    padding: 20px;
    color: white;
    padding-right: calc(var(--bs-gutter-x) / 2);
    padding-left: calc(var(--bs-gutter-x) / 2);
    margin-top: var(--bs-gutter-y);
  }
  .story-intro h1 {
    font-size: xx-large !important;
  }
}

/* Portrait */
@media only screen and (min-device-width: 375px) and (max-device-width: 667px) and (-webkit-min-device-pixel-ratio: 2) and (orientation: portrait) {
  .col-lg-4,
  .story-intro {
    width: 70%;
    background: rgba(0, 0, 0, 0.75);
    padding: 20px;
    color: white;
    padding-right: calc(var(--bs-gutter-x) / 2);
    padding-left: calc(var(--bs-gutter-x) / 2);
    margin-top: var(--bs-gutter-y);
  }
  .story-intro h1 {
    font-size: xx-large !important;
  }
}

/* Landscape */
@media only screen and (min-device-width: 375px) and (max-device-width: 667px) and (-webkit-min-device-pixel-ratio: 2) and (orientation: landscape) {
  .col-lg-4,
  .story-intro {
    width: 70%;
    background: rgba(0, 0, 0, 0.75);
    padding: 20px;
    color: white;
    padding-right: calc(var(--bs-gutter-x) / 2);
    padding-left: calc(var(--bs-gutter-x) / 2);
    margin-top: var(--bs-gutter-y);
  }
  .story-intro h1 {
    font-size: xx-large !important;
  }
}

/* ----------- iPhone 6+, 7+ and 8+ ----------- */

/* Portrait and Landscape */
@media only screen and (min-device-width: 414px) and (max-device-width: 736px) and (-webkit-min-device-pixel-ratio: 3) {
  .story-intro {
    -ms-flex: 0 33.333333%;
    flex: 0 0 33.333333%;
    max-width: 33.333333%;
  }
  .story-intro h1 {
    font-size: xx-large !important;
  }
}

/* Portrait */
@media only screen and (min-device-width: 414px) and (max-device-width: 736px) and (-webkit-min-device-pixel-ratio: 3) and (orientation: portrait) {
  .col-lg-4,
  .story-intro {
    width: 70% !important;
    background: rgba(0, 0, 0, 0.75) !important;
    padding: 20px !important;
    color: white !important;
  }
  .tile-image {
    padding-left: 50px !important;
    padding-right: calc(var(--bs-gutter-x) / 2);
    padding-left: calc(var(--bs-gutter-x) / 2);
    margin-top: var(--bs-gutter-y);
  }
  .story-intro h1 {
    font-size: xx-large !important;
  }
}

/* Landscape */
@media only screen and (min-device-width: 414px) and (max-device-width: 736px) and (-webkit-min-device-pixel-ratio: 3) and (orientation: landscape) {
  .tile-image {
    padding-left: 50px !important;
    padding-right: calc(var(--bs-gutter-x) / 2);
    padding-left: calc(var(--bs-gutter-x) / 2);
    margin-top: var(--bs-gutter-y);
  }
  .story-intro h1 {
    font-size: xx-large !important;
  }
}

/* ----------- iPhone X ----------- *

/* Portrait */
@media only screen and (min-device-width: 375px) and (max-device-width: 812px) and (-webkit-min-device-pixel-ratio: 3) and (orientation: portrait) {
  .col-lg-4,
  .story-intro {
    width: 70%;
    background: rgba(0, 0, 0, 0.75);
    padding: 20px;
    color: white;
  }
  .tile-image {
    padding-left: 50px !important;
    padding-right: calc(var(--bs-gutter-x) / 2);
    padding-left: calc(var(--bs-gutter-x) / 2);
    margin-top: var(--bs-gutter-y);
  }
  .story-intro h1 {
    font-size: xx-large !important;
  }
}

/* Landscape */
@media only screen and (min-device-width: 375px) and (max-device-width: 812px) and (-webkit-min-device-pixel-ratio: 3) and (orientation: landscape) {
  .col-lg-4,
  .story-intro {
    width: 70%;
    background: rgba(0, 0, 0, 0.75);
    padding: 20px;
    color: white;
  }
  .tile-image {
    padding-left: 50px !important;
    padding-right: calc(var(--bs-gutter-x) / 2);
    padding-left: calc(var(--bs-gutter-x) / 2);
    margin-top: var(--bs-gutter-y);
  }
  .story-intro h1 {
    font-size: xx-large !important;
  }
}
/* .section-category {
  display: flex;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  margin-right: -15px;
  margin-left: -15px;
} */
</style>
