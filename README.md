# jLox Interpreter

This repository contains the ongoing implementation of the `jLox` language, a tree-walk interpreter written in Java. The `jLox` language and its interpreter are part of the educational resource provided in the book ["Crafting Interpreters"](http://craftinginterpreters.com/) by Bob Nystrom. 

The primary aim of this project is to gain a deeper understanding of how programming languages are designed, parsed, and executed by building a complete interpreter from scratch.

## About jLox

`jLox` is the Java implementation of the Lox language. It is a simple, high-level, C-like programming language that supports object-oriented programming. The language has a C-style syntax, and its features include variables, functions, control flow, and a few data types such as numbers, strings and booleans.

## Project Structure

The project is structured as follows:

- `Lox.java`: This is the main driver of the interpreter. It handles the execution of scripts, user interaction, and error reporting.
- `Scanner.java`: The scanner takes source code as input and converts it into a sequence of tokens.
- `Token.java`: The `Token` class encapsulates information about a token, including its type, lexeme, any literal value, and the line in the source where it was found.
- `TokenType.java`: This enum represents the different types of tokens that the scanner can recognize.

## Learning Resource

This project is based on the book ["Crafting Interpreters"](http://craftinginterpreters.com/) by Bob Nystrom, which is an excellent resource for those interested in learning about interpreters and programming language design. The book provides a comprehensive guide to building an interpreter for a scripting language, complete with code snippets and detailed explanations.

## Progress

The implementation is ongoing and updates will be made as progress through the book continues.
