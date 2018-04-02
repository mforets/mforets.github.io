---
layout: post
title:  "Joining Hybrid Systems: Computation and Control (HSCC2018)"
date: 2018-04-02
categories: upcoming_event
---

This year's [21st ACM International Conference on Hybrid Systems: Computation and
Control (HSCC 2018) will take place in Porto, the 11-13 April 2018](https://www.hscc2018.deib.polimi.it/),
and our paper Reach Set Approximation through Decomposition with Low-dimensional Sets and High-dimensional Matrices,
together with Sergiy Bogomolov, Goran Frehse, Andreas Podelski, Christian Schilling and Frédéric Viry,
has been accepted for publication in this conference. The talk will be given by Christian.

Below you'll find the abstract of the contribution; the arXiv (but not definitive) version is [1801.09526](https://arxiv.org/abs/1801.09526).

> Approximating the set of reachable states of a dynamical system is an algorithmic yet mathematically rigorous way to reason about its safety. Although progress has been made in the development of efficient algorithms for affine dynamical systems, available algorithms still lack scalability to ensure their wide adoption in the industrial setting. While modern linear algebra packages are efficient for matrices with tens of thousands of dimensions, set-based image computations are limited to a few hundred. We propose to decompose reach set computations such that set operations are performed in low dimensions, while matrix operations like exponentiation are carried out in the full dimension. Our method is applicable both in dense- and discrete-time settings. For a set of standard benchmarks, it shows a speed-up of up to two orders of magnitude compared to the respective state-of-the art tools, with only modest losses in accuracy. For the dense-time case, we show an experiment with more than 10.000 variables, roughly two orders of magnitude higher than possible with previous approaches.

Further information and examples about the software of this project, go to the github page
of [JuliaReach](https://github.com/JuliaReach/). In particular, to know more about
existing and planned algorithms for reachability computations you can follow the project
[Reachability.jl](https://github.com/JuliaReach/Reachability.jl). Contributions are welcome as well!
