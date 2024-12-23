# CSS `calc()` Function Override Issue

This repository demonstrates a common error when using the CSS `calc()` function: overriding property declarations.

## Problem

The `calc()` function is powerful, but declaring the same property multiple times within the same CSS selector can lead to unintended consequences. Only the last declaration is used.

## Solution

To correct this, combine the calculations into a single declaration of the property, or use a more specific selector if intending to target separate elements with different calculations.