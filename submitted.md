---
layout: page
title: "Submitted papers"
---

Papers which have been submitted for review.

---

## Hybrid Systems and Formal Verification

1. *Reach Set Approximation through Decomposition with Low-dimensional Sets and High-dimensional Matrices* <br> Sergiy Bogomolov, M. F., Goran Frehse, Andreas Podelski, Christian Schilling, Frédéric Viry.<br>  2017, submitted. <small> **Keywords:** reachability analysis, safety verification, linear time-invariant systems, set recurrence relation </small>

## Dynamical Systems and Mathematical Optimization

2. *Occupation measure methods for modelling and analysis of biological hybrid automata*. <br> Thao Dang, Eric Fanchon, M. F., Victor Magron, Alexandre Rocca. <br> 2017, submitted. [[arXiv - cs-SY]](https://arxiv.org/abs/1710.03158). <small> **Keywords:** biological modelling, hybrid dynamical system, optimal control problem,
semidefinite optimization, occupation measures. </small>

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
