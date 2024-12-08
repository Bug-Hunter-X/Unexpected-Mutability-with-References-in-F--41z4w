# Unexpected Mutability with References in F#

This example demonstrates a potential issue with mutable variables and references in F#.  Improper handling can lead to unexpected behavior and difficult-to-debug errors.

The `bug.fs` file contains the buggy code. The `bugSolution.fs` file demonstrates a corrected approach.

## Problem

The original code uses a mutable variable `x` and a reference `y` to it. Modifying the value through the reference does not always update the original value as expected in certain cases. 