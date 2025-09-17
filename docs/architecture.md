# Blaulang Architecture

## Overview
Blaulang consists of several layers:
1. **Lexer**: Tokenizes input source code.
2. **Parser**: Produces an Abstract Syntax Tree (AST).
3. **Semantic Analyzer**: Validates types and scopes.
4. **IR**: Intermediate Representation used for optimizations.
5. **VM**: Bytecode execution and JIT compiler.
6. **Runtime**: Garbage collection, I/O, concurrency.
7. **Standard Library**: Core functions and modules.

## Module Interaction
- Frontend → IR → VM → Runtime
- Tools (Linter, Formatter) work directly on source or AST.
