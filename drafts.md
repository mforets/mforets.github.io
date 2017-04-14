---
layout: page
title: "Preprints & Reports"
---

## Submitted papers

Papers which have been submitted for review.

1. *Constructing Verification Models of Nonlinear Simulink Systems via Syntactic Hybridization.*  <br> Nikolaos Kekatos, M. F., Goran Frehse.<br>  2016, submitted. <br> Download pre-print: [[HAL]](https://hal.archives-ouvertes.fr/hal-01487658), [[local copy]]({{site.url}}/assets/papers/synlin_v2.pdf).

## Working papers

Preliminary work which has not been yet submitted for publication.

1. *Decomposing Reachability Computations for Affine Systems.* <br> Sergiy Bogomolov, M. F., Goran Frehse, Andreas Podelski, Christian Schilling, Frédéric Viry.<br>  2017, work-in-progress.

2. *Explicit Error Bounds for Carleman Linearization.* <br> M. F., Amaury Pouly. <br> 2017, to be submitted. <br> See also: [carlin package](https://github.com/mforets/carlin) for SageMath.

3. *Semidefinite Characterization of Invariant Measures for  Polynomial Systems*. <br> M. F., Didier Henrion, Victor Magron. <br> 2017, work-in-progress.


## Technical reports

Technical reports on the progess of research projects. They are not meant to be published in journals or conferences.

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
