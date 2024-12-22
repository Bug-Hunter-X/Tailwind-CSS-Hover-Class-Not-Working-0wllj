# Tailwind CSS Hover Class Not Working

This repository demonstrates a common issue encountered when using Tailwind CSS: hover classes not applying correctly.  The problem arises when there's a conflict with other CSS styles or an issue with how the Tailwind directives are set up.

## Bug Description
A simple `hover` class in Tailwind is not causing the expected style change.  The example div is supposed to change background color on hover, but it does not.

## Solution
The solution involves carefully examining the CSS cascade to identify any conflicting styles.  In this example, the issue was resolved by ensuring proper order and specificity of the Tailwind CSS directives.