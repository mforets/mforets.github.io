---
layout: page
title: Publications
---

This section contains publications that appeared in peer-reviewed journals or in conference proceedings with reviewing committee. 

## Quantum Random Walks

<ol reversed>
<hr>

  <li> <i> Quantum Walking in Curved Spacetime.</i><br> Pablo Arrighi, Stefano Facchini, M. F. <br>  Quantum Information Processing  <a href="http://link.springer.com/article/10.1007/s11128-016-1335-7"> (2016) 15: 3467.</a>  <br> 
Pre-print: <a href="https://arxiv.org/abs/1505.07023">arXiv:1505.07023
[quant-ph]</a>   <br>  
<hr>
</li>

  <li> <i> Discrete
Lorentz covariance for Quantum Walks and Quantum Cellular Automata.</i> <br> Pablo Arrighi, Stefano Facchini, M. F. <br> New Journal of Physics  <a href="http://iopscience.iop.org/1367-2630/16/9/093007/">16 (2014) 093007</a>.  <br>Pre-print: <a href="http://arxiv.org/abs/1404.4499">arXiv:1404.4499
[quant-ph]</a>   <br>  
<hr>
</li>

<li> <i> The
Dirac equation as a quantum walk: higher dimensions, observational
convergence.</i> <br> Pablo Arrighi, Vincent Nesme and M. F. <br> J. Phys. A: Math. Theor. 47 <a href="http://iopscience.iop.org/1751-8121/47/46/465302/"> (2014) 465302</a>.  <br> Pre-print: <a href="http://arxiv.org/abs/1307.3524">arXiv:1307.3524 [quant-ph]</a>   <br>  
<hr>
</li>


  <li> <i> Spatial quantum search in a triangular network.</i> <br> Gonzalo Abal, Raul Donangelo, M. F., Renato Portugal. <br> Mathematical
Structures in Computer Science,  <a href="http://journals.cambridge.org/action/displayAbstract?fromPage=online&aid=8544748&fileId=S0960129511000600">
<b> 22 </b>, pp 521-531, Cambridge
University Press </a>. <br> Pre-print: <a href="http://arxiv.org/abs/1009.1422">arXiv:1009.1422 [quant-ph]  </a> <br>  
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
