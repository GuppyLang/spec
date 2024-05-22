# Function Basics

Functions are declared using the `fn` keyword followed by the name of the function in upper-snakecase.

```
fn My_Function {
    ...
}
```

This function can be called as such:

```
My_Function
```

Parenthesis are not necesary as this function does not require any arguments. You can distinguish a function from a normal variable easily via the casing.

> Note: the `_` accessor is still available to functions, however it is preferred to use dedicated arguments as described below.

A basic function that takes arguments is written as:

```
fn My_Function(x, y, z) {
    ...
}
```

And likewise called as such:

```
My_Function(x, y, z)
```

# Advanced Function Arguments
