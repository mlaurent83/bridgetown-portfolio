---
layout: default
title: "Projects - Maëva Laurent-Estavel"
description: "A showcase of Maëva Laurent-Estavel's projects"
permalink: "/projects/"
---

<div id="navbar"></div>

<div class="container py-3 pt-0 mb-4">
  <div class="title h1 text-center libre-baskerville-bold mb-4">My projects</div>

  <!-- Card Start -->
  <div class="card mb-2" data-aos="fade-up">
    <div class="row no-gutters">

      <!-- Text section -->
      <div class="col-md-7 px-3">
        <div class="card-block px-6">
          <h4 class="card-title text-dark libre-baskerville-bold">Portable Parenting</h4>
          <p class="card-text libre-baskerville-regular">
            Portable Parenting is a website designed to help parents travel abroad lightly.
          </p>
          <p class="card-text libre-baskerville-regular">By renting items for their babies/children on the website, parents don't have to worry
            about
            traveling with heavy items. Don't forget to sign up to see all the features!</p>
          <p>Main tech: <strong>Ruby on Rails, HTML, SCSS, Javascript</strong></p>
          <a href="https://www.portable-parenting.xyz/" class="mt-auto btn btn-dark libre-baskerville-regular" target="_blank">View
            project</a>
        </div>
      </div>

      <!-- Carousel section -->
      <div class="col-md-5 d-flex align-items-center">
        <div id="CarouselTest" class="carousel slide w-100" data-ride="carousel">
          <ol class="carousel-indicators">
            <li data-target="#CarouselTest" data-slide-to="0" class="active"></li>
            <li data-target="#CarouselTest" data-slide-to="1"></li>
            <li data-target="#CarouselTest" data-slide-to="2"></li>
          </ol>

          <div class="carousel-inner">
            <div class="carousel-item active">
              <img class="d-block w-100" src="{{ '/images/portable_parenting1.png' | asset_path }}" alt="Slide 1">
            </div>
            <div class="carousel-item">
              <img class="d-block w-100" src="{{ '/images/portable_parenting2.png' | asset_path }}" alt="Slide 2">
            </div>
            <div class="carousel-item">
              <img class="d-block w-100" src="{{ '/images/portable_parenting3.png' | asset_path }}" alt="Slide 3">
            </div>
          </div>

          <a class="carousel-control-prev" href="#CarouselTest" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a class="carousel-control-next" href="#CarouselTest" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
    </div>

  </div>
  <!-- End of card -->

  <!-- Repeat similar sections for other projects -->
  <div class="card" data-aos="fade-up">
    <!-- ... Content for Connect Clique -->
  </div>

  <div class="card" data-aos="fade-up">
    <!-- ... Content for Playlist Maker -->
  </div>
</div>

<div id="footer"></div>

<script>
  AOS.init({
    duration: 800,
    easing: 'ease-in-out',
    once: true
  });
</script>
