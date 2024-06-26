# What is Scrabble Helper?
**Scrabble Helper** is a simple shell program that accepts a series of letters, then displays a list of Scrabble words possible from those letters. I undertook this project as a first foray into Elixir and functional programming, and boy howdy was it rewarding! (And terrifying, but mostly rewarding.)

  - First, I built the functionality in [Ruby](https://github.com/ruby/ruby) (easy peasy);
  - Then, I tried to build the same functionality in [Elixir](https://github.com/elixir-lang/elixir) (not so easy peasy).

Despite the simplicity of the functionality, Scrabble Helper was a real doozy—and ended up being a _fantastic_ introduction to the terrifying-yet-wonderful world of functional programming. By trying to replicate my Ruby work in Elixir, I slammed right up against some of functional programming's most opinionated principles. That friction had me entirely rethinking both the problem, and my approach to programming in general—and dare I say it, I might be a functional programming convert in the making.

If you're interested in functional programming and don't quite know where to start, like me, please feel free to hit me up! I'm but a single step into this perilous journey, and I would love some companions to ~~suffer~~ learn with along the way.

## Installation
**Scrabble Helper** requires a local installation of either [Ruby](https://github.com/ruby/ruby) or [Elixir](https://github.com/elixir-lang/elixir) (or both).
  - [Click here for Ruby installation instructions](https://www.ruby-lang.org/en/documentation/installation/)
  - [Click here for Elixir installation instructions](https://elixir-lang.org/install.html)

After installing one or both of the above, follow these directions:
  1. Clone down this Scrabble Helper repository to your local machine, using the green Code button.
  2. Open a terminal session, and navigate to the Scrabble Helper repository.
  3. Within your terminal session, enter `chmod +x run_scrabble.sh` to enable permissions.
  4. Finally, within your terminal session, enter `./run_scrabble.sh` to run the program.

## Features and Usage

To use **Scrabble Helper**, select either the Ruby or Elixir implementation (which produce identical results), then enter a series of letters. The tool will check your input against the latest [Scrabble dictionary](https://github.com/redbo/scrabble/blob/master/dictionary.txt) to produce a list of possible words.

For example, an input of `band` will produce `AB, AD, AN, AND, BA, BAD, BAND, DAB, DAN, NA, NAB`. Note that each letter in the input can only be used once, just like in Scrabble.

## Uninstallation

Just delete the repository from your local machine, and you're done! Simple and clean (like the way that you're making me feel tonight~🎵)

## Acknowledgements

- Full credit to [Verbus Counts](https://www.linkedin.com/in/verbus-counts-716ab2/) for setting me down this precarious path of functional programming.
- The incredibly well-maintained [Elixir Docs](https://hexdocs.pm/elixir/introduction.html)
- You, for hanging out
