---
Title: Gallery
Description: Kmom05 Gallery Page
---

Gallery
==================

[![Bike via assets/img](%assets_url%/img/gallery/bike.jpg)](%assets_url%/img/gallery/bike.jpg)


<!-- [![Bie via cimage](%base_url%/image/gallery/bike.jpg?w=500)](%base_url%/image/gallery/bike.jpg) -->

<!-- <img src="%assets_url%/cimage/gallery/bike.jpg?w=200" alt="Bike"/> -->

<div class="gallery">
    <picture>
        <source media="(min-width: 700px)" srcset="%base_url%/image/gallery/bike.jpg?w=1000">
        <img src="%base_url%/image/gallery/bike.jpg?w=500" alt="Bike">
    </picture>
    <picture>
        <source media="(min-width: 700px)" srcset="%base_url%/image/gallery/bike.jpg?w=1000&crop-to-fit">
        <img src="%base_url%/image/gallery/bike.jpg?w=100" alt="Bike">
    </picture>
</div>