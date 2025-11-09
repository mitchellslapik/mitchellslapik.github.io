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

  <!-- Redirect that respects baseurl (e.g., /new_site) -->
  <meta http-equiv="refresh" content="0; url={{ '/assets/pdf/cv.pdf' | relative_url }}">

  <!-- Canonical absolute URL -->
  <link rel="canonical" href="{{ '/assets/pdf/cv.pdf' | absolute_url }}">
</head>
<body>
  <p>If you are not redirected automatically,
     <a href="{{ '/assets/pdf/cv.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">
       click here to view the CV.
     </a>
  </p>

  <!-- JS fallback (in case meta refresh is blocked) -->
  <script>
    window.location.replace("{{ '/assets/pdf/cv.pdf' | relative_url }}");
  </script>
</body>
</html>
