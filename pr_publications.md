---
layout: page
title: Publications
---

This section contains publications at peer-reviewed journals or conference proceedings with reviewing committee. 

---

## Hybrid Systems and Formal Verification


1. *Modeling the Wind Turbine Benchmark with PWA Hybrid
Automata.* <br> Nikolaos Kekatos, M. F., Goran Frehse. <br> To appear in [Applied Verification for Continuous and Hybrid Systems](http://cps-vo.org/group/ARCH), 2017 Edition. <br> **Keywords:** reachability analysis, compositional methods, nonlinear control systems, SpaceEx.

---

## Quantum Random Walks

1. *Quantum Walking in Curved Spacetime.* <br> Pablo Arrighi, Stefano Facchini, M. F. <br>  Quantum Information Processing [(2016) 15: 3467](http://link.springer.com/article/10.1007/s11128-016-1335-7). <br> Pre-print: [arXiv:1505.07023 [quant-ph]](https://arxiv.org/abs/1505.07023).

2. *Discrete Lorentz covariance for Quantum Walks and Quantum Cellular Automata.* <br> Pablo Arrighi, Stefano Facchini, M. F. <br> New Journal of Physics  [16 (2014) 093007](http://iopscience.iop.org/1367-2630/16/9/093007/). <br> Pre-print: [arXiv:1404.4499 [quant-ph]](http://arxiv.org/abs/1404.4499).

3. *The Dirac equation as a quantum walk: higher dimensions, observational
convergence.* <br> Pablo Arrighi, Vincent Nesme and M. F. <br> J. Phys. A: Math. Theor. 47 [(2014) 465302](http://iopscience.iop.org/1751-8121/47/46/465302/) <br> Pre-print: <a href="http://arxiv.org/abs/1307.3524">arXiv:1307.3524 [quant-ph] 

4. *Spatial quantum search in a triangular network.* <br> Gonzalo Abal, Raul Donangelo, M. F., Renato Portugal. <br> Mathematical
Structures in Computer Science,  [22, pp 521-531, Cambridge
University Press](http://journals.cambridge.org/action/displayAbstract?fromPage=online&aid=8544748&fileId=S0960129511000600) <br> 
Pre-print: [arXiv:1009.1422 [quant-ph]](http://arxiv.org/abs/1009.1422).

---

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
