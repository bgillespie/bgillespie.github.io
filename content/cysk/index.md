+++
title = "Crates You Should Know"
date = 2020-09-16
template = "cysk.html"
+++

Some of these from [this Reddit thread](https://www.reddit.com/r/rust/comments/hat5bt/what_are_your_favorite_better_than_std_crates/).

## Libraries

### Niceties

* [anyhow](https://crates.io/crates/anyhow) - Easy idiomatic error handling.
* [thiserror](https://crates.io/crates/thiserror) - A convenient derive macro for the standard library's std::error::Error trait.
* [lazy_static](https://crates.io/crates/lazy_static)

### Data structures

* [itertools](https://crates.io/crates/itertools) - Extra iterator adaptors, iterator methods, free functions, and macros.
* [boolinator](https://crates.io/crates/boolinator) - Provides the Boolinator trait, which lets you use Option and Result-style combinators with bools.
* [bytes](https://crates.io/crates/bytes) - A utility library for working with bytes.
* [chrono](https://crates.io/crates/chrono) - Date and time library.
* [dashmap](https://crates.io/crates/dashmap) - Concurrent map.
* [regex](https://crates.io/crates/regex) - Parsing, compiling, and executing regular expressions.
* [slice-deque](https://crates.io/crates/slice_deque) - A double-ended queue that Derefs into a slice, also known as a ring buffer or circular buffer.

### System tools

* [nix](https://crates.io/crates/nix) - Rust bindings to *nix APIs.
* [winapi](https://crates.io/crates/winapi) - Rust bindings to Windows APIs.
* [socket2](https://crates.io/crates/socket2) - Utilities for handling sockets.

### Input / Output

* [serde](https://crates.io/crates/serde) - A framework for serializing and deserializing data structures efficiently and generically.
  * [serde-json](https://crates.io/crates/serde_json)
* [structopt](https://crates.io/crates/structopt) - Parse command line arguments by defining a struct.
* [clap](https://crates.io/crates/clap)

### Logging, debugging, observability

* [log](https://crates.io/crates/log)
* [fern](https://crates.io/crates/fern) - Simple, efficient logging.
* [tracing](https://crates.io/crates/tracing) - A framework for instrumenting Rust programs to collect structured, event-based diagnostic information.

### Async

* [crossbeam](https://crates.io/crates/crossbeam) - A set of tools for concurrent programming.
* [simple-mutex](https://crates.io/crates/simple-mutex) - More efficient than std::sync::Mutex and simpler than parking_lot::Mutex.
* [parking_lot](https://crates.io/crates/parking_lot) - Smaller, faster, more flexible synchronization primitives than those in `std`.
* [rayon](https://crates.io/crates/rayon) - Data parallelism library.
* [flume](https://crates.io/crates/flume) - An MPMC multi producer, multi consumer channel.
* [futures](https://crates.io/crates/futures) - Providing the foundations for asynchronous programming.
* [tokio](https://crates.io/crates/tokio) - A runtime for writing reliable, asynchronous, and slim applications.
* [async-std](https://crates.io/crates/async-std) - An async version of std. It provides all the interfaces you are used to, but in an async version and ready for Rust's async/await syntax.
* [ryu](https://crates.io/crates/ryu) - Quickly convert floating point numbers to decimal strings.

## CLI tools

* [exa](https://github.com/ogham/exa) - Replacement for `ls`.
* [bat](https://github.com/sharkdp/bat) - `cat` replacement.
* [fd](https://github.com/sharkdp/fd) - `find` replacement.
* [ripgrep](https://github.com/BurntSushi/ripgrep) - `grep` replacement.
* [sd](https://github.com/chmln/sd) - `sed` replacement.
* [dust](https://github.com/bootandy/dust) - `du` replacement.
* [ytop](https://github.com/cjbassi/ytop) - `top` replacement.
* [procs](https://github.com/dalance/procs) - `ps` replacement.
* [bandwhich](https://github.com/imsnif/bandwhich) - `iotop` replacement.
* [hyperfine](https://github.com/sharkdp/hyperfine) - `time` replacement.
* [tokei](https://github.com/XAMPPRocky/tokei) - Counts lines of code in a codebase, SLOC, plaintext, language code etc.
* [flamegraph](https://crates.io/crates/flamegraph) - Code profiler. Flamegraph generator with additional support for Cargo projects. It can be used to profile anything, not just Rust projects!

## Cargo plugins

* [cargo-geiger](https://crates.io/crates/cargo-geiger) - detects `unsafe` usages in crate and its dependencies.
* [cargo-edit](https://github.com/killercup/cargo-edit) - manage create dependencies in `Cargo.toml`.
* [cargo-upgrade](https://github.com/nabijaczleweli/cargo-update) - upgrade cargo-installed executables.

## Other

* [rustfmt](https://github.com/rust-lang/rustfmt) - Standard formatting for Rust code.
* [clippy](https://github.com/rust-lang/rust-clippy) - Linter for Rust code.
* [Evcxr](https://github.com/google/evcxr)
