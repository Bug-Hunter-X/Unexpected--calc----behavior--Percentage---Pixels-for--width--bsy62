# CSS `calc()` Bug: Percentage + Pixels

This repository demonstrates a subtle bug related to the CSS `calc()` function and its handling of mixed units (percentages and pixels) when applied to the `width` property.

## Problem

The `calc()` function is designed to allow for dynamic calculations within CSS. However, some browsers exhibit inconsistencies when combining percentages and pixels in the calculation, particularly for the `width` property. This can result in unexpected layout behaviors.

## Reproduction

The `bug.css` file contains the problematic CSS code. The expected behavior is for the div to take up 50% of its container's width plus 20px. However, depending on the browser, the actual result might deviate from this expectation.

## Solution

The `bugSolution.css` file provides a possible workaround. This often involves using a more explicit approach, such as adjusting the `width` with JavaScript or employing alternative layout techniques like flexbox or grid.