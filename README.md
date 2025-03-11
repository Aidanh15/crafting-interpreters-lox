# Lox Interpreter

This is my implementation of the Lox programming language from the book "Crafting Interpreters" by Robert Nystrom.

## Project Structure

```
lox/
├── bin/            # Compiled class files
├── src/            # Source code
│   └── com/
│       └── craftinginterpreters/
│           └── lox/ # Lox implementation
├── build.sh        # Build script
├── run.sh          # Run script
└── README.md       # This file
```

## Building and Running

To build the project:
```bash
./build.sh
```

To run the interpreter in REPL mode:
```bash
./run.sh
```

To run a Lox script:
```bash
./run.sh path/to/script.lox
```

## Implementation Progress

- [x] Basic project setup
- [ ] Scanner
- [ ] Parser
- [ ] Abstract Syntax Tree
- [ ] Interpreter
- [ ] Variables
- [ ] Control Flow
- [ ] Functions
- [ ] Resolving and Binding
- [ ] Classes
- [ ] Inheritance

## References

- [Crafting Interpreters](https://craftinginterpreters.com/) by Robert Nystrom
- [Official Repository](https://github.com/munificent/craftinginterpreters)
