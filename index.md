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
| August 24, 2027 |  |  | | |
| August 28, 2027 |  |  | | |
| August 31, 2027 |  |  | | |
| September 4, 2027 | | | | |
| September 7, 2027 | | | | |
| September 11, 2027 | | | | |
| September 14, 2027 | | | | |
| September 18, 2027 | | | | |
| September 21, 2027 | | | | |
| September 25, 2027 | | | | |
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



<!------- Abstract content ------->

<!---------------------------------------------------------------------------------------------------->

<!---------------------------------------------------------------------------------------------------->

<!---------------------------------------------------------------------------------------------------->


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
