# React Compiler with ANTLR v4 💻

This project implements a custom React compiler built using **ANTLR v4**, designed to recognize React and JavaScript code. It outputs an **Abstract Syntax Tree (AST)** and a **Symbol Table**, which includes all declared variables and functions from the provided code.

## Features
- **AST Generation:** Converts the input code into a structured Abstract Syntax Tree (AST).
- **Symbol Table:** Extracts and lists all variables and functions defined in the code.
  
## Project Overview

The project is divided into the following stages:

1. **Lexical Grammar Definition:** Tokenizes the parsed input based on defined lexical rules.
2. **Parser Definition:** Specifies the parsing rules for JavaScript, JSX, and React-specific syntax.
3. **Visitor Implementation:** Generates an Abstract Syntax Tree (AST) from the parsed input.
4. **Symbol Table Generation:** Collects and outputs a symbol table containing all declared variables and functions.

## How to Try It

1. Generate ANTLR Recognizer for "LexerGram.g4" and "ParserGram.g4".
2. Write your React and JavaScript code in the `Files/test.txt` file within the project directory.
3. Run the `Main.java` file to parse the code and generate the output (AST + Symbol Table).
