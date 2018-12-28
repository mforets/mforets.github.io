---
layout: post
title:  "JuMP-dev Upcoming Workshop"
date: 2018-12-27
categories: upcoming_event
tags: conference, optimization
---

The [Third Annual JuMP-dev Workshop](https://www.juliaopt.org/meetings/santiago2019/)
will be held from 12 to 14 March, 2019 in Santiago, Chile. The steering committee of
this workshop includes lead developers of the JuMP (Julia Mathematical Programming) ecosystem,
that come, among other institutions from Google and Rice University, Northwestern, UCLouvain,
PSR & PUC-Rio and the Massachusetts Institute of Technology (MIT).

I've registered to this event (registration is free!) and proposed a talk, see below.
I look forward to participating - particularly since the venue is not far from my place-
although it is too early to confirm yet.

The talk that I have proposed concerns flowpipe construction. Flowpipe construction
consists of under or over-approximating the sets of states reachable by dynamical systems.

As it turns out, a method has been recently developed for the class of polynomial ODEs with uncertain initial states
(see [1], abbreviated XFZ18under, and earlier references therein).
This method consists of reducing the Hamilton-Jacobi-Bellman equation to a hierarchy of semidefinite programs.

[In this notebook](https://nbviewer.jupyter.org/github/mforets/escritoire/blob/master/reachability/XFZ18under.ipynb)
I've considered the problem of approximating the flowpipe of a system of polynomial ODEs using XFZ18under. This is a Julia implementation that relies on the JuMP ecosystem (`JuMP`, `PolyJuMP`, `SumOfSquares`, `MathProgInterface`, `MathOptInterfaceMosek`) and the JuliaAlgebra ecosystem (MultivariatePolynomials, DynamicPolynomials). The plots are generated with `ImplicitEquations`.
