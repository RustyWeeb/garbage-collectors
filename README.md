# garbage-collectors
Memory Management Comparison: JavaScript, C#, and Rust

## Description

This project aims to compare different approaches to memory management in three popular programming languages: JavaScript, C#, and Rust. We present how garbage collection works in JavaScript and C#, and how Rust manages memory without a garbage collector.

## Languages and Technologies:

- JavaScript: Uses a garbage collector to automatically manage memory, employing techniques such as mark-and-sweep and reference counting.
- C#: Utilizes a generational garbage collector within the .NET framework, which divides objects into different generations for more efficient memory management.
- Rust: Employs an ownership and borrowing system, providing deterministic memory management without the need for a garbage collector.


## Key Differences:

- JavaScript: Automatic memory management, possible pauses in application execution (stop-the-world pauses).
- C#: Generational garbage collector optimizing performance by categorizing objects into generations, focusing on reducing execution pauses.
- Rust: No garbage collector, deterministic memory management through ownership system, eliminating memory leaks and access errors.


## Code Examples:

- JavaScript: Examples of GC usage in web applications.
- C#: Examples of memory optimization using the generational GC.
- Rust: Examples of memory management using the ownership system.
