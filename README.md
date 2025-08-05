# Haskell Mini Language Interpreter

This project is a minimal interpreter for a custom expression-based language written in Haskell. It includes:

- A custom AST supporting variables, natural numbers, lambdas, applications, `let`, `letrec`, and lists.
- Modular structure with parsing, REPL, and pretty-printing capabilities.
- Designed for educational or experimental use with interpreters and functional languages.

## Modules

- `Exp.hs`: Defines the abstract syntax tree (AST).
- `Main.hs`: Entry point for the REPL (to be implemented).
- Additional modules (Parsing, Printing, REPLCommand) expected for full functionality.

## Getting Started

To build or run:
```bash
ghc Main.hs
./Main
