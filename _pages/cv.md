---
layout: default
permalink: /cv/
title: cv
nav: true
nav_order: 5
# Link used by the navbar (so clicking "cv" goes straight to the PDF).
nav_url: /assets/pdf/bartoli_cv.pdf
---

{% assign cv_url = page.nav_url | relative_url %}

<script>
  window.location.replace("{{ cv_url }}");
</script>
<meta http-equiv="refresh" content="0; url={{ cv_url }}">

<p>
  Redirecting to CV PDF.
  If you are not redirected automatically, <a href="{{ cv_url }}">open it here</a>.
</p>
