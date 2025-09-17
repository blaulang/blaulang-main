# Blaulang Compiler Internals

## Stages
1. **Lexing**: Convert characters to tokens.
2. **Parsing**: Build AST.
3. **Semantic Analysis**: Type checking, variable scope.
4. **IR Generation**: Produce intermediate representation.
5. **Optimization**: Apply transformations (constant folding, dead code elimination).
6. **Bytecode Generation**: Lower IR to VM bytecode.

## Future Plans
- SSA-based IR
- Advanced optimizations
