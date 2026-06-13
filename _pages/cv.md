---
layout: default
permalink: /cv/
title: CV
nav: true
nav_order: 4
cv_pdf: /assets/pdf/CV.pdf # you can also use external links here
cv_format: jsonresume # options: rendercv, jsonresume
description: Curriculum Vitae of Chunshuo Qiu.
toc:
  sidebar: left
---

<link rel="stylesheet" href="{{ '/assets/css/al-folio-cv.css' | relative_url }}">
<link rel="stylesheet" href="{{ '/assets/css/cv-fixes.css' | relative_url }}">

{% al_folio_cv_render %}
