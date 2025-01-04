# CSS `calc()` Unexpected Behavior

This repository demonstrates an uncommon issue encountered when using the CSS `calc()` function to combine percentages and `em` units.  The `calc()` function, while powerful, can sometimes produce unexpected results in certain contexts.  This issue can be particularly subtle and difficult to debug.

The `bug.css` file showcases the problem, while the `bugSolution.css` file offers potential solutions and workarounds.

**Problem:** Inconsistent width calculations when the parent element has a dynamically changing width. 

**Solutions:**  Explore alternative approaches to achieve the desired layout, potentially using viewport units or different length units.