# CSS Specificity Issue

This repository demonstrates a subtle CSS specificity issue that can lead to unexpected behavior when combining ID and class selectors. The bug involves an incorrect assumption about how specificity works in CSS, leading to a rule not overriding as expected.

## Bug Description

A seemingly more specific CSS rule fails to override a less specific rule due to the way CSS handles specificity when combining IDs and classes. The `#specific-div` rule is not overridden by `.container #specific-div` because the ID selector's specificity is higher.

## Bug Solution

The solution involves understanding CSS specificity rules and how they are calculated. Removing the incorrect rule or modifying the selectors to achieve the desired effect is the proper approach.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` to see the buggy code.
3. Open `bugSolution.css` to see the corrected code.
4. Observe the differences in the output.