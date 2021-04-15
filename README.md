# Rust basics

Learning rust in the open. Committing everything I learn, big and small.

## Current focus

[Working through the main language book.](https://doc.rust-lang.org/book/title-page.html)

## Random things I'm finding interesting

> Rust is an ahead-of-time compiled language, meaning you can compile a program and give the executable to someone else, and they can run it even without having Rust installed.
>
> <https://doc.rust-lang.org/book/ch01-02-hello-world.html>

Key commands:

```rs
cargo build
cargo run // main one
cargo check
```

No string interpolation. Appalling.

> A few number types can have a value between 1 and 100: i32, a 32-bit number; u32, an unsigned 32-bit number; i64, a 64-bit number; as well as others. Rust defaults to an i32, which is the type of secret_number unless you add type information elsewhere that would cause Rust to infer a different numerical type.
>
> <https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html>
