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

<script>
  window.location.href = "{{ cv_path }}";
</script>
<meta http-equiv="refresh" content="0; url={{ cv_path }}">

<p>
  Redirecting to your CV PDF.
  If you are not redirected automatically, <a href="{{ cv_path }}">open it here</a>.
</p>
