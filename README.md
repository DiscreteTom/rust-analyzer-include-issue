# rust analyzer include issue

See https://github.com/rust-lang/rust-analyzer/issues/17507

The demo project could be compiled and ran by:

```bash
cd project
cargo build && cargo run
```

However in VSCode the rust analyzer will report the following error:

```md
failed to load file `../../snippet.rs`rust-analyzer[macro-error](https://rust-analyzer.github.io/manual.html#macro-error)
```
