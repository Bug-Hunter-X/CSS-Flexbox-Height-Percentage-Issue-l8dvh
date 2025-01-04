# CSS Flexbox Height Percentage Issue

This repository demonstrates an uncommon issue encountered when using percentage-based heights within CSS flexbox containers.  The child element's height does not expand to fill the container's height despite being set to 100%.  This unexpected behavior is investigated and a solution is provided.

**Bug:** The `bug.css` file contains the problematic CSS. The height of the '.box' element inside the flexbox '.container' does not expand to fill the container's height.

**Solution:** The `bugSolution.css` file offers a solution to this issue. The solution involves using the flexbox property `height: 100%;` on the container and modifying the sizing strategies for inner elements to utilize flex properties and ensure height expansion.

Feel free to explore the CSS files to understand the issue and its resolution.