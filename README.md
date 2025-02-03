# Tailwind CSS Flexbox Issue

This repository demonstrates a common issue encountered when using Tailwind CSS's flexbox utilities with fractional widths. The problem involves unexpected extra space or layout inconsistencies that can arise depending on the surrounding context.

## Problem
The `bug.html` file shows a simple flexbox layout with two divs each occupying half the width.  While seemingly straightforward, depending on the parent container's content, this can generate extra horizontal space. 

## Solution
The `solution.html` file presents a few ways to address this issue.  Often, setting `flex-shrink-0` on the children prevents extra space from appearing. 