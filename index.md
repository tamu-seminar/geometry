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

This seminar meets on Fridays 4:00-5:00 PM in Blocker 302.

The organizers are [Frank Sottile](https://franksottile.github.io/) and others.


| Date         | Speaker | Title |  Other |
|--------------|---------|-------|-------|
| August 29, 2025   |  Sample speaker       | Sample Title  | <span class="abstract-link" onclick="showAbstract('abs-sample')">View Abstract</span>  |
| September 5, 2025 |         |       |   No seminar (promotion talks)    |
| September 12, 2025|         |       |   No seminar (promotion talks)    |
| September 19, 2025|  |  |       |
| September 26, 2025|         |       |       |
| October 3, 2025   |         |       |       |
| October 10, 2025  |         |       |       |
| October 17, 2025  |         |       |       |
| October 24, 2025  |         |       |       |
| October 31, 2025  |         |       |       |
| November 7, 2025  |         |       |       |
| November 14, 2025 |         |       |       |
| November 21, 2025 |         |       |       |
| November 28, 2025 |         |       |  No seminar (Thanksgiving)     |
| December 5, 2025  |         |       |       |



# Related Links

- [Departmental seminar website](https://artsci.tamu.edu/mathematics/research/seminars/algebra-combinatorics/index.html) (not working as of Aug 13, 2025)
- [Departmental website of the algebra and combinatorics group](https://artsci.tamu.edu/mathematics/research/algebra-combinatorics/index.html#Algebra%20and%20Combinatorics) (very out of date of Aug 13, 2025)













<!-- Abstract content -->

<div id="abs-sample" style="display:none;">
This is a sample abstract. It also renders LaTeX $\binom{n}{k}$.
</div>


<!-- Code that makes the pop-up windows -->

<style>
.abstract-link {
  color: blue;
  text-decoration: bold;
  cursor: pointer;
}
</style>

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
