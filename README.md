# Unexpected Behavior with CSS `calc()`
This repository demonstrates an uncommon issue related to the CSS `calc()` function.  Incorrect spacing, missing units, or incompatible unit types within the calculation can lead to unpredictable results.  The `bug.css` file shows examples of these problems, while `bugSolution.css` provides the correct implementations.

The primary problems are:

* **Unexpected Spaces:** Spaces within the `calc()` function's arguments can invalidate the calculation.
* **Missing Units:**  Units are essential in `calc()` calculations. Omitting them leads to errors.
* **Incompatible Units:**  While you can mix percentages and pixels, inconsistent mixing of units may produce unexpected results.

This example highlights the importance of careful syntax and consistent unit usage when employing the `calc()` function in CSS.