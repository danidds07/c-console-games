**English** | [Português](README.pt-BR.md)

# Console Games in C

A collection of terminal games written in C to practice programming logic in my Algorithms 1 and 2 courses. There are two independent games that run straight in the console, with no external libraries.

## What you can play

- **Horse Race**: a simulated race with random movement each round, until a horse crosses the finish line.
- **Hangman**: the classic word-guessing game, with a limited number of attempts and the gallows drawing updated in the terminal.

Both use only the C standard library (stdio, stdlib, string, time) for input and output, random number generation and text handling.

## Tech stack

- C
- Standard library (stdio, stdlib, string, time)
- Terminal interaction

There are no external dependencies or build system; each game compiles on its own with gcc.

## How to run

**Horse Race**
```bash
gcc horse-race/corridadecavalos.cpp -o horse-race
./horse-race
```

**Hangman**
```bash
gcc hangman/jogodaforca.cpp -o hangman
./hangman
```

## Project structure
```text
c-console-games/
|-- horse-race/
|   `-- corridadecavalos.cpp
|-- hangman/
|   `-- jogodaforca.cpp
`-- README.md
```

## Academic context

Both games were built as exercises for the Algorithms 1 and 2 courses, focusing on loops, conditionals, string handling and random events. It was a pair project: I wrote the Horse Race and my classmate wrote Hangman.

## Author

Horse Race developed by Daniel Augusto Silva.
