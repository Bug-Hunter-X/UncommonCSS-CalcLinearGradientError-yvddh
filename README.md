# Uncommon CSS Error: Misuse of calc() in linear-gradient

This repository demonstrates an uncommon error encountered when using the `calc()` function within a CSS `linear-gradient`. The error arises from the incorrect application of `calc()` to define color stop positions in a gradient.

## Bug Description
The provided `bug.css` file contains CSS that attempts to create a gradient where the second color starts 50px from the right. The `calc()` function is incorrectly used to achieve this.  This results in inconsistent rendering across browsers, potential errors, or unexpected results.

## Solution
The `bugSolution.css` file presents the corrected code. Instead of using `calc()` for the color stop position, the gradient's position is calculated properly.  This ensures consistent and accurate gradient rendering.