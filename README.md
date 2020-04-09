# AVL tree implementation for Rust learning.

Rust implementation of [AVL tree](https://en.wikipedia.org/wiki/AVL_tree), one of the balance trees.  

Since balance trees frequently re-assign pointers and move ownership, the implementation provides very good understanding of Rust's ownership system. This repository provides an AVL tree implementation that is as concise as possible for learning Rust. For practical purpose, `std::collections::BTreeSet` is superior, so please use it.
