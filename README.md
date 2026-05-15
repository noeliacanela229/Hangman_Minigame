# Hangman

A terminal-based Hangman game built in C. The program picks a random word from a built-in list, gives you a hint, and draws the hangman step by step as you run out of guesses.

## How it works

- A random word is selected and a hint is displayed at the start
- You have 6 attempts to guess the word one letter at a time
- Correct guesses reveal the letter in the word; wrong guesses add a body part to the hangman drawing
- The game ends when you guess the full word or run out of tries

## How to run

You'll need a C compiler like `gcc` installed.

```bash
gcc hangman.c -o hangman
./hangman
```

## Example

```
Welcome to Hangman!
Hint: A large mammal with a trunk

Word: _ _ _ _ _ _ _ _

     _________
    |         |
    |         O

Enter a letter:
```

## Built with

- C
- Standard libraries: `stdio.h`, `stdlib.h`, `string.h`, `ctype.h`, `time.h`
