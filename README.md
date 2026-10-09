# Repolex Knowledge Graph of modelcontextprotocol/example-remote-server

RDF knowledge graph data for [modelcontextprotocol/example-remote-server](https://github.com/modelcontextprotocol/example-remote-server), parsed by [repolex](https://repolex.ai).

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
rlex download modelcontextprotocol/example-remote-server
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ca6133a4e63d22e2c035defa691d241ce22296a9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ca6133a4e63d22e2c035defa691d241ce22296a9
│           └── chunk-001.nq.gz
├── blob
│   ├── 0c9bb56b9849b1bd43a8423165d15aaedbb532ef.nq.gz
│   ├── 0db1a7f8999dc66a805727205d5ec82002980528.nq.gz
│   ├── 0e1d3e74f8a07cda05a4cec35508e2eb7c196bf4.nq.gz
│   ├── 128d1e747c42ea2c60af62c23458cb190d2ed1ef.nq.gz
│   ├── 133e22117fe03519c277bcf7fc82831321fe76bc.nq.gz
│   ├── 140705d0040bf14118b3950e96924c9ace55c936.nq.gz
│   ├── 170e17b3d021bdcb4d6bcde0b44cc0244f94f829.nq.gz
│   ├── 17acef4457956a2f86d07fdaa59966746605cffb.nq.gz
│   ├── 1ca5b2e19916a608edd4b2d4e53592d59a5b0306.nq.gz
│   ├── 1cfde8e003720c0b7cb59e77419322bd34f0ebfb.nq.gz
│   ├── 1e28e8f47e186c41ab0a7a269349a46d870d2047.nq.gz
│   ├── 21a7d583907d6a86974cfd47a72ad8de967e85e4.nq.gz
│   ├── 22b6713d8fc3ac47946cb7c2f00bef57a42f4db6.nq.gz
│   ├── 296a33753349077bd0fbedb4ac7cdb95c040ee7c.nq.gz
│   ├── 2ff897ae6bf91a8924ddfbd6ecf24a0151e9c486.nq.gz
│   ├── 325b2e8c8217c6b3287611d03549b6aa9b8aff9a.nq.gz
│   ├── 383dd5606b5c877220542d4d69ba2b19abd185e3.nq.gz
│   ├── 3952583d3f59491fce4743fcbf14ef5fea4559a4.nq.gz
│   ├── 3c478bf7bbe4da1ea9ae98aaf12f1b999b5045ee.nq.gz
│   ├── 400754193f6f22cda91b7b7879cbd0925225b5bf.nq.gz
│   ├── 4f25f50053d6cb96e1aaa131fc1d88f67507246c.nq.gz
│   ├── 515114cf28faceb1fca2fe1f15cbd5e746e11285.nq.gz
│   ├── 519e3d8081ee482478e2773541f666dd0bd52bf1.nq.gz
│   ├── 536f514336395049eab9de9df15f6700ac0b64c3.nq.gz
│   ├── 596a3db383e9af0b168b5a39940e298c63fded92.nq.gz
│   ├── 5feb735844d69192ada763057960ddd9146ae521.nq.gz
│   ├── 6eb445b60d8d3d9daae65ec3a5a0e6f657a528af.nq.gz
│   ├── 6f4c11f231ed51170f9adb80a40f681acdb847a2.nq.gz
│   ├── 70a51fa2e28a3fc300facb183d2315034d9edc62.nq.gz
│   ├── 7cbc7427c07f879f834dbbade7e1d04976abdeca.nq.gz
│   ├── 7d46710cd97a75d68798cea6111d75b3640c476d.nq.gz
│   ├── 7dacbf4ed922fcb79f6c6500d75331eabb043601.nq.gz
│   ├── 83979f0124171aa4c2d4890da8befa358bd6ed6e.nq.gz
│   ├── 86c52662d890dd8ebf115d6c228f36748c77176e.nq.gz
│   ├── 877b5dc57adca1ea4901a74d4c75c06bc2ba6075.nq.gz
│   ├── 87825b99d8a0f8ae26c3c4606ebe699a5a216dca.nq.gz
│   ├── 879f18ecd222ce1ecc50168883b83203f9341bf3.nq.gz
│   ├── 8a104e3d5bd4d243162ad098250a0a4a61add4ff.nq.gz
│   ├── 906f34cc344b26786762a4e45bcd15f7ce87941e.nq.gz
│   ├── 9afcdc1b9fc0b3b38482be37de8fa6adc953ae5e.nq.gz
│   ├── 9ff82e75f513bea6bfc9a0ffeca54ef4daafe7e8.nq.gz
│   ├── a1c05c76ca622d8be884c92821cd7e4b0fd2b5f2.nq.gz
│   ├── ad4abf04f5a9b8b659725f5b25c694ad238fcc24.nq.gz
│   ├── ad75c9e774b8073e78474d009a7da582410a7d03.nq.gz
│   ├── c004e356d66ba9679bd4a87022126c585e054312.nq.gz
│   ├── c3767e8b179ee46cb8a39a69706a95b94278d1f8.nq.gz
│   ├── c6c807fadaeca81c0a239a0e146bf971aaa0d2e9.nq.gz
│   ├── d3f9154cef526dda1e87fa3daaec58f78985447f.nq.gz
│   ├── d76233ce961290e8cdcb68b79ec727068e14f2af.nq.gz
│   ├── df32289f0b85d98885223ff71b626fe979fe2b73.nq.gz
│   ├── e013615c061e7cde8a793ba84d53f7fbf60ca820.nq.gz
│   ├── e265494cc8b913679c0410674164cdffc90cd3dc.nq.gz
│   ├── e5aa393f69944d60d811766b673e999c904af639.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec74fe4fdb0ba459041a389aafe09e05ee75f745.nq.gz
│   ├── f33a02cd16e48a11403f8a847d5f2fd282e1559a.nq.gz
│   ├── fe87778b64ee4f00ec8b4dadeb4313c68152e919.nq.gz
│   └── fe8783d08de923bbeab3d4bdb596ddcad47c8977.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ca6133a4e63d22e2c035defa691d241ce22296a9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 66 files
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

[modelcontextprotocol/example-remote-server](https://github.com/modelcontextprotocol/example-remote-server)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
