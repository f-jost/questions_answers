# Q&A

## Technologies

- Rust
- Cargo

### Run the project by executing:
- `cargo run` will compile it in a `target` folder for development (non optimized) then execute the binary from `target/debug` folder

or

- `cargo run --release` will compile it in a `target` folder for production (optimized) then execute the binary from `target/release` folder

### Build without executing:

You can choose to only build the project without running it by execute:

- `cargo build` will compile it in a `target` folder for development (non optimized)

or

- `cargo build --release` will compile it in a `target` folder for production (optimized)

You can then run the binary by either use `cargo run` or `cargo run --release` from the project root,
or just execute it by calling it. Example for running the optimized binary
you can just call `./target/release/questions_answers`

### Useful resources:

#### Rust
- Website: https://www.rust-lang.org/
- The Book: https://doc.rust-lang.org/book/
- The Reference (more details than the book): https://doc.rust-lang.org/reference/index.html

#### Cargo
- Documentation: https://doc.rust-lang.org/cargo/index.html
