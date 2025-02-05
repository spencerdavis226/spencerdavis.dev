---
layout: default
title: Resume
---

# Resume

<style>
  .pdf-container {
    width: 100%;
    max-width: 100%;
    margin: 0 auto;
  }

  .pdf-container object {
    width: 100%;
    height: 80vh; /* Adjust as needed */
    max-width: 100%;
  }
</style>

<div class="pdf-container">
  <object data="{{ '/assets/images/resume.pdf' | relative_url }}" type="application/pdf" width="100%" height="800px">
    <p>Your browser does not support PDFs. <a href="{{ '/assets/images/resume.pdf' | relative_url }}">Download the PDF</a>.</p>
  </object>
</div>
