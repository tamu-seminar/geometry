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


# Spring 2026

This seminar meets on Mondays 3:00-3:50 PM and Fridays 4:00-4:50 PM in Blocker 302.

The organizers are [Frank Sottile](https://franksottile.github.io/) and others.


| Date         | Speaker | Affiliation| Title | Other |
|--------------|---------|------------|-------|-------|
| January 12, 2026 | [Gregory Berkolaiko](https://people.tamu.edu/~gberkolaiko/) | Texas A&M | Ritz energy landscape is perfect (almost) Morse | <button type="button" class="abstract-link" onclick="showAbstract('Berkolaiko')">View Abstract</button> |
| January 19, 2026 |  | MLK Day | | |
| January 23, 2026 | [Frank Sottile](https://franksottile.github.io/) |Texas A&M | Monodromy in the Osculating Schubert Calculus | <button type="button" class="abstract-link" onclick="showAbstract('Sottile')">View Abstract</button>  |
| January 30, 2026 3:00 PM |[Luca Di Cerbo](https://people.clas.ufl.edu/ldicerbo/) | Florida |Curvature, Macroscopic Dimensions, and Symmetric Product of Curves |  <button type="button" class="abstract-link" onclick="showAbstract('DiCerbo')">View Abstract</button>|
| January 30, 2026 4:00 PM|[Ikenna Nometa](https://www.ikennanometa.com/) | Georgia Tech | Degrees of the Wasserstein distance to small toric models| <button type="button" class="abstract-link" onclick="showAbstract('Nometa')">View Abstract</button> |
| February 6, 2026 | Jinhyung Park | KAIST | Determinantal ideals of secant varieties |<button type="button" class="abstract-link" onclick="showAbstract('Park')">View Abstract</button>  |
| February 16, 2026 | | | | |
| February 20, 2026 | | | | |
| February 23, 2026 |  Jie Xu | Northeastern University | A Series of Rosenberg-Stolz Conjectures |  <button type="button" class="abstract-link" onclick="showAbstract('JieXu')">View Abstract</button>|
| February 26, 2026 | [Francis Su](https://www.francissu.com/) | Harvey Mudd College | | [Geller Lecture](https://sites.google.com/tamu.edu/geller-lecture-2026/home) <br><br> Special day and time: <br> 6 PM, Blocker 117 |
| February 27, 2026 | Monica Kang| TAMU Physics| | |
| March 2, 2026 |  [Frank Sottile](https://franksottile.github.io/) | Texas A&M | Welschinger signs and Webs of maximally inflected curves | <button type="button" class="abstract-link" onclick="showAbstract('Sottile2')">View Abstract</button> |
| March 6, 2026 | | | | |
| March 9, 2026 | | Spring Break | | |
| March 13, 2026 | | Spring Break | | |
| March 16, 2026 | Shrawn Kumar | UNC Chapel Hill | | |
| March 20, 2026 | Suhas Gondi| UC San Diego | | |
| March 23, 2026 | | | | |
| March 27, 2026 | | | | |
| March 30, 2026 | | | | |
| April 3, 2026 | | Good Friday | | |
| April 6, 2026 | | | | |
| April 10, 2026 | Nathan Chen | Harvard | | |
| April 13, 2026 | | | | |
| April 17, 2026 | | [TAGS](https://franksottile.github.io/conferences/TAGS26/index.html) | | |
| April 20, 2026 | | | | |
| April 24, 2026 | Iacopo Brivio | CMSA Harvard | | |
| April 27, 2026 | | | | |

<!-- # Past Seminars  -->
[Fall 2025](2025_2.md)




<!------- Abstract content ------->

<div id="Berkolaiko" style="display:none;" aria-hidden="true">
  <p>The Rayleigh-Ritz method approximates the eigenvalues of a large
Hermitian matrix $B$ with Ritz values, which are the eigenvalues of $B$'s
restriction to a smaller trial subspace $S$.  We can view the $k$-th
Ritz value as a real-valued function ("Ritz energy landscape") on the
manifold of all possible s-dimensional trial subspaces, the
Grassmannian $Gr_s(C^n)$ (or $Gr_s(R^n)$ for the real symmetric case).
</p><p>
Motivated by questions from quantum chemistry and spectral
optimization, this talk explores the topology of the Ritz energy
landscape. A Morse function is called "perfect" if it describes the
topology of its domain in the most efficient way possible, meaning the
number of its critical points of each type exactly matches the
corresponding Betti number of the space.  We demonstrate that for a
matrix $B$ with distinct eigenvalues, the Ritz landscape is indeed
perfect. While the function itself is not everywhere smooth and its
critical points are not isolated --- and not even Morse-Bott --- its
critical structure is nevertheless well-defined and ultimately
reflects the topology of the Grassmannian in a minimal, perfect way.
</p><p>
To be more precise, we show that the filtration of the Grassmannian by
the sublevel sets of the $k$-th Ritz value is homologically perfect.
The proof proceeds by introducing a suitable perturbation which
ensures that points of non-smoothness are not critical (by a theorem
of Zelenko and the presenter) and that the remaining smooth critical
points are isolated.
</p>
<p>Based on a joint work with Mark Goresky (IAS).
</p>
</div>

<!---------------------------------------------------------------------------------------------------->

<div id="Sottile" style="display:none;" aria-hidden="true">
  <p>
An  important special  case of  Schubert calculus  for the  Grassmannian
concerns flags osculating the rational normal curve, which is equivalent
to the  Bethe Ansatz  in the  Gaudin model for  $\mathfrak{gl}_d$.  The  most natural
family of  these problems are  indexed by partitions $\lambda$.   Liao and
Rybnikov  recently studied  a subgroup  of the  monodromy group  for the
Bethe Ansatz  equivalent to the action  of the cactus group  on standard
Young tableau of shape $\lambda$.  When $\lambda$ is a hook or is symmetric,
they  showed that  it  was  not 2-transitive,  but  was otherwise  giant
(contains the alternating group).
</p>
<p>
I will describe  this background and then give  some geometric arguments
which  refine their  work on  hooks and  symmetric partitions,  and then
present  some computational  evidence that  Harris's principle  holds in
that the monodromy is a large as possible.  This is based on joint work with Leonid Rybnikov (UdeM).
</p>
</div>

<!---------------------------------------------------------------------------------------------------->

<div id="DiCerbo" style="display:none;" aria-hidden="true">
  <p>
n this talk, I will present a detailed study of the curvature and symplectic asphericity properties of symmetric products of curves. I show that these spaces can be used to answer nuanced questions arising in the study of closed Riemannian manifolds with positive scalar curvature. For example, symmetric products of curves sharply distinguish between two distinct notions of macroscopic dimension introduced by Gromov and Dranishnikov. As a natural generalization of this circle of ideas, I will also address the Gromov–Lawson and Gromov conjectures in the Kaehler projective setting and draw new connections between the theories of the minimal model, positivity in algebraic geometry, and macroscopic dimensions. This is joint work with Alexander Dranishnikov and Ekansh Jauhari.
</p>
</div>

<!---------------------------------------------------------------------------------------------------->


<!---------------------------------------------------------------------------------------------------->

<div id="Nometa" style="display:none;" aria-hidden="true">
  <p>
The study of the closest point(s) on a statistical model from a given distribution in the probability simplex with respect to a fixed Wasserstein metric yields a polyhedral norm-distance optimization problem.
There are two components to the complexity of computing the Wasserstein distance between a data point and a model.
One is the combinatorial complexity, governed by the combinatorics of the Lipschitz polytope of the finite metric to be used.
Another is the algebraic complexity, which is governed by the polar degrees of the Zariski closure of the model.
In this talk, I will discuss the formulas for the polar degrees of rational normal scrolls and graphical models whose underlying graphs are star trees.
If time permits, I will discuss our efforts to compute polar degrees for graphical models with four binary random variables, including the path on four vertices and the four-cycle, as well as for small, no-three-way-interaction models.
</p>
<p>
This talk is based on a joint work (<a href="https://msp.org/astat/2024/15-2/astat-v15-n2-p05-s.pdf">DOI: 10.2140/astat.2024.15.249</a>) with Greg DePaul, Serkan Hoşten, and Nilava Metya
</p>
</div>

<!---------------------------------------------------------------------------------------------------->

<div id="Park" style="display:none;" aria-hidden="true">
  <p>
We show that the homogeneous ideals of secant varieties of smooth projective curves and surfaces in sufficiently ample embeddings are determinantally presented. The same result holds for the first secant varieties of arbitrary smooth projective varieties in sufficiently ample embeddings. This completely settles a conjecture of Eisenbud-Koh-Stillman for curves and partially resolves a conjecture of Sidman-Smith in higher dimensions. To establish the results, we employ the geometry of Hilbert schemes of points. Based on our method, we also prove that the homogeneous ideals of arbitrary projective schemes in sufficiently ample embeddings are generated by quadrics of rank three, confirming a conjecture of Han-Lee-Moon-Park. This is joint work with Daniele Agostini.
</p>
</div>

<!---------------------------------------------------------------------------------------------------->



<!---------------------------------------------------------------------------------------------------->

<div id="JieXu" style="display:none;" aria-hidden="true">
  <p>
In 1994 and 2006 survey articles, Rosenberg and Stolz stated a series of conjectures by "persisting" non-positive scalar curvature metrics from a closed manifold $ X $ to the product space between $ X $ and a real line, the 2-plane, or a circle, respectively.
There are two classical methods to study this type of problem: one is the method of index-theoretic obstructions, and the other is through geometric measure theory initiated by minimal hypersurfaces, then developed by e.g. Gromov's $ \mu $-bubble method.
</p><p>
In this talk, we introduce a different, conformal geometry and PDE approach to partially answer a series of Rosenberg-Stolz conjectures, and Gromov-Lawson type scalar and mean curvature comparison results for all dimensions from "transposing the positivity" point of view. We also show its application in complex geometry. Some of my work involves collaboration with S. Rosenberg.
</p>
</div>

<!---------------------------------------------------------------------------------------------------->






<!---------------------------------------------------------------------------------------------------->

<div id="Sottile2" style="display:none;" aria-hidden="true">
  <p>

</p>
A 3-dimensional subspace $f$ of real polynomials defines a map $f\colon {\mathbb P}^1 \to {\mathbb P}^2$ whose image is a rational plane curve.
It is maximally inflected when all of its flexes are real, equivalently, when its Wronski determinant has only real roots.
WE associate two {\it a priori} distinct signs ($\pm 1$) to $f$: the Welschinger invariant of the rational curve and the degree of
the Wronski map at $f$.   Extensive computation suggests that these signs coincide.   While studying the conjecture,
we were led to a deeper conjecture:  We define a mixed Wronskian, a function ${\mathbb P}^1 \to {\mathbb P}^1$.  The 
inverse image of the positive reals encodes the real geometry of $f$ and conjecturally is an object called a web.
We conjecture that known bijections between webs and standard Young tableaux and between tableaux with maximally inflected curves 
recovers the curve.
<p>
This talk will explain this  picture with compelling evidence and beautiful
<a href="https://franksottile.github.io/research/stories/webs/42.html">pictures</a>.  It  is joint  work with Brazelton,  Karp, Le,
Levinson, McKean,  Peltola, and Speyer.
</p>
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

<div id="abstract-modal-overlay"
     role="dialog"
     aria-modal="true"
     aria-labelledby="abstract-modal-title"
     style="display:none;"
     onclick="closeAbstractModal(event)">
  <div id="abstract-modal" onclick="event.stopPropagation()">
    <button id="abstract-modal-close"
            aria-label="Close abstract modal"
            onclick="closeAbstractModal()">&times;</button>
    <h2 id="abstract-modal-title">Abstract</h2>
    <div id="abstract-modal-content" tabindex="0"></div>
  </div>
</div>

<script>
function showAbstract(id) {
  const content = document.getElementById(id).innerHTML;
  document.getElementById('abstract-modal-content').innerHTML = content;

  const overlay = document.getElementById('abstract-modal-overlay');
  overlay.style.display = 'block';

  // Move focus into the modal
  document.getElementById('abstract-modal').focus();

  // Add Esc key support
  document.addEventListener('keydown', escCloseHandler);
}

function closeAbstractModal(event) {
  if (!event || event.target.id === 'abstract-modal-overlay' || event.target.id === 'abstract-modal-close') {
    document.getElementById('abstract-modal-overlay').style.display = 'none';

    // Remove Esc key support
    document.removeEventListener('keydown', escCloseHandler);
  }
}

function escCloseHandler(e) {
  if (e.key === 'Escape') {
    closeAbstractModal();
  }
}
</script>
