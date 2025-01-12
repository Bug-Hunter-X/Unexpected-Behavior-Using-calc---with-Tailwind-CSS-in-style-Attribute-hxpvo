# Unexpected Behavior Using calc() with Tailwind CSS in style Attribute

This repository demonstrates a common issue encountered when using the CSS `calc()` function within the `style` attribute of an HTML element, specifically in conjunction with Tailwind CSS.

## Issue Description

Tailwind CSS often interferes with or misinterprets `calc()` values provided directly within the `style` attribute.  This can result in unexpected layout, rendering errors, or the `calc()` function being completely ignored.

## Solution

The preferred method to handle this is to avoid using `calc()` directly within the `style` attribute. Instead, define a custom CSS class using Tailwind's `@apply` directive, or use JavaScript to dynamically set the width/height.

See the `bugSolution.js` for an alternative solution.