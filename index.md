---
layout: default
title: Wei Chen
---

#### basics
* curriculum vitae in [pdf](cv.pdf).
* github: [wch3n](http://github.com/wch3n).
* citations: 
  [google scholar](https://scholar.google.com/citations?user=ouy6ESIAAAAJa),
  [orcid](http://orcid.org/0000-0002-7496-0341).

#### research interests
- electronic structure 
- condensed matter physics
- liquid systems
- density functional theory
- many-body perturbation theory
- ab initio molecular dynamics
- high-throughput computational screening

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

