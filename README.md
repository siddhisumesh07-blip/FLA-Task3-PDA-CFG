Formal Language and Automata - Task 3

Pushdown Automata (PDA) and Context-Free Grammars (CFG)

Overview
This repository contains the implementation of three case studies based on Pushdown Automata (PDA) and Context-Free Grammars (CFG) as part of the Formal Languages and Automata Theory (FLA) assignment.

The programs demonstrate how PDAs use a stack to recognize languages and how CFGs are used to describe valid patterns and structures.

 Case Studies

1. Balanced Parentheses Checker
- Checks whether a given expression contains properly balanced parentheses.
- Uses a stack-based approach to push opening brackets and pop them when matching closing brackets are encountered.
- Uses the CFG: `S → (S)S | ε`

2. Mathematical Expression Validator
- Validates mathematical expressions based on grammar rules.
- Supports arithmetic operators, operands, and parentheses.
- Uses a Context-Free Grammar to represent valid mathematical expressions.

3. Palindrome String Recognition
- Recognizes palindrome strings over the alphabet `{a, b}`.
- Uses a Pushdown Automaton to compare the first half of the string with the second half in reverse order.
- Uses the CFG: `S → aSa | bSb | a | b | ε`

 Technologies Used
- Python
- Google Colab
- Matplotlib

Repository Contents
- `Balanced_Parentheses_Checker.ipynb` – PDA implementation and CFG demonstration.
- `Mathematical_Expression_Validator.ipynb` – Expression validation using grammar rules.
- `Palindrome_String_Recognition.ipynb` – Palindrome recognition using PDA and CFG.
- Output screenshots PDF – Contains screenshots of the program outputs and diagrams.

Conclusion
These case studies demonstrate the applications of Pushdown Automata and Context-Free Grammars in recognizing structured languages. They provide practical examples of stack-based computation and grammar-based language representation.
