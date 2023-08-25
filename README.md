# rust-guessing-game

Improved guessing game example from Rust book Ch. 2, w/quit commands

## Requirements

* Rust (for compilation only)

## Building

### Manual

Compile using Cargo:

```sh
cargo build --release
```

## Usage

Run the program to guess the random number.
Enter '`q`' or '`quit`' to give up and exit early.

```sh
./target/release/guessing_game
Guess the number!
Please input your guess.
1
You guessed: 1
Too small!
Please input your guess.
50
You guessed: 50
Too small!
Please input your guess.
75
You guessed: 75
Too small!
Please input your guess.
88
You guessed: 88
Too big!
Please input your guess.
82
You guessed: 82
You win!
```
