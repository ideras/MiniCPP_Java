# MiniCpp Compiler

## Overview

`minicpp` is a mini compiler project designed to process a language similar to C++. The project demonstrates fundamental compiler construction techniques, including lexical analysis, parsing, and abstract syntax tree (AST) generation.

**Note:** The code for this project was generated with the assistance of ChatGPT, an AI language model developed by OpenAI.

## Project Structure

### Lexer

The `Lexer` class is responsible for tokenizing the input source code. It reads the source code and generates a sequence of tokens based on regular expressions.

### Parser

The `Parser` class takes the tokens produced by the `Lexer` and constructs an abstract syntax tree (AST) representing the syntactic structure of the source code.

### Abstract Syntax Tree (AST)

The AST classes represent the structure of the source code and include nodes for expressions, statements, declarations, and more. The AST is used to facilitate further analysis and transformations of the source code.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Maven (for dependency management)

### Building the Project

To build the project, navigate to the project directory and run:

```bash
mvn clean package
```

This command compiles the Java source files and packages them into a JAR file.

### Example Usage

   Create a sample source file, e.g., `example.cpp`, with the following content:

   ```cpp
   int main() {
       int x = 10;
       if (x > 5) {
           cout << "x is greater than 5" << endl;
       }
       return 0;
   }
   ```

   Run the minicpp compiler:

   ```bash
   java MiniCppCompiler example.minicpp
   ```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or discussions related to the `minicpp` project, please contact [Ivan de Jesus Deras](mailto:ideras@gmail.com).

---

Feel free to adjust any sections or details as needed!
