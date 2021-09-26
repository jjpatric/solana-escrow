### Environment Setup
1. Install Rust from https://rustup.rs/
2. Install Solana v1.6.2 or later from https://docs.solana.com/cli/install-solana-cli-tools#use-solanas-install-tool

### Build and test for program compiled natively
```
$ cargo build
$ cargo test
```

### Build and test the program compiled for BPF
```
$ cargo build-bpf
$ cargo test-bpf
```


Last time I go up to [here](https://paulx.dev/blog/2021/01/14/programming-on-solana-an-introduction/#trying-out-the-program-understanding-alice-s-transaction)

Still having errors running `cargo build-bpf` because the feature 'resolver' is required, even though I added `cargo-features = ["resolver"]` to Cargo.toml
