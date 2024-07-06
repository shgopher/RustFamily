<!--
 * @Author: shgopher shgopher@gmail.com
 * @Date: 2024-01-26 17:23:17
 * @LastEditors: shgopher shgopher@gmail.com
 * @LastEditTime: 2024-07-06 23:49:03
 * @FilePath: /RustFamily/基础/hello-world/README.md
 * @Description: 
 * 
 * Copyright (c) 2024 by shgopher, All Rights Reserved. 
-->
# hello world
## 背景
Rust是一种系统编程语言，以其安全性、并发性和性能而闻名。它旨在提供内存安全的同时，不牺牲性能，并且能够防止诸如数据竞争和空悬指针等常见的编程错误。
## rust 编程哲学
- **内存安全**：Rust的所有权和生命周期系统确保内存安全，无需垃圾收集器。
- **并发性**：Rust提供了现代的并发编程模型，能够安全地在多个线程之间共享数据。
- **性能**：Rust的性能与C和C++相当，因为它允许直接访问硬件资源。
- **实用性**：Rust强调实用性，提供了丰富的标准库和包管理器Cargo。
## rust 语言特性
- **所有权系统**：Rust通过所有权系统管理内存，确保数据的生命周期。
- **模式匹配**：Rust提供了强大的模式匹配能力，使代码更加简洁和安全。
- **类型推断**：Rust的类型推断系统减少了需要显式编写的类型信息。
- **泛型和特性**：Rust支持泛型编程和特性，增加了代码的复用性。
- **错误处理**：Rust使用`Result`和`Option`类型来处理可能的错误。
## hello world
```rust
fn main() {
  println!("hello world"); /// prrintln!宏用于打印输出, /// 注释方法用于输出 文档注释
}
```