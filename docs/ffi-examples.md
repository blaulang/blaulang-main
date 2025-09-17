# Blaulang FFI Examples

## Example: Using C Math Library
```bll
extern func c_sin(float) -> float

let x = 3.14
print(c_sin(x))
```

## Example: Interacting with C++ Class
```cpp
// C++ code
extern "C" int counter_increment(int v) {
    return v + 1;
}
```

```bll
extern func counter_increment(int) -> int
let y = counter_increment(5)
```

