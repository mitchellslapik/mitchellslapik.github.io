---
layout: page
permalink: /music/
title: music
nav: true
nav_order: 4
---

<style>
  .music-container {
    width: 100%;
    margin: 0 auto 30px;
    text-align: center;
  }

  .spotify-wrapper {
    width: 100%;
    max-width: 550px;
    margin: 0 auto;
  }

  .spotify-wrapper iframe {
    display: block;
    width: 100%;
    height: 450px;
    margin: 0 auto;
    border: 0;
    border-radius: 12px;
  }

  .tweets {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
    gap: 20px;
    margin: 0 auto;
  }

  .tweet-wrapper {
    display: grid;
    place-items: center;
    width: 100%;
    max-width: 550px;
    margin: 0 auto;
    overflow: hidden;
  }

  /*
   * Style the original blockquote before Twitter converts it,
   * as well as the iframe Twitter inserts afterward.
   */
  .tweet-wrapper .twitter-tweet,
  .tweet-wrapper .twitter-tweet-rendered,
  .tweet-wrapper iframe {
    width: 100% !important;
    max-width: 550px !important;
    margin: 0 auto !important;
    box-sizing: border-box;
  }

  /*
   * Overrides theme-level blockquote indentation that can cause
   * the initial right-to-left jump.
   */
  .tweet-wrapper blockquote {
    margin-left: auto !important;
    margin-right: auto !important;
    padding-left: 0 !important;
    padding-right: 0 !important;
  }
</style>

<!-- Music Section -->
<div class="music-container">
  <div class="spotify-wrapper">
    <iframe
      src="https://open.spotify.com/embed/album/6KdzEUEBoN6nJVFHIMqw7b?utm_source=generator"
      allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
      loading="lazy">
    </iframe>
  </div>
</div>

<!-- Tweets Section -->
<div class="tweets">

  <div class="tweet-wrapper">
    <blockquote class="twitter-tweet">
      <p lang="en" dir="ltr">
        Check out our live performance at the World-Famous
        <a href="https://twitter.com/RandRStudioLive">@RandRStudioLive</a>,
        available here:
        <a href="https://t.co/TdgeB09lTG">https://t.co/TdgeB09lTG</a>
        <a href="https://t.co/xTnfvkaqg2">pic.twitter.com/xTnfvkaqg2</a>
      </p>
      — The Chirp Chirps (@TheChirpChirps)
      <a href="https://twitter.com/TheChirpChirps/status/1660347862041985025">
        May 21, 2023
      </a>
    </blockquote>
  </div>

  <div class="tweet-wrapper">
    <blockquote class="twitter-tweet">
      <p lang="en" dir="ltr">
        Thanks everyone for coming out to our reunion show last week at
        Valhalla! The Chirp Chirps are Back!
        <a href="https://t.co/fLK5ZmCl9v">pic.twitter.com/fLK5ZmCl9v</a>
      </p>
      — The Chirp Chirps (@TheChirpChirps)
      <a href="https://twitter.com/TheChirpChirps/status/1725333888560517512">
        November 17, 2023
      </a>
    </blockquote>
  </div>

</div>

<script
  async
  src="https://platform.twitter.com/widgets.js"
  charset="utf-8">
</script>
