# Dart `reduce` method and empty lists

This example demonstrates a common error in Dart when using the `reduce` method on an empty list. The `reduce` method requires at least one element in the list; otherwise, it throws a `RangeError`.

The solution shows how to handle this situation using an appropriate check to prevent the error.  The code also uses null safety features for improved robustness.
