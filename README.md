# CSS `calc()` Errors

This repository demonstrates common errors encountered when using the CSS `calc()` function, specifically focusing on unit mismatches and missing spaces.  Incorrect usage can lead to unexpected layout behavior and debugging challenges.

The `bug.css` file showcases the problematic code, while `bugSolution.css` provides corrected versions.

**Issues:**
* **Missing Spaces:**  Spaces are crucial in `calc()` operations.  Missing spaces around operators can lead to parsing errors.
* **Unit Mismatch:** Inconsistent units (e.g., mixing `px` and `%`) within the `calc()` expression can cause unexpected results.

**Solutions:**
* **Ensure correct spacing** around the operators (+, -, *, /) within the `calc()` function.
* **Maintain consistent units** throughout the calculation.

This example highlights the importance of paying attention to detail when using the powerful `calc()` function in CSS.