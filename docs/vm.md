# Blaulang Virtual Machine

## Design
- Stack-based VM
- Supports bytecode instructions for arithmetic, logic, control flow, and function calls.

## Bytecode Format
- Instructions are fixed-length opcodes with operands.
- Example:
```
LOAD_CONST 1
LOAD_CONST 2
ADD
STORE_VAR x
```

## JIT Compilation
- Planned to integrate LLVM backend.
