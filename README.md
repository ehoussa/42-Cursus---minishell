# Minishell Project

The Minishell project at 42 Network involves creating a simplified version of a Unix shell. The goal is to implement a command-line interpreter capable of executing basic shell commands, handling environment variables, and managing processes.

## Table of Contents

- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Features](#features)
- [Example Commands](#example-commands)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The main goal of the project is to implement a command-line interpreter (shell) that can execute commands entered by the user, handle built-in commands, manage environment variables, and execute programs located in the PATH.

## Project Structure

The project typically consists of the following files:

- **minishell.c**: Contains the main logic for initializing the shell, reading input, and executing commands.
- **parser.c**: Functions for parsing and tokenizing user input into commands and arguments.
- **executor.c**: Functions to execute commands, manage processes, and handle I/O redirection.
- **builtin.c**: Implementation of built-in shell commands (e.g., `cd`, `echo`, `exit`, `env`).
- **utils.c**: Utility functions for memory management, string manipulation, and error handling.
- **minishell.h**: Header file containing function prototypes and necessary macros.
- **Makefile**: Defines compilation rules and dependencies for building the `minishell` executable.

## Usage

To compile and run the `minishell` program, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ehoussa/42-Cursus---minishell/
   cd 42-Cursus---minishell
   ./minishell
   ./minishell
