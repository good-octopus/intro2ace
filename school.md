<html lang="en">
<head>
  <link rel="icon" type="image/svg+xml" href="favicon.svg">
  <link rel="manifest" href="site.webmanifest">
  <link rel="stylesheet" href="left.css">
  <script>
    document.addEventListener("DOMContentLoaded", function() {
      var navLinks = document.querySelectorAll("#navMenu a");
      var currentPage = window.location.pathname.split("/").pop();

      navLinks.forEach(function(link) {
        if (link.getAttribute("href") === currentPage) {
          link.classList.add("current-section");
        }
      });
    });
  </script>
</head>
<body>
  <div id="navMenu">
    <ul>
      <li><a href="introduction.md">Introduction</a></li>
      <li><a href="experiences_by_others.md">Experiences by Others</a></li>
      <li><a href="glossary.md">Glossary</a></li>
      <li><a href="myth_busters.md">Myth Busters</a></li>
      <li><a href="other_resources.md">Other Resources</a></li>
      <li><a href="school.md">School</a></li>
      <li><a href="survive_sex_ed.md">Survive Sex Ed</a></li>
      <li><a href="trust_science.md">Trust Science!</a></li>
      <li><a href="why_i_made_this_website.md">Why I Made This Website</a></li>
      <li><a href="worried.md">Worried?</a></li>
    </ul>
  </div>
  <div class="content">
    #advice about school

    #we all die
  </div>
</body>
</html>
