Sandbox javascript inside components.

Main idea is to load javascript functions from wasi blob/kv.

```
cargo build
wasmtime run ./target/wasm32-wasip2/debug/jazz.wasm
```
