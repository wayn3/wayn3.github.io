---
layout: default
title: Wei Chen (#CompPhys)
---

#### basics
* now at UCLouvain (be).
* curriculum vitae ([pdf](cv.pdf)).
* github: [wch3n](http://github.com/wch3n).
* profile: 
  [Google scholar](https://scholar.google.com/citations?user=ouy6ESIAAAAJa),
  [Orcid](http://orcid.org/0000-0002-7496-0341).

#### research interests
- Electronic structure
  ... Development of highly-accurate hybrid density-functional theory 
      and many-body perturbation theory methods for condensed matter systems
- High-throughput computational screening
  ... Magnetic materials, emerging photovoltaic materials

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

