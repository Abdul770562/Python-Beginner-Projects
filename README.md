# Python Beginner Projects

A collection of small Python projects for practicing programming fundamentals, including functions, loops, conditionals, randomization, user input, and basic object-oriented programming. The repository contains both terminal-based exercises and games built with Python's `turtle` graphics module.

## Projects

| Project | Description | Interface |
| --- | --- | --- |
| [CaesarCipher](CaesarCipher/) | Encode and decode messages using a Caesar shift. | Terminal |
| [Calculator](Calculator/) | Perform addition, subtraction, multiplication, and division, with an option to continue from a result. | Terminal |
| [CoffeMachine](CoffeMachine/) | Simulate a coffee machine, including drink selection, resource checks, payments, and reports. | Terminal |
| [GuessTheNumberGame](GuessTheNumberGame/) | Guess a randomly selected number, choosing an easy or hard attempt limit. | Terminal |
| [HangmanGame](HangmanGame/) | Guess a hidden word one letter at a time while avoiding the hangman. | Terminal |
| [HigherLowerGame](HigherLowerGame/) | Compare two public figures and guess who has more followers. | Terminal |
| [PongGame](PongGame/) | Play a two-player Pong game with keyboard-controlled paddles. | Turtle window |
| [SnakeGame](SnakeGame/) | Play Snake, collect food, and avoid the walls and your tail. | Turtle window |

## Requirements

- Python 3
- A terminal for the command-line projects
- A graphical desktop environment for the `turtle` games

Most projects use only Python's standard library. The graphical projects use `turtle`, which is included with many Python installations but may require a working Tk installation. `SnakeGame` also imports `winsound`, which is available on Windows only.

## Run a project

Clone the repository and change into the directory for the project you want to run. Run its `main.py` or, for Hangman, `hangman.py`:

```bash
git clone https://github.com/Abdul770562/Python-Beginner-Projects.git
cd Python-Beginner-Projects/GuessTheNumberGame
python main.py
```

For another project, replace `GuessTheNumberGame` with its directory name. For Hangman, use:

```bash
cd ../HangmanGame
python hangman.py
```

On systems where the Python 3 command is `python3`, substitute `python3` for `python`. Run each script from its own project directory so its local module imports can be found.

## Notes

- `SnakeGame` requests a difficulty when it starts. Its sound effects are optional in the code, and `winsound` is Windows-specific.
- The coffee-machine entry point currently imports `coffee_maker`, but the repository file is named `cofee_maker.py`. Rename that module or update the import before running the project.
- These are beginner learning exercises and may have limitations; they are intended as a starting point for experimentation and improvement.

## Contributing

Suggestions and improvements are welcome. If you add a project, include its source files in a clearly named folder and update this README with a short description and run instructions.

## License

No license is currently specified. Unless a license is added, the repository's contents are not explicitly made available for reuse, modification, or redistribution.
