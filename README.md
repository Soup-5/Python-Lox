# Python Lox Interpreter
![GitHub Repo stars](https://img.shields.io/github/stars/Soup-5/Python-Lox)
![GitHub forks](https://img.shields.io/github/forks/Soup-5/Python-Lox)
![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/Soup-5/Python-Lox/total)
![GitHub](https://img.shields.io/github/license/Soup-5/Python-Lox)
---

## Description

An (*incredibly* bare bones) Python 3.9.2 interpreter implementation of the lox 
programming language, adapted from the *jlox* tree-walk interpeter in the book
"[Crafting Interpreters](https://craftinginterpreters.com/)" by Robert Nystrom.\
\
I put "bare bones" because currently the interpreter only supports a few of
lox's basic features so far:
- Literals (strings, floats)
- Basic Arithmetic (+, -, *, /)
- Boolean Arithmetic & Equality
- Expressions
- Statements (only `print` & `var`)
- Variable Declaration
- Variable Assignment
- Comments (single & multi-line)
- Block Statements & Scope
- If/Else Statements
- While Loops\
I plan on adding more as I progress through the book

## Installation

### Windows:

- This project assumes you have already installed python 3.9.2, if not you can 
  [download it here for Windows (64-bit)](https://www.python.org/ftp/python/3.9.2/python-3.9.2-amd64.exe)
  or grab other builds [here](https://www.python.org/downloads/release/python-392/)
- Download this project's latest release [here](https://github.com/Soup-5/Python-Lox/archive/refs/tags/v1.0.2.zip)
- Unzip and extract `Downloads/Python-Lox-1.0.0.zip`
- Open the `Windows PowerShell` app using the **Start** menu
- Run the script by typing in the following format: `python3 src/main.py *.lox`

For example, if you want to run the `fizzbuzz.lox` script you can type in the following command:
```bash
python3 src/main.py examples/fizzbuzz.lox
```

### Macbook:

- This project assumes you have already installed python 3.9.2, if not you can 
  [download it here for MacOS](https://www.python.org/ftp/python/3.9.2/python-3.9.2-macos11.pkg)
  or grab other builds [here](https://www.python.org/downloads/release/python-392/)
    - You might need to install [Apple's Developer Tools](https://developer.apple.com/xcode/resources/)
      if you haven't already
- Download this project's latest release [here](https://github.com/Soup-5/Python-Lox/archive/refs/tags/v1.0.2.zip)
- Unzip and extract `Downloads/Python-Lox-1.0.0.zip`
- Open the `Terminal` app through **Launchpad**
- Use `cd` to change to the project's directory
- Run the script by typing in the following format: `python3 src/main.py *.lox`

For example, if you want to run the `fizzbuzz.lox` script you can type in the following command:
```bash
python3 src/main.py examples/fizzbuzz.lox
```

### Debian/Ubuntu:

- This project assumes you have already installed python 3.9.2, if not you can
  run `sudo apt install python3.9`
- Download this project's latest release [here](https://github.com/Soup-5/Python-Lox/archive/refs/tags/v1.0.2.zip)
- Run `unzip Downloads/Python-Lox-1.0.0.zip`
- Use `cd` to change to the project's directory
- Run the script by typing in the following format: `python3 src/main.py *.lox`

For example, if you want to run the `fizzbuzz.lox` script you can type in the following command:
```bash
python3 src/main.py examples/fizzbuzz.lox
```

## License & Attributions

This Project is licensed under the [MIT License](https://opensource.org/license/mit/)\
\
Huge thank you to [Bob Nystrom](https://github.com/munificent) for letting me dive
into the monstrosity that is compiler/interpreter programming with *Crafting Interpreters*
