# intermezzOS: The Book

## Prerequisites

This project is built using [Rust], so you'll need to
install Rust in order to build the book. 

[`multi-rust`] is the recommended way to install Rust.

You also can download Rust [here][1].

## Up and Running

```
$ cargo install mdbook
$ mdbook build
``` 

The [`mdbook`] crate builds from `markdown` files in `/src`,
creating `html` files in a `/book` directory.

Open `index.html` in your browser to view the built book.

[`mdbook`]: https://github.com/azerupi/mdBook
[1]: https://www.rust-lang.org/downloads.html
[`multi-rust`]: https://github.com/brson/multirust
[Rust]: http://www.rust-lang.org
