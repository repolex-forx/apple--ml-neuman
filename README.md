# Repolex Knowledge Graph of apple/ml-neuman

RDF knowledge graph data for [apple/ml-neuman](https://github.com/apple/ml-neuman), parsed by [repolex](https://repolex.ai).

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
rlex download apple/ml-neuman
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 15d64ac218b1c8bd6a99ab876d2408898c859c69
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 15d64ac218b1c8bd6a99ab876d2408898c859c69
│           └── chunk-001.nq.gz
├── blob
│   ├── 03a938ccebfc35e47a7a0a1e0ebb9df826c7c5e1.nq.gz
│   ├── 08c9ae47e9263a463eb50bfaeea4752d629fc767.nq.gz
│   ├── 0c37b6cc29f46870606bf4b4402b5b1f6e56090e.nq.gz
│   ├── 113ab60df6d236be2bf995eedf74c86dd06d5642.nq.gz
│   ├── 13223504c541bcb00a1ff57e712059ab6a09d4e1.nq.gz
│   ├── 1483998424430150df61186b16d098e714e8a564.nq.gz
│   ├── 1e2b7334e4d8bc426a786fc3ab27c42610f6e3b7.nq.gz
│   ├── 20f63dc5310e421219d5b73e47ac522dc796229d.nq.gz
│   ├── 2fc5d3fc26d34b62885841556e6bfaf717f9f350.nq.gz
│   ├── 3179130c1a58d63433eb1814a91501a3db93a902.nq.gz
│   ├── 33c15bba594192b7028522e54fc6b8af9ff6916a.nq.gz
│   ├── 3e47282bdfa374992cdd0e8b3f1b1dfb3f690df7.nq.gz
│   ├── 408ba9c4012f910a996c9dcf3b8dbcb18cb529dc.nq.gz
│   ├── 4993fafce3927e185318eb53458ad039bbdd4e84.nq.gz
│   ├── 4c334f330e5b582919e79fa63044fdc24863eeb7.nq.gz
│   ├── 5008ddfcf53c02e82d7eee2e57c38e5672ef89f6.nq.gz
│   ├── 50bb07a997ee0ed89ebdebf7c12ba2f7e052a7e7.nq.gz
│   ├── 57336ec241333004bcfc9a5a6c893fcdc61b3976.nq.gz
│   ├── 584ce646feeec1755d69b0a547ee2747431a8eed.nq.gz
│   ├── 640e9535cf04c5c4d26c9d932f04266ad81a0588.nq.gz
│   ├── 68f09c1dda60cfcbeb3ee5d8f60f74cf57150a78.nq.gz
│   ├── 68f1224d5d7a46cc14b4857dc59c75e7bf325d7f.nq.gz
│   ├── 6b3d05a0781eeaa332e3339ba8fff0acc1d9279a.nq.gz
│   ├── 7052c0c21b18b3422b36a502276b0ee33abf4e77.nq.gz
│   ├── 7872be2cf48365bd51311167fcb206364033b7a8.nq.gz
│   ├── 7d890ec380485835c39221ff6efd162bca70386c.nq.gz
│   ├── 8368fcc84580745ac5c3535778e6095ea9d2979e.nq.gz
│   ├── a6105c51536bc52bd73a2efbb6425eaaa36a43bd.nq.gz
│   ├── a9ad5fb94c6957efdd934aaa42c2733ea78cc64d.nq.gz
│   ├── b2426f6b773ac056101154d20a3976d84672c3a7.nq.gz
│   ├── b26cf0b7ad6dfaba34eb1dce26618913aee4f1b1.nq.gz
│   ├── b3cee13ee2949892d298cbbda896b57c14084996.nq.gz
│   ├── b885c5f2f7bfaea7429e41738816cd4a41aaf093.nq.gz
│   ├── bc8eced64037318e54a425dddc4d920bb0e65a20.nq.gz
│   ├── bd4a708126a36de8a6be02346244dc4951aeb19e.nq.gz
│   ├── c6b6a089941bf68d2c8c7fccb9afb9af5a1892bf.nq.gz
│   ├── ca75d3faf50dd2d97032f08be38a92485bc6ae38.nq.gz
│   ├── d90226174d5134b4dae83f46e0670338381c708f.nq.gz
│   ├── dd2e51855ea04e4b96ccd3f7fef909ac16f4f5a6.nq.gz
│   ├── e2f23fad27304db101eb2e64c65156abc9c89ba5.nq.gz
│   ├── e4560dd2330c2a50b4ded0f4a9314f706246132a.nq.gz
│   ├── e613185655f30e349aeaa0a98e796e0f1a74c8da.nq.gz
│   ├── eda23db88d3fef9c1d641775f799076a69c6c0be.nq.gz
│   ├── f435309a6e9fed17d7a9146cca2e2897679d0fd4.nq.gz
│   ├── f74d733ce51625ebaac596ae1528474afed3765a.nq.gz
│   ├── f75cd62f3302fa0b2ab381af0e2a133eab88cd5b.nq.gz
│   └── fed0243f9008fadc949499a5a0f7f1f1fb3a697d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 15d64ac218b1c8bd6a99ab876d2408898c859c69.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 53 files
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

[apple/ml-neuman](https://github.com/apple/ml-neuman)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
