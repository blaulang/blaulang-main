# Developing Blaulang Modules

## Structure
A module is a collection of `.bll` files or C++ extensions.

## Example
```bll
// math.bll
func square(x) -> int {
    return x * x
}
```

## Import
```bll
import math

print(math.square(4))
```

## Native Modules
- Written in C++
- Registered via FFI
