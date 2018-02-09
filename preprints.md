---
layout: page
title: "Preprints"
---

Papers which have been submitted to a reviewing committee.

---

## Hybrid Systems and Formal Verification

2. *LazySets: a Library for Convex Sets*.
<br> Sergiy Bogomolov, M. F., Goran Frehse, Andreas Podelski, Christian Schilling, Frédéric Viry.
<br> 2018, submitted. <br> <small> **Keywords:** convex sets, lazy set representation, reachability analysis. </small>

2. *Occupation measure methods for modelling and analysis of biological hybrid automata*. <br> Thao Dang, Eric Fanchon, M. F., Victor Magron, Alexandre Rocca. <br> 2017, submitted. [[arXiv - cs.SY]](https://arxiv.org/abs/1710.03158).<br> <small> **Keywords:** biological modelling, hybrid dynamical system, optimal control problem,
semidefinite optimization, occupation measures. </small>

## Numerical Analysis and Systems Control

1. *Explicit Error Bounds for Carleman Linearization.* <br> M. F., Amaury Pouly. <br> 2017, submitted. [[arXiv - math.NA]](https://arxiv.org/abs/1711.02552). <br> See also: [carlin package](https://github.com/mforets/carlin) for SageMath. <br>
<small> **Keywords:** carleman linearization, polynomial ODEs, infinite-dimensional systems, guaranteed integration, nonlinear control theory. </small>

<div class="posts">
  {% for post in paginator.posts %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ site.baseurl }}/{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    <!-- original: {{ post.content }}
    use the trick below to display only a fragment of the post (e.g. first 100 words with truncatewords:100)
    -->
    {{ post.content | strip_html | truncatewords:75 }}  
  </div>
  {% endfor %}
</div>
