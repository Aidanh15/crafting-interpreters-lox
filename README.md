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

## Git Branching Strategy

This repository uses the following branching strategy:

- `main` - The primary implementation following the book's code
- `chapterX` - Branches for each chapter (e.g., `chapter4`, `chapter5`)
- `challenge-X-Y` - Branches for individual challenges (e.g., `challenge-4-1` for Chapter 4's first challenge)

### How to navigate:

1. For the standard implementation as presented in the book, follow the `main` branch.
2. To see the implementation of a specific challenge, check out the corresponding challenge branch.

### For contributors:

When implementing a challenge:
1. Branch off from the respective chapter branch (e.g., `git checkout -b challenge-4-1 chapter4`)
2. Implement the challenge
3. Commit and push to that branch

This strategy allows us to maintain a clean main implementation while exploring alternative implementations through the book's challenges.
