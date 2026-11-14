---
layout: page
permalink: /product/
title: product
description: "stuff that facilitate research progress"
nav: true
nav_order: 3
_styles: >
  hr { border: 0; border-top: 1px solid var(--global-divider-color); height: 0; }
  .product { display: flex; gap: 2rem; align-items: flex-start; margin: 1.5rem 0; }
  .product-media { flex: 0 0 38%; max-width: 38%; }
  .product-media video { display: block; width: 100%; height: auto; border-radius: 0.5rem; box-shadow: 0 2px 5px rgba(0, 0, 0, 0.16), 0 2px 10px rgba(0, 0, 0, 0.12); }
  .product-body h3 { margin: 0 0 0.75rem; font-size: 2rem; font-weight: 400; }
  .product-body p { margin: 0 0 1rem; }
  @media (max-width: 640px) { .product { flex-direction: column; gap: 1rem; } .product-media { flex-basis: auto; max-width: 100%; width: 100%; } }
---

<hr>
<div class="product">
  <div class="product-media">
    <video src="/assets/video/dataset-shortlist-demo.mp4" autoplay muted loop playsinline aria-label="Dataset Shortlist demo"></video>
  </div>
  <div class="product-body">
    <h3>Dataset Shortlist</h3>
    <p>Find research data you can actually get.</p>
    <p><a href="https://wangnicolas.github.io/dataset-shortlist/">product page</a></p>
  </div>
</div>
<hr>
