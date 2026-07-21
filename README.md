# writing-an-os-with-rust

a small operating system written in Rust, built by following the "Writing an OS in Rust" blog series by Philipp Oppermann.

## about

this is a learning project where im building a minimal kernel from scratch. it covers stuff like:
- freestanding rust binaries (no std lib)
- a bootable kernel for x86_64
- VGA text mode output
- unit and integration testing in `no_std`
- CPU exceptions and interrupts
- paging and memory management
- heap allocation and custom allocators
- async/await and cooperative multitasking

## getting started

### prerequisites
- rust (nightly toolchain)
- `bootimage` crate
- QEMU (to run the OS)

### build and run
```bash
cargo build
cargo run
```

## status

work in progress, following the whole series post by post.

## contributors

- [Fanizza Tahir](https://www.linkedin.com/in/fttahir/)
- [Muhammad Rayan Khan](https://www.linkedin.com/in/muhammad-rayan-30604b252/)

## license

this project is licensed under the MIT License. see the [LICENSE](LICENSE) file for details.

## references

- [Writing an OS in Rust](https://os.phil-opp.com/)
- [The Rust Programming Language (PDF)](https://www.scs.stanford.edu/~zyedidia/docs/rust/rust_book.pdf)
- [Rust Documentation](https://doc.rust-lang.org/stable/)
- [The Rust Book](https://doc.rust-lang.org/stable/book/)
- [The Rust Book (GitHub)](https://rust-lang.github.io/book/)
- [Writing an OS in Rust (YouTube playlist)](https://youtube.com/playlist?list=PLib6-zlkjfXkdCjQgrZhmfJOWBk_C2FTY)
