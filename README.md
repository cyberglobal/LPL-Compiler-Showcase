# LPL-Compiler-Showcase
A compiler for a subset of the LPL language.

This project implements the first stage of a compiler for the LPL programming language.

---

## Objectives

The goal is to build a working compiler for a **basic subset** of LPL (without methods or arrays), covering:

| Component | Description |
|----------|-------------|
| AST Construction | Manually build Abstract Syntax Trees for 5 sample programs provided in the coursework. |
| Code Generation | Implement `compile()` methods in AST classes to generate **SSM** assembly instructions. |
| Parser Implementation | Build a recursive-descent parser based on the LL(1) grammar defined in `LPL.sbnf`. |

These components combine to form the full compiler pipeline.

---

##  Academic Integrity Notice
This work was submitted as part of an assessed coursework. To protect academic policy and avoid enabling plagiarism. 
Full source code is stored in a private repository
