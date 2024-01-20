# Grep Tool(Made with Rust)

This Rust application is a simple text search tool designed to search for a specified query in a given file. It can be a useful utility for quickly finding occurrences of a particular string in a text file.

## Usage

To use the application, run it from the command line with the following syntax:

```bash
./search_application <query> <filename>
```

- `<query>`: The string you want to search for in the file.
- `<filename>`: The name of the file in which you want to perform the search.

## Example

```bash
./search_application hello example.txt
```

This example command searches for the string "hello" in the file named "example.txt".

## Error Handling

The application provides basic error handling for insufficient command-line arguments. If the user fails to provide the required arguments, an error message is displayed, guiding the user on the correct usage.

## Building and Running

Ensure you have the [Rust programming language](https://www.rust-lang.org/) installed on your system. To build and run the application, use the following commands:

```bash
cargo build
cargo run <query> <filename>
```

This assumes you are in the project directory.
