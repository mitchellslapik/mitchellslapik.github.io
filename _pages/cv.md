---
layout: none
permalink: /cv/
title: cv
nav: true
nav_order: 5
---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Redirecting to CV PDF...</title>

  <script>
    // Redirect immediately once the page starts loading
    window.location.replace("{{ '/assets/pdf/cv.pdf' | relative_url }}");
  </script>

  <!-- Canonical absolute URL -->
  <link rel="canonical" href="{{ '/assets/pdf/cv.pdf' | absolute_url }}">
</head>
<body>
  <noscript>
    <p>If you are not redirected automatically,
       <a href="{{ '/assets/pdf/cv.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">
         click here to view the CV.
       </a>
    </p>
  </noscript>
</body>
</html>
