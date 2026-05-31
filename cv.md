---
layout: default
title: CV
---

<style>
  .cv-header {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    margin-bottom: 1rem;
  }
  .download-btn {
    display: inline-block;
    font-family: Arial, sans-serif;
    font-size: 0.78rem;
    letter-spacing: 0.07em;
    text-transform: uppercase;
    padding: 0.4rem 1rem;
    border: 1px solid #0051a2;
    color: #0051a2;
    text-decoration: none;
    transition: background 0.2s, color 0.2s;
  }
  .download-btn:hover {
    background: #0051a2;
    color: #fff;
  }
  .cv-frame {
    width: 100%;
    height: 80vh;
    border: 1px solid #ddd;
    display: block;
  }
  .cv-fallback {
    display: none;
    padding: 2rem;
    text-align: center;
    border: 1px solid #ddd;
    color: #888;
    font-family: Arial, sans-serif;
    font-size: 0.88rem;
  }
</style>

<div class="cv-header">
  <h1>CV</h1>
  <a class="download-btn" href="/cv.pdf" download>Download PDF</a>
</div>

<iframe
  class="cv-frame"
  src="/JoshO_ConnorCV_SP26_.pdf"
  title="Joshua O'Connor CV">
  <div class="cv-fallback">
    Your browser can't display PDFs inline.
    <a href="/cv.pdf">Download the PDF instead.</a>
  </div>
</iframe>
