# F# Mutable Variable Scope Issue

This example demonstrates a common issue with mutable variables in F# when dealing with function scope. The `swap` function attempts to swap the values of two mutable variables, but due to how mutable variables are handled within function scopes, the swap doesn't work correctly. The solution shows how to resolve this by using tuples or more advanced techniques.