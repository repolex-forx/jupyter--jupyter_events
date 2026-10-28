# Repolex Knowledge Graph of jupyter/jupyter_events

RDF knowledge graph data for [jupyter/jupyter_events](https://github.com/jupyter/jupyter_events), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download jupyter/jupyter_events
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── deb61b4924d808234d295fe316360f6478584acb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── deb61b4924d808234d295fe316360f6478584acb
│           └── chunk-001.nq.gz
├── blob
│   ├── 1cea1a855624c14898e94ea69831bbf463f2fa36.nq.gz
│   ├── 1ed845561ae35283f31eca9caad298aa98a7d905.nq.gz
│   ├── 201a1bcf5ee063b51436a5fd915d1f8c6af7f8d3.nq.gz
│   ├── 208e5c37e2d3579afc5b803a8b0306ae2d2a3a82.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 250201efa1f298a4a6d6fc6c612f2d16dcec7811.nq.gz
│   ├── 2793b7ecf9229b99c820df13239d131812a06eef.nq.gz
│   ├── 396330bb9729d2ec595617aef79fb28600d86bd7.nq.gz
│   ├── 3c5ade05c70fd2221e8c5b82a675c1099bf59bf9.nq.gz
│   ├── 44f282e727103c382808863ee20efb67b67ae4d1.nq.gz
│   ├── 50a49a5f581bb05b14104f751121e005bd2c2b29.nq.gz
│   ├── 5295e776b63d7adfab3ddad99962cc6f81968909.nq.gz
│   ├── 52defd3009b9e6007efed4b5c1521ef7bcd6ef73.nq.gz
│   ├── 597772b573424c5cc7f205fe3ec0d6b3d76ff5fa.nq.gz
│   ├── 5bc663e143708a12bf7ec74fe2620a2c0accc366.nq.gz
│   ├── 5e83f7822be668368c07c65c17a80a06e48aaf44.nq.gz
│   ├── 60af4c5f16741c7c2fe17cdd9718ae5f6d56d8a4.nq.gz
│   ├── 64eab5919461766b847ca23f624ba024702b381f.nq.gz
│   ├── 67f9c872e916d118aec00dac63013b80e7e01f25.nq.gz
│   ├── 6f0292a6354bb610f6b5cde515dde8bbd86de917.nq.gz
│   ├── 72487602dc70f46529dd118f13f8e9e7fdc9e801.nq.gz
│   ├── 725feab5ce652dc39f3f2c77b9fd3c90bf049c65.nq.gz
│   ├── 732464a3507eb395b6f5e9a065cd453d98056130.nq.gz
│   ├── 7a5b9ebf30b2a8f19766d2698ab2159f1ca6e4f5.nq.gz
│   ├── 7aef7d2b972365e7abc1043be65508be9e441acf.nq.gz
│   ├── 80c1c94f7b75b6bdaaf49c1418007f294546f3f8.nq.gz
│   ├── 86a947c85a0f430204ab880d475e18b4e9832c91.nq.gz
│   ├── 8c5852661efda8fb05840d03e3b8795b04b6f03a.nq.gz
│   ├── 8c6bf850f3c9dbd7a540a2047db9bce1c3cdcf9a.nq.gz
│   ├── 8cd3f482cd23de43e188d6a4fe470397ebcc433e.nq.gz
│   ├── 911d091056fbd2ede3ff9f7c17cc35348fbf4be2.nq.gz
│   ├── 919a9379f2a5ac3d72fe0a72b402e094bf1b36a7.nq.gz
│   ├── 930c027bb309563d6f66fe352d5fbc8abe58a2ce.nq.gz
│   ├── 9df341245f810962915027f03fab65dfc5619ca0.nq.gz
│   ├── b0ae5c6de2187058b87a816af0e820a23fb9bf8f.nq.gz
│   ├── b40f64426dc0d33dac00d9a4e13f0485761bb4f2.nq.gz
│   ├── b5ef5007a63736d2a9c3bdc4b0d0ab9260ec08ef.nq.gz
│   ├── b94a625460cd88e2e50488ee3b6ea3d040134036.nq.gz
│   ├── bd7a161112700bed9d9bcde07b3bd71378828c68.nq.gz
│   ├── c5eec32b6873e9b3063a1ef030264c89944706fe.nq.gz
│   ├── c7aa98e3f499b1db8ef688e6338aa572a65d8d1b.nq.gz
│   ├── c7bd6b178a20a17361a1c51118b98b99abb1d9db.nq.gz
│   ├── cac790cd5015b78a9b4cc4cd20c8403e6dc856ba.nq.gz
│   ├── d07f0be227246baa8675a2e4da003ba80da1edc2.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d7b38c0973ee05520d06d81c98847e0882d7a6c7.nq.gz
│   ├── d87f98248c524ff56ce2fc0063babfa6c260ae9f.nq.gz
│   ├── d9e2cf0486f14371a9e394ffe45207bd909593aa.nq.gz
│   ├── dc88c303bb2d82f04c68bbb808a98195666edde4.nq.gz
│   ├── dd45d6b20175e557cacae611518dcb6432383292.nq.gz
│   ├── e4ad08f8a37e7ac35ca125e91c50910a35bbef62.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6cc2d17e516b16bc97b9599bcb05a751005b1de.nq.gz
│   ├── e7f8c361b9d09d6486634c2211ae9eab7ca0bcff.nq.gz
│   ├── ed696d44e6519339c446301c735cde94175c7ae9.nq.gz
│   ├── f145aa8f9f472d7db252a04f013ca4730fe0ab5e.nq.gz
│   ├── f15bc19626b1608ed28ad89c71e668b063d6c955.nq.gz
│   ├── f181fd676260a69063eec7363d4586a0377e237a.nq.gz
│   ├── f8fad082457ad73e41fbe66e2117a13ce9d4ca70.nq.gz
│   ├── fcdd3e88b66ec9b10362685146ef2a36088e54f3.nq.gz
│   └── fe6c0d254bb25625107cb8c214ed2cc79ba4e9c1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── deb61b4924d808234d295fe316360f6478584acb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 69 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[jupyter/jupyter_events](https://github.com/jupyter/jupyter_events)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
