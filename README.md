Stage 1
========

- Grammer

Stage 2
========
Deadline - March 20

- Lexical Analyzer
	- Print tokens
	- Report lexical errors
- Parser
- Abstract Syntax Tree
- Symbol Table

Plan / list your semantic rules of your language (March 25)

Stage 3
========
Deadline - April 20

- Semantic Analyzer
- Code Generation

----

Instructions
=============
To create asm

	make

To execute asm

	make exec

---

TODO
======
- Accept some special symbols in STRL like >, =, <, !
- Accept negative numbers in lexer/parser
- limit number values
- limit identifier and string length
- Codegen what all did you do
- ~~multiple assignment codegen and typechecking (done implicitly by single assignment)~~
- .size()

Errors
======
- Duplicate declarations of variable: .
- arr = [1, 2, 3];