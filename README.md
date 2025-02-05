# CSS `calc()` Function Errors

This repository demonstrates common errors encountered when using the `calc()` function in CSS and provides solutions.

The `bug.css` file shows examples of incorrect usage, such as inconsistent unit mixing and relying on implicit parent container dimensions.

The `bugSolution.css` file provides corrected implementations, ensuring accurate calculations.

## Issues Addressed

* **Inconsistent Units:**  The `calc()` function throws errors if you mix units inconsistently (e.g., `px` and `%`).
* **Undefined Parent Dimensions:** Incorrect calculation results if the parent container's width or height is not specified.

## Solutions

* Ensure consistent units in all parts of the `calc()` expression.
* Explicitly set the dimensions of the parent container using `width` and `height` properties.
* Thoroughly test your `calc()` expressions across different screen sizes.