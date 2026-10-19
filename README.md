# Repolex Knowledge Graph of klen/mixer

RDF knowledge graph data for [klen/mixer](https://github.com/klen/mixer), parsed by [repolex](https://repolex.ai).

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
rlex download klen/mixer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 431ca2756af5571efc4d08d743fa8ab2a8619183
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 431ca2756af5571efc4d08d743fa8ab2a8619183
│           └── chunk-001.nq.gz
├── blob
│   ├── 0486fe57ce31be70bb544fe101da831d09787c1b.nq.gz
│   ├── 176f89d5fdae502392b6fc27beb83f82234c895e.nq.gz
│   ├── 2348c51ee4eaff6de79c90f28f79716ae6aac1c4.nq.gz
│   ├── 263218f2268f6822784621c68a92908e1dd286b8.nq.gz
│   ├── 2c4bd2342b3acf03028bcb6b3217aa5dd63bec74.nq.gz
│   ├── 2cc75280b41f3f59502c4d4dc75f034dc8624b1e.nq.gz
│   ├── 2d5b02b872343ac34d0029cdf3e3e2d0ac73dfae.nq.gz
│   ├── 2ee2cf3edd384d6b91d52f4302a1339ee3a92486.nq.gz
│   ├── 31e2f5fe067c24f18d5a9e3a4c5f714c05732ac2.nq.gz
│   ├── 3c95d35446f287f0a277764a03233146eb9b9371.nq.gz
│   ├── 3e136e13b59864dee71934499141c01cec50acd3.nq.gz
│   ├── 490e55b3cb8c12f4059bddfc2c39339575b438aa.nq.gz
│   ├── 4ac32c9885685b6094d67fa7db732ab6249487a9.nq.gz
│   ├── 4ad4e4c04d6dcc76ff26b6ab9eaff7967f189cfc.nq.gz
│   ├── 572aca3d15f4cbf3bae005b7df85eb778839545c.nq.gz
│   ├── 57a7491c8e0653ae0cc81592be264a9d1b5fb3f7.nq.gz
│   ├── 58d900d9959dcf0ea3119c7ec23d8b526cc4fafb.nq.gz
│   ├── 59a83955e96228b553d9c7cab060cfdde430f139.nq.gz
│   ├── 5e3d97ecd58add6c7b311284ea51b5e940ca3cc8.nq.gz
│   ├── 5f9b4c71bc50437e3a53ce30d3e1ccab5fa1de78.nq.gz
│   ├── 602a7af93c2d62a17aa1da66601ad4b434971d3e.nq.gz
│   ├── 6297a24a1588437da87b21a489957be3e302d72b.nq.gz
│   ├── 675e1d0f13c59c0eeccfb517f72e04c5cd6547c3.nq.gz
│   ├── 69392d807fda751a2ecaf17c0b91a48ae53e893b.nq.gz
│   ├── 694d6134ceb1ca271dfdfc30406b6cd6a03a9d33.nq.gz
│   ├── 6be4b1826df5ac0feed13bf16a51f700c9bd17b2.nq.gz
│   ├── 6d41f8946661187bef46b8fab7922e147ff26d29.nq.gz
│   ├── 71d5df00cd6c0967f2947c230951f3e648e2a417.nq.gz
│   ├── 764518e594e8d292abebb57d14eda222c20e7ba9.nq.gz
│   ├── 81c93c9204c4dfe93af2868bd2ae7f8b1f1f3e4d.nq.gz
│   ├── 87cf702c37f3d9d9fc82172028cbf52c00cf64f0.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 9147162b017c631f6d17bab60bd0194b6804cadd.nq.gz
│   ├── 97cd3def1c39e2590a99eaef43d3f77afa9ec735.nq.gz
│   ├── 9a235ccac15366f2f6ec53334999b10a19c36b9a.nq.gz
│   ├── 9a69a1e214ccb71f3a07ddc0863c71c6b0e881d0.nq.gz
│   ├── a2387bc518e49bb531913ff84069890f8b98c0c4.nq.gz
│   ├── a40c1ae4b1e5c0838d9f06bf21df1503e11d2616.nq.gz
│   ├── bc2862395e1ab8c43bd53f79d8c75531f3f17dcb.nq.gz
│   ├── c4089eb4ebf15bf988b76566b49c02ad98f3827a.nq.gz
│   ├── c505209f3376f664b7d9e510d8470aeba0cf8acc.nq.gz
│   ├── d00eda863076097349b40d4282c00abb82e510c9.nq.gz
│   ├── d22a79e4146156891a770b8f794356518e5ab734.nq.gz
│   ├── d5706c01af69454cb6273f0827320011df401986.nq.gz
│   ├── d76abf415d3832ebe0823b608f3d69329a85fe8c.nq.gz
│   ├── db62956b6f5c73ca969648d1b68fc8554b748af1.nq.gz
│   ├── dbe9d0a2a23dd4ad1d9d465de8e5fb762d17a81e.nq.gz
│   ├── e00ab7e9f72ff5ababdd645da2089eaf8c058eb7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ecca62f5064082a2ed76a62394465f7d12ae7e63.nq.gz
│   ├── f033f4d42c9e327944392f3d27d3c091b5b242b7.nq.gz
│   ├── f58dc11e30d39fdfd04a3245d088343e43e863bc.nq.gz
│   ├── f5cdc280ca63f1a8836c6c9be3a1ec87f16cc445.nq.gz
│   ├── f8ce0db07a3dfdcb3ab50a2aa3b4daaebe4cf10a.nq.gz
│   └── ff195d60547c775ad3c367c53d2c5439b1b59a38.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 431ca2756af5571efc4d08d743fa8ab2a8619183.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 63 files
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

[klen/mixer](https://github.com/klen/mixer)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
