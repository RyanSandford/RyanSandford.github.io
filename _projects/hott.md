---
layout: page
title: Lean 3 Homotopy Type Theory Library Contribution
description: Contributed formalized proofs regarding the notion of the 2-adjoint equivalence to the open source Homotopy Type Theory Library in Lean 3
img: /assets/img/HOTT_thumbnail.png
importance: 3
category: work
---

__Homotopy Type Theory (HoTT)__ is an intuitionistic type theory which views types
as abstract, homotopy-invariant objects. As remarked in the HoTT book,
this correspondence is quite remarkable as it provides a link between
homotopy theory (which is related to algebraic topology, homological algebra, and higher category theory)
and type theory, a field of mathematical logic and theoretical computer science.
HoTT provides a type-theoretic foundation to
mathematics rather then the conventional set theoretic foundation.
This in turn, allows for proofs within HoTT to be formalized and
understood by a computer via a proof assistant.

During the summer of 2019, myself, Daniel Carranza, and Jonathan Chang, under the supervision of
Chris Kapulkin, began exploring the notion of __2-adjoint equivalences__ and coherences between types.
This resulted in the construction, proof, and formalization of many properties one would expect
from a 2-adjoint equivalence. The following summer the remaining properties were formalized by Daniel
Carranza. The final, formalized proofs were added to the
[HoTT in Lean 3 library](https://github.com/gebner/hott3) and can be found in
the [2adj](https://github.com/gebner/hott3/tree/master/src/hott/types/2_adj) directory.
Moreover, a [paper](https://lmcs.episciences.org/7124) describing the 2-adjoint equivalence and its formalization was
published to the journal of Logical Methods in Computer Science.
Additional links are provided in the [publication](https://ryansandford.github.io/publications/) section of this site.



<div class="row">
    <div class="col-sm-7 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/homotopy.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-5 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/homotopyhomotopy.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Proving equality between types corresponds to showing there is a path between spaces (more specifically,
      that the path space is inhabited). We can also prove equality of path
      spaces by considering paths between paths, as we see in the first image, and equality of
      paths between paths by showing there is a path between paths between paths, as we
      see in the second image.

</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/HoTT_table.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Table 1 is provided in section 1 of the HoTT book and provides a comparison between sets, types, logic, and homotopies.
</div>

A well written and informal introduction to HoTT can be found [here](http://www.science4all.org/article/homotopy-type-theory/).
The author also provides some very nice visualizations (including the thumbnail of this project).

<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/Hott_book_cover.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    The Homotopy Type Theory Book.
</div>

__Useful Links:__

* [HoTT website](https://homotopytypetheory.org)

* [HoTT book](https://homotopytypetheory.org/book/)

* [HoTT wikipedia page](https://en.wikipedia.org/wiki/Homotopy_type_theory)

* [Lean 3 Theorem Prover](https://github.com/leanprover/lean)
