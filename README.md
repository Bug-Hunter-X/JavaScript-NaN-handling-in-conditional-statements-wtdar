# JavaScript NaN Handling Bug

This repository demonstrates a subtle bug in JavaScript related to handling NaN (Not a Number) values within conditional statements using loose comparison. The provided code appears to correctly handle null and negative numbers, but fails when NaN is provided as an input.  The solution demonstrates how to correctly handle this edge case using strict equality and Number.isNaN().