# Expo CLI: Unclear 'Module not found' Errors

This repository demonstrates a common yet elusive bug in Expo CLI related to 'Module not found' errors. The issue arises when the root cause isn't immediately apparent, often hidden behind asynchronous operations or complex import chains.  This makes debugging difficult.

## Problem Description

The `bug.js` file contains a faulty import statement that causes a 'Module not found' error. The error message, while indicating a missing module, does not explicitly point to the underlying problem (typo in file name).

## Solution

The `bugSolution.js` file demonstrates the correction of the import statement, resolving the 'Module not found' error.