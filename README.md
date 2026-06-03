# @plurnk/plurnk-mimetypes-grammar-julia

Pre-built `tree-sitter-julia` WASM grammar for the [@plurnk/plurnk-mimetypes](https://github.com/plurnk/plurnk-mimetypes) framework.

## install

```
npm i @plurnk/plurnk-mimetypes-grammar-julia
```

## what's in here

- **`julia.wasm`** — pre-built from the pinned upstream [tree-sitter-julia](https://github.com/tree-sitter/tree-sitter-julia) commit (SHA in `.grammar-pin`)
- `scripts/build-wasm.mjs` — reproducible rebuild from the pinned source
- `scripts/verify-wasm.mjs` — CI byte-identical reproducibility check

Declares only `web-tree-sitter` as a peer — no native `tree-sitter`, no node-gyp.

## license

MIT. The bundled `julia.wasm` is built from the upstream tree-sitter-julia grammar; see the pinned commit for that project's attribution.
