# Mini C Compiler

A simple C compiler implementation in Python built from scratch. This compiler supports basic C language features including:

- Arithmetic operators (+, -, *, /, %)
- Relational operators (<, >, <=, >=, ==, !=)
- Logical operators (&&, ||, !)
- Variables and assignments
- If-else conditions
- While loops
- Basic I/O operations

## Components

1. `lexer.py` - Tokenizes the input C code
2. `parser.py` - Parses the tokens and creates an Abstract Syntax Tree (AST)
3. `code_generator.py` - Generates Python code from the AST
4. `main.py` - Main entry point of the compiler

# ▶️ How to Run
1. Clone the repo
bash
Copy
Edit
git clone https://github.com/Uditatripathi/mini_compiler.git
cd mini_compiler
2. Run the compiler
bash
Copy
Edit
python main.py input.c
3. Execute the output
bash
Copy
Edit
python output.py

## Usage

```bash
python main.py input.c
```

This will compile the C code in `input.c` and generate equivalent Python code. # mini_compiler
