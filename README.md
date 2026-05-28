# pleme-isvariant-derive

Per-variant matches-style predicate: pub fn is_<variant>(&self) -> bool. Generated from a tatara-rust-ast PerVariantDeriveSpec.

[![Build](https://github.com/pleme-io/pleme-isvariant-derive/actions/workflows/auto-release.yml/badge.svg)](#)
[![crates.io](https://img.shields.io/crates/v/pleme-isvariant-derive.svg)](https://crates.io/crates/pleme-isvariant-derive)

## Install

```toml
[dependencies]
pleme-isvariant-derive = "*"
```

## Generation

This crate is mechanically emitted by [`tatara-rust-ast`](https://github.com/pleme-io/tatara-rust-ast). The author surface is a typed `(defmacro …)` Spec — the proc-macro implementation, tests, Nix flake, caixa wrapper, and CI workflow are all generated. See the catalog at `catalog.json` in the parent registry.
