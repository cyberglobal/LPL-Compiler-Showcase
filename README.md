# LPL-Compiler-Showcase
Compiler for a subset of the LPL language.

This project implements the first stage of a compiler for the LPL programming language.  
---

##  Objectives

The goal is to build a working compiler for a **basic subset** of LPL (without methods or arrays), covering:

| Component | Description |
|----------|-------------|
| **AST Construction** | Manually build Abstract Syntax Trees for 5 example programs provided in the spec. |
| **Code Generation** | Implement `compile()` methods in AST classes to generate **SSM** assembly code. |
| **Parser Implementation** | Complete a recursive-descent parser based on the **LL(1)** grammar in `LPL.sbnf`. |

These combine to produce a functional compiler pipeline.
---
## Academic Integrity Notice
This work was submitted as part of an assessed coursework.
Full source code is stored in a private repository
