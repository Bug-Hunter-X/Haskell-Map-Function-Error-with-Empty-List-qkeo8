# Haskell Map Function and Empty Lists

This repository demonstrates a common error when using the `map` function in Haskell with empty lists.  The provided code snippet showcases the error, and a solution is implemented to illustrate proper handling of empty lists.

The issue arises from an incomplete pattern match in the function definition. The original code fails to handle the case of an empty list, resulting in a runtime error.  The solution addresses this by explicitly checking for and handling empty lists, thereby providing a robust and error-free implementation.

This example highlights the importance of comprehensive pattern matching in Haskell, especially when working with potentially empty data structures like lists.