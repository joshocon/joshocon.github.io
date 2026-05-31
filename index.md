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
  and a first-generation college student. In high school, I independently stumbled onto
  integer partitions while playing with number patterns — I didn't know it was mathematics yet.
  When I later saw Euler's partition generating function in Prof. Martin's combinatorics course,
  something clicked into place. That moment has shaped everything since.
</p>
<p>
  My interests are broadly in algebraic combinatorics. I'm drawn to the thread that runs
  through my research so far: turning complicated geometry into algebra, and turning that
  algebra into combinatorics. I find the most satisfaction when a hard structural question
  reduces to something you can count.
</p>

<h2>Currently</h2>
<div class="currently">
  <p>REU at Michigan State (SURIEM) — quantum sl₃ knot invariants</p>
  <p>Honors thesis (prospective) with Prof. Jeremy Martin — chromatic symmetric functions</p>
  <p>Reading: Rosa Orellana's recent work on the star basis expansion of the CSF</p>
</div>

<h2>Outside math</h2>
<p>
  I founded and run the KU Math Club, and have worked as a supplemental instructor,
  grader, and tutor across several courses — mentoring first-generation students is
  something I care about as much as the research. Outside of math I play guitar, sing,
  and compete at video games.
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
</div>
