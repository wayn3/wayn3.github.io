---
layout: default
title: Wei Chen (#CompPhys)
---

* now at uclouvain.be
* curriculum vitae in [pdf](cv.pdf)
* github ([wch3n](http://github.com/wch3n))
* research profile: 
  [Google Scholar](https://scholar.google.com/citations?user=ouy6ESIAAAAJa),
  [ORCID](http://orcid.org/0000-0002-7496-0341)

## research interests
- Highly-accurate hybrid density-functional theory 
  and many-body perturbation theory methods for condensed matter systems
- Defect physics in semiconductors
- High-throughput and data-driven material discovery
- Ferromagnetic semiconducting materials 
- Emerging photovoltaic materials (CZTSSe)

{% for post in site.posts %}

<article class='post'>
  <h1 class='post-title'>
    <a href="{{ site.path }}{{ post.url }}">
      {{ post.title }}
    </a>
  </h1>
  <div class="post-date">{{ post.date | date: "%b %-d, %Y" }}</div>
  {{ post.content }}
</article>

{% endfor %}

