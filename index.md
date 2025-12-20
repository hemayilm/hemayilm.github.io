---
layout: default
title: "Home"
---

<!-- Home page hero: profile photo and intro -->
<header class="hero" role="banner">
  <div class="container hero__inner">

   <!-- Profile photo -->
<div class="hero__photo" aria-hidden="false">
  <img src="{{ '/assets/images/image.png' | relative_url }}" alt="Profile photo">
</div>

<!-- Intro content -->
<div class="hero__content">
  <h1 class="hero__title">Hi — I'm Hamayil Mammadova.</h1>
  <p class="hero__subtitle">
    I am a student passionate about programming, web development, and designing elegant digital experiences. 
    I enjoy creating clean and modular websites, experimenting with modern design concepts, and continuously learning new technologies.
    Outside of coding, I appreciate aesthetics that are subtle, refined, and balanced — blending creativity with clarity.
  </p>

  <!-- Action links: About + Projects -->
  <div class="hero__actions">
    <a class="btn btn--primary" href="{{ '/about/' | relative_url }}">About Me</a>
    <a class="btn btn--secondary" href="{{ '/projects/' | relative_url }}">My Projects</a>
  </div>
</div>

  </div>
</header>

<main role="main" class="container">
  <!-- Welcome section -->
  <section aria-labelledby="welcome-heading">
    <h2 id="welcome-heading">Welcome</h2>
    <p>
      Thank you for visiting my personal website. Here, you can explore my skills, projects, and experience in Information Systems. 
      I focus on building web solutions that are responsive, accessible, and visually appealing, combining both technical skill and creative design.
    </p>
  </section>

  <!-- Optional: future sections for featured projects, achievements, or skills -->
</main>
