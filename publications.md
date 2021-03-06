---
layout: page
title: Publications
---

This section contains publications at peer-reviewed journals or conference proceedings
with reviewing committee.

---

## Hybrid Systems and Formal Verification

1. *JuliaReach: a Toolbox for Set-Based Reachability* <br> Sergiy Bogomolov, M. F., Goran Frehse, Kostiantyin Potomkin, Christian Schilling.<br> Accepted in [22nd ACM International Conference on Hybrid Systems: Computation and Control](http://hscc2019.eecs.umich.edu/),
2019 Edition to be held in Montreal, Canada.
<br> Download pre-print: to appear soon
<br><small> **Keywords:** reachability analysis, hybrid systems, lazy computation

1. *ARCH-COMP18 Category Report: Continuous and Hybrid Systems with Linear Continuous Dynamics* <br>
Matthias Althoff, Stanley Bak, Xin Chen, Chuchu Fan, Marcelo Forets, Goran Frehse, Niklas Kochdumper, Yangge Li, Sayan Mitra, Rajarshi Ray, Christian Schilling and Stefan Schupp (2018). <br>
In [ARCH18. 5th International Workshop on Applied Verification of Continuous and Hybrid Systems, 54: 23–52.](https://dblp.org/db/conf/adhs/arch2018.html).
<br> Download pdf: [[easychair]](https://easychair.org/publications/paper/4cGr)
<br><small> **Keywords:** reachability analysis, safety verification, competition </small>

1. *Reach Set Approximation through Decomposition with Low-dimensional Sets and High-dimensional Matrices* <br> Sergiy Bogomolov, M. F., Goran Frehse, Andreas Podelski, Christian Schilling, Frédéric Viry.<br>  In [21st ACM International Conference on Hybrid Systems: Computation and Control](https://www.hscc2018.deib.polimi.it/),
2018 Edition to be held in Porto, Portugal.
<br> Download pre-print: [[arXiv]](https://arxiv.org/abs/1801.09526)
<br><small> **Keywords:** reachability analysis, safety verification, linear time-invariant systems, set recurrence relation </small>

2. *Modeling the Wind Turbine Benchmark with PWA Hybrid Automata.* <br>
Nikolaos Kekatos, M. F., Goran Frehse. <br> In [Applied Verification for Continuous and Hybrid Systems](http://cps-vo.org/group/ARCH), 2017 Edition. <br> Download pre-print: [[HAL]](https://hal.archives-ouvertes.fr/hal-01508674) <br> <small> **Keywords:** reachability analysis, compositional methods, nonlinear control systems, SpaceEx. </small>

3. *Constructing Verification Models of Nonlinear Simulink Systems via Syntactic Hybridization.*  <br> Nikolaos Kekatos, M. F., Goran Frehse.<br>  Accepted in 56th IEEE Conference on Decision and Control, held in Melbourne, Australia (2017). <br> Download pre-print: [[HAL]](https://hal.archives-ouvertes.fr/hal-01487658), [[local copy]]({{site.url}}/assets/papers/synlin_v2.pdf).

---

## Mathematical Optimization

1. *Occupation measure methods for modelling and analysis of biological hybrid systems*. <br> Alexandre Rocca, M. F., Victor Magron, Eric Fanchon, Thao Dang.<br>
In [6th IFAC Conference on Analysis and Design of Hybrid Systems (ADHS 18)](https://www.cs.ox.ac.uk/conferences/ADHS18/) to be held in Oxford, UK, July 11-13, 2018.
<br> Download pre-print: [[arXiv - cs.SY]](https://arxiv.org/abs/1710.03158).<br>
<small> **Keywords:** biological modelling, hybrid dynamical system, optimal control problem, semidefinite optimization, occupation measures. </small>

2. *Semidefinite Characterization of Invariant Measures for  Polynomial Systems*.
<br> Victor Magron, M. F., Didier Henrion. <br>
Presented in [18th French-German-Italian conference on Optimization](https://math.uni-paderborn.de/ag/mathematik-und-ihre-anwendungen/fgi-2017/), held in Paderborn, Germany (2017).
<br> Download pre-print: [[arXiv - math.DS]](https://arxiv.org/abs/1807.00754).<br>
<br> <small> **Keywords:** invariant measures, dynamical systems, polynomial optimization, semidefinite programming, moment-sum-of-square relaxations, Christoffel function. </small>

---

## Quantum Random Walks

1. *Quantum Walking in Curved Spacetime.* <br> Pablo Arrighi, Stefano Facchini, M. F. <br>  Quantum Information Processing [(2016) 15: 3467](http://link.springer.com/article/10.1007/s11128-016-1335-7). <br> Download pre-print: [[arXiv - quant-ph]](https://arxiv.org/abs/1505.07023). <br> <small> **Keywords:** paired QWs, lattice quantum field theory, quantum simulation. </small>

2. *Discrete Lorentz covariance for Quantum Walks and Quantum Cellular Automata.* <br> Pablo Arrighi, Stefano Facchini, M. F. <br> New Journal of Physics  [16 (2014) 093007](http://iopscience.iop.org/1367-2630/16/9/093007/). <br> Download pre-print: [[arXiv - quant-ph]](http://arxiv.org/abs/1404.4499). <br> <small> **Keywords:** discrete Lorentz transformation, local Lorentz covariance, special relativity, observer equivalence, circuit transformation, Lorentz boosts. </small>

3. *The Dirac equation as a quantum walk: higher dimensions, observational
convergence.* <br> Pablo Arrighi, Vincent Nesme and M. F. <br> J. Phys. A: Math. Theor. 47 [(2014) 465302](http://iopscience.iop.org/1751-8121/47/46/465302/) <br> Download pre-print: [[arXiv - quant-ph]](http://arxiv.org/abs/1307.3524). <br> <small> **Keywords:** Friedrichs symmetric hyperbolic systems, quant
um walk, quantum lattice gas automata, quantum computation, Trotter-Kato, Baker-Campbell-Thomson, operator splitting, Lax theorem. </small>

4. *Spatial quantum search in a triangular network.* <br> Gonzalo Abal, Raul Donangelo, M. F., Renato Portugal. <br> Mathematical
Structures in Computer Science,  [22, pp 521-531, Cambridge
University Press](http://journals.cambridge.org/action/displayAbstract?fromPage=online&aid=8544748&fileId=S0960129511000600) <br>
Download pre-print: [[arXiv - quant-ph]](http://arxiv.org/abs/1009.1422).

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
