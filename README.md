# rust

## Project
Single page web application

## Pre-requisites
- cargo
- web-assembly

## Procedure
Install cargo
```bash
sudo pacman -S cargo
```

```rust
cargo install wasm-pack 
```
Compile Rust to Wasm and generate JS interop code

```rust
cargo install cargo-make
```
Task runner

```rust
cargo install simple-http-server
```
simple server to serve assets

## Troubleshooting

Issue: wasm32-unknown-unknown target not found

Solution:
```bash
sudo pacman -S rustup
```

```bash
rustup default stable
```

```bash
rustup target add wasm32-unknown-unknown
```

### Useful links
https://www.sheshbabu.com/posts/rust-wasm-yew-single-page-application/
