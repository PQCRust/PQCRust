# PQCRust

This is all WIP


# Adding a new component to the project

To add a new component you simply follow the following procedure:

```sh
cd crates
cargo new pqcrust_<name of your library>
vim ../Cargo.toml
<insert "crates/pqcrust_<name of your library>" in the [workspace.members] section>
```
