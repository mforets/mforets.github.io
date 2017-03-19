---
layout: page
title: Submitted Papers & Technical Reports
---

This section contains work that has either have been submitted for publication in a regular journal or a conferences, or technical research reports. 

## Hybrid Systems and Formal Verification


**Keywords:** compositional methods, reachability analysis, SpaceEx, nonlinear control systems. 

<ol reversed>
<hr>

<li> <i> Decomposing Reachability Computations for Affine Systems </i><br> Sergiy Bogomolov, M. F., Goran Frehse, Andreas Podelski, Christian Schilling, Frédéric Viry.<br>  2017, work-in-progress.  
<br>  
<hr>
</li>

<li> <i> Modeling the Wind Turbine Benchmark with PWA Hybrid
Automata </i><br> Nikolaos Kekatos, M. F., Goran Frehse. <br>  2017, submitted.
<br>  
<hr>
</li>

  <li> <i>Formal Verification of Nonlinear Simulink Models
via Syntactic Hybridization </i><br> Nikolaos Kekatos, M. F., Goran Frehse.<br>  2016, submitted. <a href="https://hal.archives-ouvertes.fr/hal-01487658"> Get latest version from HAL</a>, or download <a href="{{site.url}}/assets/papers/synlin.pdf"> a local copy. </a>
<br>  
<hr>
</li>

<li> <i> Compositional Analysis of Circuits with Parametric Uncertainties</i><br> M. F., Goran Frehse, Nikolaos Kekatos.<br> December 2016. Technical deliverable report of the project NANO2017.<br>
<hr>
</li>

<li> <i> Modeling Analog Circuits with Technological Dispersion</i><br> M. F., Stefano Minopoli, Goran Frehse. <br>  July 2016. Technical deliverable report  of the project NANO2017.<br> 
<hr>
</li>


</ol>



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
