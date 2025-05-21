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
  .gallery-grid img {
    width: auto;
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
    <img src="{{ base_path }}/images/gallery/Mio.jpeg" alt="This is Mio">
    <img src="{{ base_path }}/images/gallery/Nomi.jpeg" alt="This is Nomi">
    <img src="{{ base_path }}/images/gallery/Both1.jpeg" alt="">
    <img src="{{ base_path }}/images/gallery/Both2.jpeg" alt="">
</div>