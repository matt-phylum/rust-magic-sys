rust-magic-sys
==============

[Rust](http://www.rust-lang.org/) declarations for [libmagic](http://darwinsys.com/file/).

---

This [cargo -sys package](http://doc.crates.io/build-script.html#*-sys-packages) provides `libmagic` declarations for e.g. the [`magic` binding](https://github.com/robo9k/rust-magic).


# Usage

[`magic-sys` is available on crates.io](https://crates.io/crates/magic-sys) so you can use it like this (in your `Cargo.toml`):

```toml
[dependencies.magic-sys]
version = "0.0.4"
```