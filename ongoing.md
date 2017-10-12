---
layout: page
title: "Ongoing"
---

Preliminary work which has not been yet submitted for publication.

1. *Explicit Error Bounds for Carleman Linearization.* <br> M. F., Amaury Pouly. <br> 2017, to be submitted. <br> See also: [carlin package](https://github.com/mforets/carlin) for SageMath.

2. *Carleman Linearization for Set-based Reachability*. <br> M. F., Nikolaos Kekatos, Goran Frehse, Amaury Pouly. <br> 2017, work-in-progress.

3. *Reachability of Nonlinear Systems using Support Functions*. <br> M. F., Goran Frehse. <br> 2017, work-in-progress.

4. *Fighting the Wrapping Effect Through Invariance*. <br> M. F., Goran Frehse. <br> 2017, work-in-progress.

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
