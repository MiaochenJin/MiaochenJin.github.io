---
permalink: /gallery/
title: "Gallery"
author_profile: true
---
{% include base_path %}
<style>
  /* simple CSS grid for your images */
  .gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    grid-gap: 1rem;
    margin: 2rem 0;
  }
  .gallery-grid figure {
    margin: 0;
    /* give every figure the same height */
    height: 200px;
    overflow: hidden;
  }
  .gallery-grid img {
    width: 100%;
    height: 100%;
    display: block;
  }
  .gallery-grid figcaption {
    text-align: center;
    margin-top: 0.5rem;
    font-size: 0.9rem;
    color: #555;
  }
</style>

## Mio and Nomi

They are sisters from the same litter!

<div class="gallery-grid">
    <figure>
        <img src="{{ base_path }}/images/gallery/Mio.jpeg" alt="This is Mio">
        <figcaption>This is Mio</figcaption>
    </figure>
    <figure>
        <img src="{{ base_path }}/images/gallery/Nomi.jpeg" alt="This is Nomi">
        <figcaption>This is Nomi</figcaption>
    </figure>
    <figure>
        <img src="{{ base_path }}/images/gallery/Both1.jpeg" alt="">
    </figure>
    <figure>
        <img src="{{ base_path }}/images/gallery/Both2.jpeg" alt="">
    </figure>
</div>