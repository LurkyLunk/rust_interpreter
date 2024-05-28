# # Rust Interpreter

## Overview

This project is a simple interpreter written in Rust. It provides a basic framework to parse and execute a custom scripting language. The goal is to demonstrate how to build an interpreter from scratch using Rust, covering lexical analysis, parsing, and evaluation of expressions.

## Features

- **Lexical Analysis**: Tokenize input strings into meaningful symbols.
- **Parsing**: Convert tokens into an Abstract Syntax Tree (AST).
- **Evaluation**: Execute the AST to produce results.
- **Error Handling**: Basic error handling for syntax and runtime errors.

## Getting Started

### Prerequisites

- Rust installed on your machine. You can download it from [here](https://www.rust-lang.org/).

### Basic Usage

1. **Provide Script**: You can write scripts using the custom scripting language supported by this interpreter.
2. **Run Script**: Execute the script using the interpreter to see the results.

### Adding New Features

1. **Extend the Lexer**: Add new token types in `src/lexer.rs`.
2. **Update the Parser**: Modify `src/parser.rs` to handle new syntax.
3. **Enhance the Evaluator**: Implement new operations in `src/evaluator.rs`.
