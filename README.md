Virtual Compiler Implementation using Python
📌 About the Project

This project is a simple implementation of a compiler built using Python.
It shows how source code is processed step by step through all major compiler phases.

The aim is to understand the internal working of a compiler in a clear and practical way.

🏗️ Phases Included

Lexical Analysis

Syntax Analysis

Semantic Analysis

Intermediate Code Generation

Code Optimization

Code Generation

📂 Project Structure
Compiler_Project/
│
├── lexer.py
├── parser.py
├── semantic_analyzer.py
├── intermediate_code.py
├── optimizer.py
├── code_generator.py
└── README.md
🔹 What Each Phase Does

Lexical Analysis – Breaks the input into tokens.
Syntax Analysis – Checks if the statement follows grammar rules.
Semantic Analysis – Validates declarations and usage of variables.
Intermediate Code Generation – Produces three-address code.
Code Optimization – Simplifies unnecessary operations.
Code Generation – Converts the code into simple machine-like instructions.

⚙️ Technologies Used

Python 3

Regular Expressions

Basic Compiler Design Concepts

▶ How to Run

Run any phase using:

python filename.py
🎯 Learning Outcome

This project helps in understanding how a compiler converts source code into executable instructions through different stages.
