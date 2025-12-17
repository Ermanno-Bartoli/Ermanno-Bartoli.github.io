---
layout: cv
permalink: /cv/
title: cv
nav: true
nav_order: 5
cv_pdf: bartoli_cv.pdf # you can also use external links here
description: This is a description of the page. You can modify it in '_pages/cv.md'. You can also change or remove the top pdf download button.
toc:
  sidebar: left
---

{% assign cv_path = '/assets/pdf/bartoli_cv.pdf' | relative_url %}

<div class="embed-responsive embed-responsive-1by1" style="min-height: 80vh;">
  <object data="{{ cv_path }}" type="application/pdf" width="100%" height="100%">
    <p>
      Your browser can’t display the PDF inline.
      <a href="{{ cv_path }}" target="_blank">Open the CV in a new tab.</a>
    </p>
  </object>
</div>
