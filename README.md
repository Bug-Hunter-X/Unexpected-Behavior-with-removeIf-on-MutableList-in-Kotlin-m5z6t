# Unexpected Behavior with removeIf on MutableList in Kotlin

This repository demonstrates a potential issue when using the `removeIf` function with a mutable list in Kotlin.  The `removeIf` function modifies the list in place, which can lead to unexpected behavior if not handled correctly. The example highlights this behavior and offers a solution.

## Bug
The original code removes even numbers from a mutable list.  However, the iteration behavior might not be entirely intuitive, leading to potential issues in more complex scenarios.