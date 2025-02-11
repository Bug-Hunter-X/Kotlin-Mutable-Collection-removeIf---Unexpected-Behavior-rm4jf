# Kotlin Mutable Collection removeIf() Unexpected Behavior

This repository demonstrates an uncommon bug in Kotlin related to the `removeIf()` function when used with mutable collections like `MutableList` and `MutableMap`. The problem arises when the lambda expression used in `removeIf()` modifies the collection during iteration, leading to unexpected results.

The `bug.kt` file contains code that illustrates this issue. The `bugSolution.kt` file provides a solution that avoids this problem.