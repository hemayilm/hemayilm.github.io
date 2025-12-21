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
      <h1 class="hero__title">Hi — I'm Hamayil Mammadova</h1>
      <p class="hero__subtitle">
        I am a <span class="highlight">student passionate about programming</span>, <span class="highlight">web development</span>, and designing elegant digital experiences.
      </p>
      <p class="hero__subtitle">
        I enjoy creating clean, modular websites, experimenting with modern design concepts, and continuously learning new technologies. Outside of coding, I appreciate aesthetics that are subtle, refined, and balanced — blending creativity with clarity.
      </p>
      <div class="hero__buttons">
        <a href="{{ site.baseurl }}/about.html" class="btn btn--primary">Learn About Me</a>
        <a href="{{ site.baseurl }}/projects.html" class="btn btn--secondary">View My Projects</a>
      </div>
    </div>

  </div>
</header>

<main role="main" class="container">

  <!-- Welcome section -->
  <section aria-labelledby="welcome-heading" class="section content-block">
    <h2 id="welcome-heading">Welcome</h2>
    <p>
      Thank you for visiting my personal website. Here, you can explore my skills, projects, and experience in Information Systems. 
      I focus on building web solutions that are <strong>responsive</strong>, <strong>accessible</strong>, and <strong>visually appealing</strong>, combining both technical skill and creative design.
    </p>
  </section>

  <!-- Optional: Featured Projects Section -->
  <section aria-labelledby="featured-projects" class="section content-block">
    <h2 id="featured-projects">Featured Projects</h2>
    <p>
      Explore some of my recent projects that showcase my skills in web development, digital logic, and AI education.
    </p>
    <div class="featured-projects">
      <a href="{{ site.baseurl }}/projects.html#breaking-logic-gates" class="btn btn--primary">Breaking Logic Gates</a>
      <a href="{{ site.baseurl }}/projects.html#hour-of-ai" class="btn btn--primary">Hour of AI</a>
    </div>
  </section>

</main>