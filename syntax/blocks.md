# Block Basics

Blocks are seperate "chunks" of code that get executed in a lower scope. They consist of any code enclosed within curly braces. Blocks can be used standalone, or as functions using the `fn` keyword.

```
{
    ...
}
```

Blocks can also be passed arguments in a similar fashion to functions. This is useful for callbacks. These arguments are bound to `_` and presented as a map.

```
    get_user_info({
        io.out("#[_.name] is #[_.age] years old.")
    })
```
