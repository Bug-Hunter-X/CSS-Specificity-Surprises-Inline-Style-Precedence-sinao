# CSS Specificity Issue: Unexpected Font Size

This repository demonstrates a common yet subtle issue in CSS related to specificity and inheritance. The primary issue is the unexpected overriding of styles due to higher specificity, particularly when inline styles are involved. The example shows how inline styles can override other styles even if they seem less relevant, creating unexpected visual results.

## Setup

To reproduce the unexpected behavior, simply open the `bug.html` file in a web browser.  The font size of the paragraph will not match the intended style due to specificity issues.

## Solution

The `solution.css` file offers several approaches to solve the issue using the cascading style sheet rules and selectors correctly. The solution demonstrates how to control style inheritance and specificity effectively to achieve the desired outcome.