# Inconsistent Horizontal Centering with `margin: 0 auto;` and Percentage Widths

This repository demonstrates a common CSS issue related to horizontally centering elements using `margin: 0 auto;` when the width is defined as a percentage.  Some browsers handle this inconsistently, leading to unexpected results.

## The Problem

The `bug.css` file contains CSS that attempts to center a div horizontally. However, due to the use of a percentage width, the centering is not consistent across all browsers.  The issue stems from how different browsers calculate the percentage width relative to the parent container's content width versus its total width.

## The Solution

The `bugSolution.css` file provides a solution.  It utilizes techniques that ensure consistent horizontal centering regardless of the browser or whether the width is a percentage or a fixed value.