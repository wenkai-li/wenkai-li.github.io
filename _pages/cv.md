---
layout: default
permalink: /cv/
title: cv
nav: true
nav_order: 5
---

<style>
  /* Remove top margin from container */
  .container.mt-5 {
    margin-top: 0 !important;
    padding: 0 !important;
    max-width: 100% !important;
  }

  /* Make PDF container full width and height */
  .pdf-container {
    width: 100vw;
    height: calc(100vh - 60px); /* Subtract navbar height */
    margin-left: calc(-50vw + 50%);
    position: relative;
  }
</style>

<div class="pdf-container">
  <iframe src="{{ '/assets/pdf/CV_research_Wenkai_Li.pdf' | relative_url }}" width="100%" height="100%" style="border: none;">
    <p>Your browser does not support PDFs.
       <a href="{{ '/assets/pdf/CV_research_Wenkai_Li.pdf' | relative_url }}">Download the PDF</a>.
    </p>
  </iframe>
</div>
