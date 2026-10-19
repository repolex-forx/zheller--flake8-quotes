# Repolex Knowledge Graph of zheller/flake8-quotes

RDF knowledge graph data for [zheller/flake8-quotes](https://github.com/zheller/flake8-quotes), parsed by [repolex](https://repolex.ai).

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
rlex download zheller/flake8-quotes
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e75accbd40f0e1fa1e8f0e746b93c9766db8f106
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e75accbd40f0e1fa1e8f0e746b93c9766db8f106
│           └── chunk-001.nq.gz
├── blob
│   ├── 0578c09900fc3e8a51335d2042c01a39a9b9660a.nq.gz
│   ├── 08c56ff8e12a825603f5734dba13036303a5b784.nq.gz
│   ├── 0a7f85ef56a63c74d31588ece0eaec1d66e75dee.nq.gz
│   ├── 0e5935648823c40a8c6eb3a3f9a9d69d14103fb5.nq.gz
│   ├── 116da38184726a6e88e90157ec2b7de355cfa38c.nq.gz
│   ├── 152e015cabeace06f4ae5da99574b95125e44511.nq.gz
│   ├── 2545767414e5f03ba3b25d307fe865a663b32c4f.nq.gz
│   ├── 3684034d7a1c32e6de9bd36175719c33db2ea7df.nq.gz
│   ├── 369637051e1599bcd5d513cd2cee45258416fd18.nq.gz
│   ├── 39d1daa4a373a7ab990a34c1dfb13917c142773a.nq.gz
│   ├── 4248918459d21b998daed319f2b63307bd80f16f.nq.gz
│   ├── 50c241fa3e529886558103d7ace2201db25718c2.nq.gz
│   ├── 571aebf844baac8d7fdd7c5474a874f2f233a5df.nq.gz
│   ├── 5a7e641b34905bf9f6e737641b9273a75504d622.nq.gz
│   ├── 609e51768a28fc02631b0cef7542d8578630938e.nq.gz
│   ├── 6ad330e8a0e0dc48d9325893b6851f56a4e2dc56.nq.gz
│   ├── 6f79509c218724a88e1571d42ebfd608c37bbbbc.nq.gz
│   ├── 7495b6317ddb75010398ad304aa54432d06e3289.nq.gz
│   ├── 7b2675a35483d3556f93d69d50c16ec8caa04c87.nq.gz
│   ├── 80ae1bd2ae07b846a028ac6b3bfaa92a7104df1a.nq.gz
│   ├── 816eeb97db048e6a96c8653fafc4b074456e1dfd.nq.gz
│   ├── 825ae7e2792a9bf11b20e380d426ea14e0402f53.nq.gz
│   ├── 85acebb03fc54295ed967399a67d5db1aa452edd.nq.gz
│   ├── 89de354795ec7a7cdab07c091029653d3618540d.nq.gz
│   ├── 8b32a0b524fc195b387ae61233bb12fb98b2b308.nq.gz
│   ├── 9e546e2fa0d0a36fab7e2635a662ef8ba43138d7.nq.gz
│   ├── 9eabf07e517116526aaf534f5d9e6ccaa63dc547.nq.gz
│   ├── ab17dab3d5c1a083ea2279adc436682fb8137d12.nq.gz
│   ├── ad6f8cd1c7886a703fb1d54ca5f7b3112e5c9846.nq.gz
│   ├── b11fa21be1df81330b1e47c11392aa57909948b7.nq.gz
│   ├── b1c8aa06ac4718c8f0b903345e7e287c37b62722.nq.gz
│   ├── b8b277ed1c5547831af0416ff553ca3323d07216.nq.gz
│   ├── c359a409d634a76d83f86fac0843e1049d28db24.nq.gz
│   ├── c7ec4e2e73cdc61e6e045aa76dfcd8388cf7f543.nq.gz
│   ├── ce71335ff089068236d89765284dbbb8cb37feae.nq.gz
│   ├── cf45f36e8d90446dcdf6a41c5bd586feec8b90a8.nq.gz
│   ├── cfb857c2524e2681e29e8efcb43405e32b6a10db.nq.gz
│   ├── d06aa162d2b2dc14bb185e22e9dd1cc96b65b539.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eaceabcb5303696ff9b8c045b14875ee9b8f5857.nq.gz
│   ├── f6310076385fa1fbf299fe9a50a35e80039d9833.nq.gz
│   └── f8fe9c5eca8cb3defb19cd1b597cc4cb036fb75f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e75accbd40f0e1fa1e8f0e746b93c9766db8f106.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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

[zheller/flake8-quotes](https://github.com/zheller/flake8-quotes)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
