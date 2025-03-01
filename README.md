# Haskell Hello World

A simple "Hello, World!" program written in Haskell.

## Project Description

This project demonstrates a basic Haskell program that prints "Hello, World!" to the console.

## Code Explanation

The program consists of a single file `hello.hs` with the following code:

```haskell
main :: IO ()
main = putStrLn "Hello, World!"
```


- `main :: IO ()` - This is the type signature declaring that `main` is an IO action that returns unit `()`
- `main = putStrLn "Hello, World!"` - This defines the main function to print "Hello, World!" to the console

## How to Run

### Prerequisites

- Install the Haskell Platform or GHC (Glasgow Haskell Compiler)

### Compilation and Execution

You can run the program in several ways:

1. **Compile and run:**
   ```bash
   ghc hello.hs
   ./hello  # On Unix-like systems
   hello.exe  # On Windows
   ```

2. **Run with GHCi (Haskell interpreter):**
   ```bash
   ghci hello.hs
   *Main> main
   ```

3. **Run directly with runghc:**
   ```bash
   runghc hello.hs
   ```# haskell-playground
