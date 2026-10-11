# Repolex Knowledge Graph of jazzband/django-mongonaut

RDF knowledge graph data for [jazzband/django-mongonaut](https://github.com/jazzband/django-mongonaut), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-mongonaut
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6a008c7b8fca7dfcb132e41cdbcd3748d8ed2e3d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6a008c7b8fca7dfcb132e41cdbcd3748d8ed2e3d
│           └── chunk-001.nq.gz
├── blob
│   ├── 033a8744a7fa63a0fdb83c0c11fec009d21ec3d5.nq.gz
│   ├── 07b46a843f833be8b0a19a59eb75ee9afdfa07f0.nq.gz
│   ├── 10559b88d7b452ca9614809a1f50a1954d060942.nq.gz
│   ├── 158a8831accb40257a16da96913ac1b776580f6d.nq.gz
│   ├── 21cf6fba6a17437417e08042911a3508511782e9.nq.gz
│   ├── 22879a7ed5f4193b0941bbc22b78417c04af25cf.nq.gz
│   ├── 244272422b554c1d6d40bd4da97d66f2e1b9438d.nq.gz
│   ├── 2930c18f901cc1709821550bb29803253192a737.nq.gz
│   ├── 2a24d86250dbee071cc3fd68dfcac2df8a88b39c.nq.gz
│   ├── 2af59a66175faca0b91cb13e15b3e35e3f2842b6.nq.gz
│   ├── 2c8bb4c5eb0a337b3c19cd448dcd91cc668328fb.nq.gz
│   ├── 315c3fd8c744d85d0abf4625893660a6d6abedd9.nq.gz
│   ├── 318c070311805e1fe48b357d7d6f3cdb631099c0.nq.gz
│   ├── 35480515632dcaeae097f13d0df96ef92c3b3a42.nq.gz
│   ├── 3739092fc3078805e13ab6a71a43a03b5a3f0bc5.nq.gz
│   ├── 394c4511fa03f53b01ed4990992fd57efb7cd202.nq.gz
│   ├── 3fe1f0cb4d23ee1624a5967284419e97099f7de2.nq.gz
│   ├── 409795edb5603a581503d4ba058563d90a0ccee7.nq.gz
│   ├── 42fc2509716ee91316bf413d14a0f654b6dfe68d.nq.gz
│   ├── 45e68c325804de6b44c9549d978be149f0c35fe5.nq.gz
│   ├── 4a457a23074da4db74cccbcc14075931e7f17b12.nq.gz
│   ├── 4ad81d7f14d7174cb36bee83d6ecc4862591fe35.nq.gz
│   ├── 4e8991e8545335b8659f8857148f50c63389ed67.nq.gz
│   ├── 4f29f27741f575cab45ac54af5c8f79fc9cfb7a0.nq.gz
│   ├── 5b16ac7d40c11b3c0b077c92e997f113e88e5d98.nq.gz
│   ├── 5bbcbedeaf08bc972822276631407d553e98dbc8.nq.gz
│   ├── 5bd4da661926b9e60eda87b6cdd2821b000dccbf.nq.gz
│   ├── 68012d6c44c3cd4a83dd888324ce09044906be4d.nq.gz
│   ├── 6a2118e8376790b68fd06c05c01654e32d740e85.nq.gz
│   ├── 725573f232a6b594a251363aa282dc135c9c5cd2.nq.gz
│   ├── 81fffa54a9a9f91b06311e9a83d8a832f2efa48b.nq.gz
│   ├── 846f6b4061a68eda58bc9c76c36603d1e7721ee8.nq.gz
│   ├── 8ee589760d242a358287ef93209785b01be5d7a8.nq.gz
│   ├── 901441ed4c0fd2e61fe775056d204a5a1355ee6c.nq.gz
│   ├── 91d6b22bc8fba7987a608515cebf57fa66f52c72.nq.gz
│   ├── 9b633be044b4d33faa7f1dad30e773ea9a16f360.nq.gz
│   ├── 9bd41a1f2d4b4dadf8651e4fa3fb191982c74503.nq.gz
│   ├── a77ef3784094304ec866162831261d07b14a51c0.nq.gz
│   ├── a7ce3c57530cd724da417601b69a01f50210216a.nq.gz
│   ├── ae8fe1df253f163e1160b2997da7a415e7911add.nq.gz
│   ├── b2b34b877a151d63905905869ca38f8789f3673f.nq.gz
│   ├── b4e1878bcbd558b0776c97d290bb7eb46c98a51c.nq.gz
│   ├── b6598b48a0b5b887ecf64516d473f84b5ed72ce3.nq.gz
│   ├── bedf2a1edb988ca4fd27ccb41f180210fe3f0b8f.nq.gz
│   ├── bfe7bd19fd00094db7cad25fc1ef391cb5d28f74.nq.gz
│   ├── c07ed31f8e165678cd8d7a6185a8b5ed54c6b92a.nq.gz
│   ├── c57f27b5b7761accae21ac156160d413c721c78b.nq.gz
│   ├── c73596f1cbf42846e8d6ffd972a3895921718ea2.nq.gz
│   ├── cf02f9e7abe66b3ecefd0d5ecd12efd7c484c6bf.nq.gz
│   ├── d639492eaadbbf68ff83e43d0bad5664c7cff41b.nq.gz
│   ├── d8994d57a61df433d8b13994dd56c5ff28550758.nq.gz
│   ├── da6b917a1cff578d863a912d7d0f510790b9a74e.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e95f8221f5139ee303e1e29a89a9f8392cbf36f9.nq.gz
│   ├── eacae63e947efae92907bb0f8ec07d40dadae0c8.nq.gz
│   ├── f0047c336f3e6a4d8ef149f412a2b9fef875298d.nq.gz
│   ├── f2fd028976047af75d14104adda3645044ef3209.nq.gz
│   ├── f98f4bf9f55f18e270c189322dddd98976ca425b.nq.gz
│   ├── fd1a45c03c75a92b38dde5a0702161691ee21522.nq.gz
│   ├── fdb613b60e0735348cc22cdca59739da81d2d0eb.nq.gz
│   └── fdc3588b25f4692511cdbe0c2d755da107bb10a1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6a008c7b8fca7dfcb132e41cdbcd3748d8ed2e3d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 70 files
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

[jazzband/django-mongonaut](https://github.com/jazzband/django-mongonaut)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
