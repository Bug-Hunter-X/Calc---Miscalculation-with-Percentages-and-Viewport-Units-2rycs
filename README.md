# CSS `calc()` Miscalculation Bug

This repository demonstrates a bug related to unexpected calculations using the CSS `calc()` function with percentages and viewport units (like `vw` or `vh`). The issue arises when combining these units within a single `calc()` expression, leading to incorrect sizing or positioning of elements.

## Bug Description
The provided `bug.css` file contains CSS rules that illustrate the miscalculation. The expected behavior is described in the comments within the file. However, the actual behavior differs, resulting in unexpected layout.

## Solution
The `bugSolution.css` file provides a possible solution to address the issue.  This could involve using alternative calculation methods or restructuring the CSS to avoid the problematic combination of units within `calc()`.  The solution might depend on the specific browser and its interpretation of the `calc()` function.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the layout and compare it to the expected behavior documented in `bug.css`.
4. Examine `bugSolution.css` for a potential workaround or fix.