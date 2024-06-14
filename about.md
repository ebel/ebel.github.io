---
layout: page
title: About
permalink: /about/
---

---
layout: default
title: About
permalink: /about/
---

<article class="post">

  <header class="post-header">
    <h1 class="post-title">{{ page.title | escape }}</h1>
  </header>

  <div class="post-content">
    <p>Welcome to the about page. Here are some useful links:</p>
    <ul>
      <li><a href="{{ site.baseurl }}{% link _pages/projects.md %}">Projects</a></li>
      <li><a href="{{ site.baseurl }}{% link _pages/resume.md %}">Resume</a></li>
      <li><a href="{{ site.baseurl }}{% link _pages/links.md %}">Links</a></li>
      <li><a href="{{ site.baseurl }}{% link _pages/random.md %}">Random</a></li>
      <li><a href="{{ site.baseurl }}{% link _pages/things_ive_done.md %}">Things I've Done</a></li>
    </ul>
  </div>

</article>
