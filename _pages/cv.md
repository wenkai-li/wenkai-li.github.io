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
    margin-top: 20px !important;
    padding: 0 20px !important;
    max-width: 100% !important;
  }

  /* Make PDF container 2/3 width with white space on sides */
  .pdf-container {
    width: 66.67%; /* 2/3 of the width */
    height: calc(100vh - 100px); /* Subtract navbar height and some padding */
    margin: 0 auto; /* Center the container */
    position: relative;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1); /* Optional: add subtle shadow */
  }
</style>

<div class="pdf-container">
  <iframe
    src="{{ '/assets/pdf/CV_research_Wenkai_Li.pdf' | relative_url }}"
    width="100%"
    height="100%"
    style="border: none;"
  >
    <p>
      Your browser does not support PDFs.
      <a href="{{ '/assets/pdf/CV_research_Wenkai_Li.pdf' | relative_url }}"
        >Download the PDF</a
      >.
    </p>
  </iframe>
</div>
