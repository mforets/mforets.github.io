---
layout: page
title: "Ongoing"
---

Preliminary work which has not been yet submitted for publication.

1. *Reachability Computations for Formal Verification in Julia.*
<br> See [JuliaReach-AES](https://github.com/JuliaReach/JuliaReach-AES).
<br> 2018, work-in-progress.

2. *LazySets: a library for convex sets.*
<br> See [LazySets.jl](https://github.com/JuliaReach/LazySets.jl) in github.
<br> 2018, work-in-progress.

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
