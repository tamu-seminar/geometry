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
| August 24, 2027 | Samuel Sottile | Stanford | Lagrangian Fibrations in High Dimensions <button type="button" class="abstract-link" onclick="showAbstract('SSottile')">View Abstract</button> | |
| August 28, 2027 | [Sung Gi Park](https://sites.google.com/view/sunggipark/) | Princeton | From GIT to Baily-Borel: Moduli of hypersurfaces via minimal exponents <button type="button" class="abstract-link" onclick="showAbstract('Park')">View Abstract</button> | 11&dash12 Note special time |
| August 31, 2027 | Phil Speegle | Texas A&M | TBA  <button type="button" class="abstract-link" onclick="showAbstract('Speegle')">View Abstract</button>| |
| September 4, 2027 | | Promotion talk  | | |
| September 7, 2027 | | | | |
| September 11, 2027 | | Promotion talk  | | |
| September 14, 2027 | [Shend Zhjeqi](https://shend-zh.github.io/.github.io/) | University of Michigan | TBA | |
| September 18, 2027 | | Promotion talk  | | |
| September 21, 2027 | | | | |
| September 25, 2027 | | Promotion talk  | | |
| September 28, 2027 | | | | |
| October 2, 2027 | | | | |
| October 5, 2027 | | | | |
| October 9, 2027 | | | | |
| October 12, 2027 | | | | |
| October 16, 2027 | | | | |
| October 19, 2027 | | | | |
| October 23, 2027 | | | | |
| October 26, 2027 | | | | |
| October 30, 2027 | | SIAM TX-LA | | |
| November 2, 2027 | | | | |
| November 6, 2027 | | | | |
| November 9, 2027 | | | | |
| November 13, 2027 | | | | |
| November 16, 2027 | | | | |
| November 20, 2027 | | | | |
| November 23, 2027 | | | | |
| November 30, 2027 | | | | |
| December 4, 2027 | | | | |

<!-- # Past Seminars  -->
[Spring 2026](2026_1.md)
[Fall 2025](2025_2.md)



<!-------------------------------------    Abstract content    --------------------------------------->

<!---------------------------------------------------------------------------------------------------->
<div id="SSottile" style="display:none;" aria-hidden="true">
  <p> The SYZ conjecture posits that special Lagrangian fibrations provide a geometric explanation for mirror symmetry.
  On the purely symplectic side, non-special Lagrangian torus fibrations provide a useful framework for understanding the geometry of symplectic manifolds.
  However, there is no general theory of these fibrations in dimensions higher than four, in part due to a dearth of examples.
  This limits many applications to four dimensions.
  </p>
  <p>
  In this talk, I will present my work on constructing Lagrangian torus fibrations in all dimensions.
  I will show that many complete intersections in toric varieties admit such fibrations.
  For example, Batyrev-Borisov mirror pairs have dual Lagrangian torus fibrations.
  I will also show that all Fano threefolds admit Lagrangian torus fibrations with base the three dimensional ball.
 </p>
</div>

<!---------------------------------------------------------------------------------------------------->
<div id="Park" style="display:none;" aria-hidden="true">
  <p> The moduli space of smooth hypersurfaces in projective space
can be constructed as a GIT quotient by linear changes of coordinates,
and it comes with a natural GIT compactification. In certain degrees
and dimensions, Hodge theory provides a second compactification via
the period map, namely the Baily-Borel compactification. Building on
recent progress on higher singularities and a new stability criterion
formulated in terms of the minimal exponent (a refinement of the log
canonical threshold), I will discuss the birational geometry of these
two compactifications and describe consequences for the boundary
behavior of the period map.
 </p>

</div> 
<!---------------------------------------------------------------------------------------------------->

<!---------------------------------------------------------------------------------------------------->
<div id="Speegle" style="display:none;" aria-hidden="true">
  <p> TBA
 </p>
</div>
<!---------------------------------------------------------------------------------------------------->


<!---------------------------------------------------------------------------------------------------->
<div id="" style="display:none;" aria-hidden="true">
  <p> TBA
 </p>
</div>
<!---------------------------------------------------------------------------------------------------->

---------------------------------------------------------------------------------------------------->


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
