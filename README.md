# JavaScript Loose Comparison and Null/Undefined Handling
This repository demonstrates a common JavaScript error related to loose comparison (==) and the handling of null and undefined values.

## The Bug
The `foo` function attempts to add two numbers. However, it uses loose comparison (`==`) to check for null values, which can lead to unexpected results when `undefined` is passed as an argument.

## The Solution
The solution involves using strict equality (`===`) to accurately check for null values and adding a specific check for undefined. This avoids unintended type coercion and produces the expected output.