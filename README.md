# Uncommon Node.js Bug: Null Value Handling

This repository demonstrates a subtle bug in Node.js related to how null values are handled within a function. The bug can lead to unexpected behavior if not properly addressed. This repository shows the buggy code and a corrected version.

## Bug Description

The original function `myFunction` does not explicitly handle cases where one or both of its input arguments are `null`.  This can result in errors such as `TypeError` if the code attempts an operation such as addition on `null` values. 

## Solution

The solution demonstrates a more robust approach to handle `null` values as input parameters.   The corrected function includes a check for `null` values at the beginning and returns a 0, to prevent runtime errors. 
