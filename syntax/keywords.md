# Keywords
- [`flag`](#flag)
- [`set`](#set)
- [`mut`](#mut)
- [`use`](#use)
- [`from`](#from)
- [`as`](#as)
- [`fn`](#fn)
- [`while`](#while)
- [`each`](#each)
- [`in`](#in)
- [`if`](#if)
- [`elif`](#elif)
- [`else`](#else)
- [`case`](#case)
- [`when`](#when)
## flag
`flag` tells the Guppy compiler to add certain header information to the bytecode before the it is then interpreted. 
## set
`set` is for setting variables. 
## mut
`mut` is used to create mutable variables in conjuction with set, or after a variable has been declared. 
## use 
`use` will attempt to import an external module, whether it's a builtin, external library, or module you created. It will always be used in conjuction with `from`. See [from](#from).

Examples:
```
use io from "io" # imports the export io from builtin io
```
```
use parser from "./parser" # imports module via a relative path
```
## from
`from` is used alongside `use` and specifies the target a module should be loaded from. It is to be followed by a string with no whitespace which is either the name of a builtin module or one installed with the package manager, or a relative or absolute file path. See [use](#use).
## as 
`as` is used alongside `use` and `from` however is optional. `as` allows the name of the import to be changed in the use statement itself. 

Example: 
```
use stdio as io from "stdio" 
```

This allows you to reserve the `stdio` name, for example if you want to use the name `stdio` somewhere else. 
### fn
### while 
### each 
### in 
### if 
### elif 
### else
### case
### when