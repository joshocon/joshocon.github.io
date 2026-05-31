---
layout: default
title: About
---

<style>
  .about-grid {
    display: grid;
    grid-template-columns: 220px 1fr;
    gap: 2.5rem;
    align-items: start;
    margin-top: 0.5rem;
  }
  .about-grid img {
    width: 100%;
    border: 1px solid #ddd;
  }
  .contact-row {
    display: flex;
    flex-direction: column;
    gap: 0.3rem;
    margin-top: 0.5rem;
  }
  .contact-row a { color: #0051a2; }
  .label {
    font-family: Arial, sans-serif;
    font-size: 0.75rem;
    text-transform: uppercase;
    letter-spacing: 0.07em;
    color: #999;
  }
  @media (max-width: 600px) {
    .about-grid { grid-template-columns: 1fr; }
    .about-grid img { max-width: 240px; }
  }
</style>

<div class="about-grid">
  <div>
    <img src="/image.jpeg" alt="Joshua O'Connor" />
  </div>
  <div>
    <h1>Joshua O'Connor</h1>
    <p style="color:#888; font-family:Arial,sans-serif; font-size:0.85rem; margin-bottom:1.2rem;">
      Mathematics · University of Kansas
    </p>

    <h2>About</h2>
    <p>
      I'm a senior mathematics undergraduate at the University of Kansas, a McNair Scholar,
      and a first-generation college student. My areas of interest broadly are in algebraic combinatorics. I am excited by turning complicated geometry into algebra, and turning that algebra into combinatorics. This has been a common
      theme among all of my research experiences so far.
    </p>
    <p>
      I founded and run the KU Math Club, and have supported the math department by working as a supplemental intrsuctor, grader, and tutor for a variety of courses.
    </p>

    <h2>Contact</h2>
    <div class="contact-row">
      <span class="label">Email</span>
      <a href="mailto:j984o820@ku.edu">j984o820@ku.edu</a>
      <span class="label" style="margin-top:0.5rem;">GitHub</span>
      <a href="https://github.com/joshocon">joshocon</a>
      <span class="label" style="margin-top:0.5rem;">LinkedIn</span>
      <a href="https://www.linkedin.com/in/joshua-oconnor-ku/">joshua-oconnor-ku</a>
    </div>
  </div>
</div>
