# Repolex Knowledge Graph of PennyLaneAI/pennylane-sphinx-theme

RDF knowledge graph data for [PennyLaneAI/pennylane-sphinx-theme](https://github.com/PennyLaneAI/pennylane-sphinx-theme), parsed by [repolex](https://repolex.ai).

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
rlex download PennyLaneAI/pennylane-sphinx-theme
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e9d5dcf0ff6048fbb23e8fb5e28d0628108a7bfa
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e9d5dcf0ff6048fbb23e8fb5e28d0628108a7bfa
│           └── chunk-001.nq.gz
├── blob
│   ├── 009eba9bec9352a3139c3dd48ae25f3bcd246db7.nq.gz
│   ├── 052f1cf4e31d4974ea9b65a593584f7e1d557c54.nq.gz
│   ├── 10979399423feb10cad9c0b73a2965bf790a14d5.nq.gz
│   ├── 17e5fd7d1bd829fa4fab5da1578094e67123dc68.nq.gz
│   ├── 1a1a65ad152e21348b22a6c2b23bd9c6caf12406.nq.gz
│   ├── 1bd1392bbd924fba026eacb603e1e24dd7382cb6.nq.gz
│   ├── 1d00515882a1bac6205331ab871a50e0a80d630b.nq.gz
│   ├── 1e3d51b77bd2ed6f15a3babdb61e17e58469d040.nq.gz
│   ├── 1fe2c21553bdcda1e958bd29644a522cfdda5f1a.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 273e1745d26019bca22ec16fcf4ebebefbeb4af3.nq.gz
│   ├── 2ad508a2b3acb619d064608d6fee05eb9ff1ce18.nq.gz
│   ├── 2c736af2cee0cbb816e2262cf44eff403eab9437.nq.gz
│   ├── 3556c0ba86d51d87992795334df98098530f743c.nq.gz
│   ├── 3837cc5a4d8e56cfc1fadba216b6d466112a054f.nq.gz
│   ├── 43e5fc880e4965a6ca952a1c7db1e91b6a2b00d6.nq.gz
│   ├── 4740ad8f03b73a6f997222f434d9e86d635027b8.nq.gz
│   ├── 48e1bcfb249e6677baa6e07f0c80ea24726d7d02.nq.gz
│   ├── 49077e8e0fd5cf771fdab0064190a450530fa21a.nq.gz
│   ├── 4be89762de406db2375d8b7651c82e3aaf6e549b.nq.gz
│   ├── 51bee1a627b57e0033e9ee69ac226a1ae9e11df3.nq.gz
│   ├── 5982e3b0456c104058d4f861b22592082d593798.nq.gz
│   ├── 667c50abd7ffb86721b6a188053415c7347e70bc.nq.gz
│   ├── 68a6a9d2b9b078cf6b0d5a4792806a29202f48d6.nq.gz
│   ├── 6c860a2b478a118c3a5f79891db01162b8886b39.nq.gz
│   ├── 6f699454cdb8246844141f84b8b768005f7d34ec.nq.gz
│   ├── 700f5bf5b7d519c87883f399d4894c6b856ce585.nq.gz
│   ├── 77c93323dbb1d69cc078ae11253c15376cb8c5ca.nq.gz
│   ├── 7af0be5f5aa3085ed170156707988de2336a40d2.nq.gz
│   ├── 7c32530ebf557b9361f132fb5768df73327d684c.nq.gz
│   ├── 82f74f47d8fb89896156096bed1cd93543bbc3e8.nq.gz
│   ├── 8314805c27a11488380329e1a719c28d6508b1c0.nq.gz
│   ├── 88bc15929db5cd12a8695e9d2d0ecfa54562002b.nq.gz
│   ├── 9001915c0a4d91593b00f6ce7f86992e1b0ecc37.nq.gz
│   ├── 9a61d5f2e65f978d7c5516b8844546cba8b8c32b.nq.gz
│   ├── 9ab80d791bfd0693dbe1817a22cf21339b7f4b17.nq.gz
│   ├── b0c4c353fe71a58b8a2d969ee59b1f4cefa6d83b.nq.gz
│   ├── b499ece057ec19d420619ecc06f73b922959a982.nq.gz
│   ├── b4c918587648d4e0f3e3c3d53048f2e93a64029b.nq.gz
│   ├── bcf8fed49a48515f47d2dd7931185f9211131989.nq.gz
│   ├── ccd42a7418acb128609371ae9e396f309edb4fca.nq.gz
│   ├── cf48864fa2286b6d4dce94bbc8ac60e5a1a9bcc4.nq.gz
│   ├── cf510d1b3ccda19d64692a87b998b1b0b134747a.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── da55fc50ab854a236ac9c71a7bb395aa9db8f2c9.nq.gz
│   ├── dccf4a189c8b8d29496a5904bcb36ea9ce04b115.nq.gz
│   ├── e18d4328547dad1c7fc329a4a5b5f295c7b787dd.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eaaea6f082213a5cc41fd56c76d739169bfcb7e8.nq.gz
│   └── f0e2a7a6a60eb482ae3c9d563be637ddcfefa989.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e9d5dcf0ff6048fbb23e8fb5e28d0628108a7bfa.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 58 files
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

[PennyLaneAI/pennylane-sphinx-theme](https://github.com/PennyLaneAI/pennylane-sphinx-theme)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
