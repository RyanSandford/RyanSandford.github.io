---
layout: page
title: Regular Chains Library Developer
description: Developed tools for the regular chains library
img: /assets/img/regular_chains_thumbnail.png
importance: 2
category: work
---

__Regular chains__ are a powerful tool whose main application lies
in solving systems of polynomial equations, inequations,
and inequalities, symbolically. Loosely, regular chains
are triangular systems of polynomial equations with
desirable computational properties.
A formal definition of a regular chain and a description of its properties
and implementation in Maple can be found [here](https://www.maplesoft.com/support/help/maple/view.aspx?path=RegularChains).

I have been developing commands in the
_AlgebraicGeometryTools_ sub-package of the _RegularChains_ library. In particular,
my work concerns the _IntersectionMultiplicity_, _TangentCone_, and _TriangularizeWithMultiplicity_
commands, where I have introduced new, underlying algorithms and improved the implementation
of previous algorithms. A paper on this work and the resulting performance improvements,
is underway and will be made available shortly.
For now, the corresponding slides can be found [here](https://ryansandford.github.io/assets/pdf/MC2021_slides.pdf).

The _RegularChains_ library is available through [Maple](https://www.maplesoft.com/products/Maple/) or through the regular chains website [here](http://www.regularchains.org/).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/regular_chains_thumbnail.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    The LimitPoints command uses regular chains to compute the limit points of a space curve.
    Here the space curve (in green) is defined by the intersection of the red and blue surfaces,
    with limit points (0,0,0) and (0,1,0).
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/tc.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
  The TangentCone command uses regular chains to compute the tangent cone of a space curve. The
  resulting tangent cone is displayed here in green.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-9 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/mth191.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    The TriangularizeWithMultiplicity command can be used to solve a system of polynomial equations
    and compute the intersection multiplicity at each solution. Above we display the polynomial system mth191, for which TriangularizeWithMultiplicity returns 8 solutions in the form of regular chains, and their corresponding
    intersection multiplicities.
</div>
