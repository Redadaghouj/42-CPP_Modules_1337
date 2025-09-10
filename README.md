# 🖥️ 42 C++ Modules

[![1337 Badge](https://img.shields.io/badge/1337-Project-blue)](https://www.42network.org/)
![Status](https://img.shields.io/badge/Status-In_Progress-orange)

### A comprehensive journey through C++ fundamentals and advanced concepts

---

## 📜 Project Overview

This repository serves as a master project for the C++ Common Core at 1337, a series of C++ modules covering fundamental and advanced topics. Each module is a submodule in this repository, designed to be compiled and evaluated independently while building upon concepts from previous exercises.

> ⚠️ All code must follow the **C++98 standard**.

---

## 📁 Modules

  * **Module 00: A simple introduction to OOP in C++**
    This module covers fundamental concepts such as namespaces, classes, and standard I/O streams while adhering to the C++98 standard.

  * **Module 01: Memory allocation, pointers to members, and references**
    This module builds on C++ fundamentals, focusing on memory allocation, pointers, and references. It also introduces topics like member functions, namespaces, and standard I/O streams.

  * **Module 02: Ad-hoc polymorphism, operator overloading and the Orthodox Canonical class form**
    This module expands on C++ fundamentals, focusing on designing classes that are robust and reusable by implementing canonical class form and overloading operators for custom functionality, all while adhering to the C++98 standard.

  * **Module 03: Inheritance, visibility, and virtual functions**
    This module focuses on object-oriented programming concepts such as inheritance, visibility, and virtual functions.

  * **Module 04: Polymorphism, interfaces, and abstract classes**
    This module delves deeper into polymorphism, abstract classes, and the creation of interfaces in C++.

## 🚀 Getting Started

To clone this repository and all its submodules, run the following command:

```bash
git clone --recursive git@github.com:Redadaghouj/42-CPP_Modules_1337
```

If you have already cloned the repository without the `--recursive` flag, you can initialize and update the submodules by running:

```bash
git submodule update --init --recursive
```

## 🛠️ Compilation

Each module has its own `Makefile`. To compile an exercise, navigate to its directory and run `make`.

### 📌 Compilation Flags

Your code must be compiled with `c++` and the following flags:

```bash
-Wall -Wextra -Werror -std=c++98
```

## 📜 General Rules

  * **Language Standard**: All code must comply with the C++98 standard.
  * **Forbidden Functions**: `*printf()`, `*alloc()`, and `free()` are strictly forbidden.
  * **STL Usage**: The Standard Template Library (STL) is not allowed until Modules 08 and 09.
  * **Memory Management**: All memory allocated with `new` must be deallocated with `delete` to prevent memory leaks.
  * **Headers**: All header files must include guards to prevent double inclusion.
  * **Output**: Every output message must end with a newline character and be displayed to standard output.
