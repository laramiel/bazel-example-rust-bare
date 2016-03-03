# bazel-example-rust-bare

An example project demonstrating bazel build rules for rust.
This repository contains a remote library, without BUILD
rules or WORKSPACE.

This example can be compiled without bazel using:
```
rustc --crate-type=lib bare.rs
```

