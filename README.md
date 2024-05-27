# Minigrep

Minigrep is a simple command-line tool implemented in Rust that mimics the basic functionality of the `grep` command. It searches for a specified string within a given file and prints all the lines that contain that string.

## Getting Started

### Prerequisites

- Ensure you have [Rust](https://www.rust-lang.org/) installed on your system. If not, you can install it by following the instructions on the official Rust website.

### Cloning the Repository

To clone the repository, open your terminal and run:

```bash
git clone https://github.com/sibsaurabh/minigrep.git
cd minigrep
```

### Running the Project

To run the Minigrep tool, use the following command:

```
cargo run -- <searchString> <filePath.
```

- searchString: The string you want to search for in the file.
- filePath: The path to the file you want to search within.

### Case Insensitive Search

To perform a case-insensitive search, set the environment variable IGNORE_CASE to 1:

```
export IGNORE_CASE=1
cargo run -- <searchString> <filePath>
```

### Running Tests

To run the tests for the Minigrep tool, use the following command:

```
cargo test
```

### Acknowledgments

This project is based on the tutorial from the Rust Programming Language Book.
