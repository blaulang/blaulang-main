# Getting Started with Blaulang

This tutorial introduces you to Blaulang basics.

## Hello World
Create a file `hello.bll`:
```bll
func main() {
    print("Hello, Blaulang!")
}
```

Run it:
```bash
blaulang hello.bll
```

## Variables
```bll
let x = 10
var y = 20
y = y + x
```

## Functions
```bll
func add(a, b) -> int {
    return a + b
}
```
