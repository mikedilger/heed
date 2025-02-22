# heed
A fully typed [LMDB](https://en.wikipedia.org/wiki/Lightning_Memory-Mapped_Database) wrapper with minimum overhead, uses bytemuck internally.

[![License](https://img.shields.io/badge/license-MIT-green)](#LICENSE)
[![Crates.io](https://img.shields.io/crates/v/heed)](https://crates.io/crates/heed)
[![Docs](https://docs.rs/heed/badge.svg)](https://docs.rs/heed)
[![dependency status](https://deps.rs/repo/github/meilisearch/heed/status.svg)](https://deps.rs/repo/github/meilisearch/heed)
[![Build](https://github.com/meilisearch/heed/actions/workflows/rust.yml/badge.svg)](https://github.com/meilisearch/heed/actions/workflows/rust.yml)

![the opposite of heed](https://thesaurus.plus/img/antonyms/153/heed.png)

This library is able to serialize all kind of types, not just bytes slices, even _Serde_ types are supported.

Go check out [the examples](heed/examples/).

## Building from Source

### Using the system LMDB if available

If you don't already have clone the repository you can use this command:

```bash
git clone --recursive https://github.com/meilisearch/heed.git
cd heed
cargo build
```

However, if you already cloned it and forgot about the initializing the submodules:

```bash
git submodule update --init
```
