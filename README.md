# Repolex Knowledge Graph of explosion/spacy-curated-transformers

RDF knowledge graph data for [explosion/spacy-curated-transformers](https://github.com/explosion/spacy-curated-transformers), parsed by [repolex](https://repolex.ai).

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
rlex download explosion/spacy-curated-transformers
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── be9875be64363f6540ce073ee936bd32a948693d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── be9875be64363f6540ce073ee936bd32a948693d
│           └── chunk-001.nq.gz
├── blob
│   ├── 0b4b7bab291901cff4cb9748d66775dfcaf010ba.nq.gz
│   ├── 1075d703575527e363de00d130c733f96a6c4c34.nq.gz
│   ├── 1c0a5540a9e0740c673283e2566eff66884addb1.nq.gz
│   ├── 21bfa21cb5382d6379ab04e82a56c5ffaaf062fc.nq.gz
│   ├── 27fbdd3a588be5998e358bd3d3d699b2c6c41d72.nq.gz
│   ├── 28278a28c8fa8355b67419e3333f2f61859c61b5.nq.gz
│   ├── 2a6b7487daa85ae817fbab6bcad6aad0dc527550.nq.gz
│   ├── 343b5417ecc47d5de2e3905a88765c0e9a0228f8.nq.gz
│   ├── 361536c48ee40ddd63da74aed81bfa908ecf5b82.nq.gz
│   ├── 38eee473778798eaeaaeb9c439ca0950187dcdd9.nq.gz
│   ├── 3af8060dba870aac31bba2badb5c2ad1f3847bbc.nq.gz
│   ├── 3d4fded10fddcb5590f4e2a2320bcfa1726fa1ac.nq.gz
│   ├── 3dc08e8490078707355e5a1a722a1e61c5b5c3f6.nq.gz
│   ├── 47fffae79e6520883728494d26ef51be46c38bda.nq.gz
│   ├── 4d05f44965d1b77766bff296e2c8778b9752397a.nq.gz
│   ├── 4d4b944a0d00d72a0cdcde076c81e079546a4939.nq.gz
│   ├── 4df4e73ec5b7c0806c876482765f6c7744c51639.nq.gz
│   ├── 5a172f98b642ba34d753ea74a595e3e7368b70ac.nq.gz
│   ├── 5c6e2bc5b4b446511c3ca4a289234abbe4c9a875.nq.gz
│   ├── 5daea2f6974efa13895e70a1770a133264b48653.nq.gz
│   ├── 5f94a950a27da174c266615c8980c76371906807.nq.gz
│   ├── 6847a9c0c59130bf4180bdd94e4e27e56c55cfc5.nq.gz
│   ├── 69f9f8fa101c115496daf843c15e76c6058483d8.nq.gz
│   ├── 6ab1215fe2350ae74e039dc0cef185c738a60050.nq.gz
│   ├── 6bc145d8bd08d27177f0b8f55025760845846b9f.nq.gz
│   ├── 6c0d460196ae1d12630ff8471214865e521abf70.nq.gz
│   ├── 6ca8216ffef798121ff9ce7f6ecfb47756a069e3.nq.gz
│   ├── 70ab676c51f9cebf3916fc35c7e05f1a4952b915.nq.gz
│   ├── 71b39fd6e5fc97a2f2cd7ff03f69baf8b04638cd.nq.gz
│   ├── 7b1d0cd323c8c15101ab2f5d8e9397569428db1b.nq.gz
│   ├── 7b45ce2c297b265919682a6632c0eb5df26ea6eb.nq.gz
│   ├── 7f4fba8a1e12383ee10195bfe3fd0d6f316aeb27.nq.gz
│   ├── 8084b41080a8ee53fcc1e1bb8b228c74b5609457.nq.gz
│   ├── 8a3d529a6c191ca978f3d2636aefae5ee2379cea.nq.gz
│   ├── 8fbeeb55edf11f2ebcb8507934b6adbd90d0793f.nq.gz
│   ├── 903dcd524575c7622dc5b78f06f6b5b0a6c31e71.nq.gz
│   ├── 9097672f83bc00402823bf5016d7c73a2b646bd2.nq.gz
│   ├── 92a11e248cb11dc3efc62849c5b3fa305508cba2.nq.gz
│   ├── 9a771be712ce2b4b83c1e9137d12b48534630f79.nq.gz
│   ├── 9ac3c35f5d6bd3ccfa3b354be4f62148291e2d25.nq.gz
│   ├── 9acc959890c0792545bcd742d582189d1ba79db3.nq.gz
│   ├── 9b0bf082423dce5efd271c32d5a1352569fb1d61.nq.gz
│   ├── 9c406323575718caf810ba61e1a6d76384fe59dd.nq.gz
│   ├── 9eee1db1e6352cfe9d8ccce7be4c69e29da478c2.nq.gz
│   ├── 9f80153718b937a6dc407a1bde9db20794451c57.nq.gz
│   ├── a0bce221b30ddeacf106b76281d9e6ebfdcfdf94.nq.gz
│   ├── ad9a520c31185ae908227f7f4f44782ad694b0a4.nq.gz
│   ├── b6ed43f7a8d3cc33f018048f20d3780890359292.nq.gz
│   ├── b98b64dc3577edf0f79daa5f581e5c3ad4cf98bf.nq.gz
│   ├── b9ddb42cb4cb60db69d657516748fcd672c0b872.nq.gz
│   ├── bc1d9ce29d4435118385ce6fe468c1cacb5e2adb.nq.gz
│   ├── bcd5198b79841d8e110974297b3dea71666a2c71.nq.gz
│   ├── c02e173231609ad8ce06edecaab7e018b557614a.nq.gz
│   ├── c1f3faeaaea3211e95ae195280b3fd2496a44761.nq.gz
│   ├── c281f19b1494c597e12b140a0292f52e2df8b762.nq.gz
│   ├── c8087849beb2fdc984a6d454848557095429840c.nq.gz
│   ├── cdfee3140adeb765c2b114e793e70d6f69839e10.nq.gz
│   ├── d8c58e4bb31c246beff22c110e712d57d1a7a0f2.nq.gz
│   ├── dc4f5198ea1d74bf91620176023b5ec962539bf8.nq.gz
│   ├── e4c7e497e4c71d1b80aac4e142c78c1095b8106e.nq.gz
│   ├── e5b677a5b4d8b6a1327999a93d3a3ca76c2f1c0a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7a9a69dc509cd6fdda280b5095bac24834b953e.nq.gz
│   ├── e8e0b848fa20b0ae24d3b7a0c9d305af23b4e30a.nq.gz
│   ├── f26dbf5b74d91253d08fa5cf21ac3b365c65fc92.nq.gz
│   ├── f414c05e359d4f8004a2518f5bbd8ced57ecff0e.nq.gz
│   ├── fd1447c03fa5aad419a1c7bbb8ebb9b1b9acaf36.nq.gz
│   └── fd211f5dcec99062e8742232068133c1880c4fbf.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── be9875be64363f6540ce073ee936bd32a948693d.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 75 files
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

[explosion/spacy-curated-transformers](https://github.com/explosion/spacy-curated-transformers)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
