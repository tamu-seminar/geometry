---
layout: default
---

<script>
  window.MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$', '$$'], ['\\[', '\\]']]
    },
    svg: { fontCache: 'global' }
  };
</script>
<script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js" async></script>


# Fall 2025

This seminar meets on Mondays 3:00-3:50 PM and Fridays 4:00-4:50 PM in Blocker 302.

The organizers are [Frank Sottile](https://franksottile.github.io/) and others.


| Date         | Speaker | Affiliation| Title | Other |
|--------------|---------|------------|-------|-------|
| August 25, 2025   |  Justin Lacini  | Texas A&M  | Logarithmic bounds on Fujita's conjecture | <span class="abstract-link" onclick="showAbstract('Lacini')">View Abstract</span>  |
| August 29, 2025   |      |   | No seminar  |  (promotion talks)  |
| September 5, 2025 |      |   | No seminar  | (promotion talks)    |
| September 12, 2025|      |   | No seminar | (promotion talks)    |
| September 22, 2025| Matthew Faust | Michigan State |  Algebraic Geometry in the Study of the Eigenvalues of Discrete Periodic Operators|   <span class="abstract-link" onclick="showAbstract('Faust')">View Abstract</span>  ddd TBA     |
| September 25, 2025| Jordy Lopez   | Notre Dame    |  Toric compactifications of periodic graph operators | <span class="abstract-link" onclick="showAbstract('Lopez')">View Abstract</span>  Special time, Thursday 11-12 Bloc 605AX  |
| October 6, 2025   | [Debaditya Raychadhury](https://rcdeba.github.io/) | University of Arizona  |   Singularities of Secant varieties   |   <span class="abstract-link" onclick="showAbstract('Raychadhury')">View Abstract</span>    |
| October 10, 2025  |      |   |      |       |
| October 17, 2025  |      |   |      |       |
| October 24, 2025  |      |   |      |       |
| October 31, 2025  |      |   |      |       |
| November 3, 2025  | [Thomas Tony](https://ttony.eu/)   | University of M&uuml;nster  |       | Monday      |
| November 14, 2025 |      |   |       |       |
| November 21, 2025 |      |   |       |       |
| November 28, 2025 |      |   |       |  No seminar (Thanksgiving)     |
| December 5, 2025  |      |   |       |       |


# Related Links

- [Departmental seminar website]() (not working as of Aug 13, 2025)
- [Departmental website of the geometry and topology](https://artsci.tamu.edu/mathematics/research/geometry-and-topology/) (very out of date of Aug 13, 2025)













<!-- Abstract content -->

<div id="Lacini" style="display:none;">
A longstanding conjecture of T. Fujita asserts that if $X$ is
a smooth complex projective variety of dimension $n$ and if $L$ is an
ample line bundle, then $K_X+mL$ is basepoint free for $m\geq n+1$. The
conjecture is known up to dimension five by work of Reider, Ein,
Lazarsfeld, Kawamata, Ye and Zhu. In higher dimensions, breakthrough
work of Angehrn, Siu, Helmke and others showed that the conjecture
holds if $m$ is larger than a quadratic function in $n$. We show that for
$n\geq 2$ the conjecture holds for $m$ larger than $n(\log\log(n)+3)$. This is
joint work with L. Ghidelli.
</div>



<!-- Abstract content -->

<div id="Faust" style="display:none;">
 Given a periodic graph $G$, we consider a class of discrete periodic operators given by the sum of a weighted adjacency
 operator and a potential. We wish to study the spectrum of this operator acting on the Hilbert space of square-summable
 functions on the vertices of $G$. By Floquet theory, the spectrum can be realized as the projection of a finite number of
 band functions. If one of these band functions is constant, the operator is said to have a flat band, corresponding to
 eigenvalues of infinite multiplicity. In this talk, we will introduce the relevant background and discuss recent results
 that demonstrate that, generically, discrete periodic operators do not exhibit flat bands. This is based on joint work
 with Wencai Liu.
</div>



<!-- Abstract content -->

<div id="Lopez" style="display:none;">
A periodic graph operator is a weighted Laplacian plus potential acting on functions on
the vertices of a periodic graph. It is well-known that the spectrum of a periodic graph
operator is the projection of an affine algebraic variety known as the Bloch
variety. Motivated by Bättig, we compactify the Bloch variety of a periodic graph operator
inside the normal toric variety associated to its Newton polytope. For a family of
periodic graphs, we extend this operator to such toric variety by expressing the
compactification as the support of a kernel sheaf. We outline a few spectral-theoretic
consequences of this compactification. This is joint work with Matthew Faust (MSU),
Stephen Shipman (LSU), and Frank Sottile.
</div>


<!-- Abstract content -->

<div id="Raychadhury" style="display:none;">
 Secant varieties are classical objects in algebraic
geometry. Given a smooth projective variety inside a projective space,
its secant variety is by definition the closure of the union of secant
lines. It is almost always singular and sits inside the same
projective space by its construction. In this talk, we will discuss
the singularities of secant varieties when the embedding is
sufficiently positive. In particular, we will study the Du Bois
complex of secant varieties and will also discuss about its local
cohomology modules. The results are obtained in various collaborations
with Q. Chen, B. Dirks, S. Olano and L. Song.
</div>


<!-- Code that makes the pop-up windows -->

<style>
/* Modal background */
#abstract-modal-overlay {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.5);
  display: none;
  z-index: 1000;
}

/* Modal box */
#abstract-modal {
  background: white;
  width: 80%;
  max-width: 700px;
  margin: 5% auto;
  padding: 20px;
  border-radius: 8px;
  position: relative;
  overflow-y: auto;
  max-height: 90vh;
  font-family: Arial, sans-serif;
}

/* Close button */
#abstract-modal-close {
  position: absolute;
  top: 10px;
  right: 15px;
  font-size: 20px;
  cursor: pointer;
}
</style>

<!-- Modal structure -->
<div id="abstract-modal-overlay" onclick="closeAbstractModal(event)">
  <div id="abstract-modal" onclick="event.stopPropagation()">
    <span id="abstract-modal-close" onclick="closeAbstractModal()">&times;</span>
    <h2>Abstract</h2>
    <div id="abstract-modal-content"></div>
  </div>
</div>

<script>
function showAbstract(id) {
  const content = document.getElementById(id).innerHTML;
  document.getElementById('abstract-modal-content').innerHTML = content;
  document.getElementById('abstract-modal-overlay').style.display = 'block';
}

function closeAbstractModal(event) {
  if (!event || event.target.id === 'abstract-modal-overlay' || event.target.id === 'abstract-modal-close') {
    document.getElementById('abstract-modal-overlay').style.display = 'none';
  }
}
</script>
