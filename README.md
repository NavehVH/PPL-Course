# Principles of Programming Languages (PPL) — Course Assignments

This repository contains my assignments for the **Principles of Programming Languages (PPL)** course.  
The course explores the theory and practice behind modern programming languages — their design, semantics, and implementation — through hands-on exercises in **Scheme (Racket)**, **TypeScript**, **JavaScript**, and **Prolog**.

---

## Course Overview

The course focuses on understanding the **principles underlying the design of programming languages**.  
It combines theoretical foundations with practical software projects, emphasizing both **language design** and **meta-programming**.

### Main Objectives
1. **Learning principles of programming languages:**  
   - Elements of programming languages and abstraction mechanisms.  
   - Formal definitions: concrete syntax, abstract syntax, and operational semantics.  
   - Program correctness via type checking and type inference.
2. **Describing program execution:**  
   - Study of evaluators, interpreters, transformers, and compilers.
3. **Comparing programming paradigms:**  
   - Functional, Logic, and Imperative programming.
4. **Learning principles of program design:**  
   - Abstraction, contracts, modular architecture, and testing.

The course interleaves two main threads:
- Learning new programming techniques (functional and logic programming) using **JavaScript**, **TypeScript**, and **Prolog**.  
- Learning **meta-programming** by developing parsers, interpreters, and program transformers — including a **type inference system** for functional programming.

---

## Topics Covered

### 1. Applied Functional Programming
- Benefits of Functional Programming (FP): safety, concurrency, asynchronous code  
- Core FP concepts: pure functions, immutability, higher-order functions, composition  
- FP in JavaScript: `map`, `filter`, `reduce`, `flatMap`, `zip`, chaining  
- TypeScript typing: incremental typing, basic types, interfaces, contracts  
- Hierarchical data types: arrays, objects, JSON  
- Higher-order and polymorphic procedures (generic types)

### 2. Syntax, Semantics, and Types
- Concrete vs. abstract syntax (JavaScript vs. Scheme)  
- Operational semantics and the substitution model  
- Types: primitive, composite, and algebraic data types

### 3. Higher-Order Functions
- Functions and the processes they generate  
- Anonymous functions, closures, lexical scope  
- Partial evaluation, currying, and composition  
- Primitive and derived expressions, special operators

### 4. Abstraction on Data and Control
- Data abstraction: ADTs, interfaces, immutable data structures  
- Modeling abstract syntax using algebraic data types  
- From iterators to streams to observables (push/pull data flow)  
- Control abstraction: Promises, async/await, reactive programming, coroutines  
- Continuation-passing style (CPS) and tail recursion optimization

### 5. Evaluators for Functional Programming
- Abstract syntax parsing  
- Evaluators for substitution and environment models  
- Implementation of environment-based operational semantics

### 6. Type Correctness and Inference
- Type checking and type inference algorithms  
- Program transformation: **Scheme → Typed Scheme**

### 7. Logic Programming
- Relational and logic programming fundamentals  
- Backtracking optimization (cuts) and unification  
- Building an evaluator for **Prolog**

---

## Learning Outcomes

By completing this course, I gained hands-on experience in:
- Designing and implementing interpreters and type systems.  
- Applying functional and logic programming paradigms in real projects.  
- Understanding formal semantics and how to reason about code behavior.  
- Building modular, typed, and testable program architectures.

---

## Technologies Used
- **Racket (Scheme)** — for interpreters, type inference, and CPS examples  
- **TypeScript & JavaScript** — for functional programming and evaluators  
- **Prolog** — for logic programming and meta-programming exercises

---

## License
This repository is for educational purposes as part of the *Principles of Programming Languages* course.
