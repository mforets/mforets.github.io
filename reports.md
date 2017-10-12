---
layout: page
title: "Technical Reports"
---

Technical reports that document the progress of research projects.
They are not meant to be published in journals or conferences.

<ol reversed>
<hr>

<li> <i> Compositional Analysis of Circuits with Parametric Uncertainties</i><br> M. F., Goran Frehse, Nikolaos Kekatos.<br> December 2016. Technical deliverable report of the project NANO2017.<br>
<hr>
</li>

<li> <i> Modeling Analog Circuits with Technological Dispersion</i><br> M. F., Stefano Minopoli, Goran Frehse. <br>  July 2016. Technical deliverable report  of the project NANO2017.<br> 
<hr>
</li>

</ol>

If you are interested to know more about a technical report please send me an email.

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
