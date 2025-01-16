# CSS Pseudo-element Rendering Issue

This repository demonstrates a subtle CSS bug related to the use of pseudo-elements (`:before` or `:after`) without explicitly specifying content.  The lack of content can cause the pseudo-element to be ignored by the browser, resulting in unexpected styling issues.

The `bug.css` file contains the erroneous code. The solution is provided in `bugSolution.css`.