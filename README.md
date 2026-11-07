# Repolex Knowledge Graph of networkx/nx-guides

RDF knowledge graph data for [networkx/nx-guides](https://github.com/networkx/nx-guides), parsed by [repolex](https://repolex.ai).

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
rlex download networkx/nx-guides
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c76026a27209e931062fe97a989504d85c14ac19
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c76026a27209e931062fe97a989504d85c14ac19
│           └── chunk-001.nq.gz
├── blob
│   ├── 001b1e6e9b5b8c7d98e2f4c2ed574184b1ec08df.nq.gz
│   ├── 0929f915fa0b1db8f8b4eb507c51d3e772c25856.nq.gz
│   ├── 0a86f8445d82cf39636f9f52908495f84c93d045.nq.gz
│   ├── 0ae9fc2a1b8b2362d63f2e2c29489e683577446e.nq.gz
│   ├── 14b26dafec0eb0b6467bc6de9ec13cc174b45ea0.nq.gz
│   ├── 1c415ecdccf8650eac84ebb3d1f7173d51ecb098.nq.gz
│   ├── 1d4e60fac178cc4130da620509f37a1244c23701.nq.gz
│   ├── 206a253857aab2e48e6c02692c9fccd3c165c359.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 2bb08ce6d21c364e205bfa9364b485773ab321f8.nq.gz
│   ├── 2ccddf160554489093ee859073cb60be1be3df5c.nq.gz
│   ├── 2d15431fa0b2a4c655b1505332ae38116e88e009.nq.gz
│   ├── 2e96d73edb16d1e6f192b25564a50fb0271774e7.nq.gz
│   ├── 302368a6f8cf3f1c77d4339ee3c848f51896e9b9.nq.gz
│   ├── 30519ba252d32e91b7da1d1835a7e72fbc8706f5.nq.gz
│   ├── 37d4f118e880a72b1a9f3c87f1f132e92b7529f4.nq.gz
│   ├── 4acc6630531181857b30950d5c2c3c9bb07ccf28.nq.gz
│   ├── 56934c9149b789e7e0c1841c46939685fc1a364d.nq.gz
│   ├── 59befdc111512cf19fdb3cf04b8da8baad8c1f22.nq.gz
│   ├── 5d5ecb94fab3047a0126ffc8cd608f7c86d5f704.nq.gz
│   ├── 6575285162a89bbffdb83a6262fb3652ae1b8a2f.nq.gz
│   ├── 789cf58d00b39829d7426f02f85c69039ff27979.nq.gz
│   ├── 79ea95d3d17ab4cc686ef114a66bc5906e80113c.nq.gz
│   ├── 7db4037531b69fdce54383397d4d55c63b5d84dd.nq.gz
│   ├── 7e46668e27441c54e6e8ee9fed45a49d8dfe98cf.nq.gz
│   ├── 7e74c4d6a6109413c0967ece5a6e84ee7400d383.nq.gz
│   ├── 7f8492d02ce3a84e4b373317f81deb7b30b90973.nq.gz
│   ├── 815103a85545af8af527cca50d2dda45cbff14c5.nq.gz
│   ├── 852b3fb4af2d790296d3c51ce1e7e1cb8ab34b41.nq.gz
│   ├── 86b5a30f96ef36b8b98225e08cc7f420ac681458.nq.gz
│   ├── aa20bf8b902e4e7ea5f0deb75dea1f3b13bd7533.nq.gz
│   ├── aaca0e394a1e8d0e77293582b1ce893bd95d31a4.nq.gz
│   ├── b7444af366d1c8372404598a1166a53203745d31.nq.gz
│   ├── b86db498b4428446882668d30ff10b9ce6361044.nq.gz
│   ├── b9e871fa3724dea38a8e4ad7ed560140ab1ea03e.nq.gz
│   ├── bddc3a078bc51a74174e62c0a986620067b32e6b.nq.gz
│   ├── c4839d6624423f24be8bcd5ab2e3ddcfd24aa116.nq.gz
│   ├── c8e1b7eedfb84d074f5f96811ecdd18725758c07.nq.gz
│   ├── d2aca3a7e10145bee54ec8c0c5c0fe0b38673664.nq.gz
│   ├── d38d4fef07fa3999240fa3d64c3b811a735302d6.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d55ceff8ca4930ed0232b453d495c0fb2b856253.nq.gz
│   ├── dcadfa139ef97d44448bada1cb7aa90444c1b575.nq.gz
│   ├── e426955ebeaf3bb4c077e9d8fb1e02b8ad33e9f8.nq.gz
│   ├── e8281020ffdc1ade602377a0c2b5895f0dbe00de.nq.gz
│   ├── eb29d1d34117ce76e780b297d4a3504ec08b6a4a.nq.gz
│   ├── eb8a1e40a5a9c4af5aac8e5151c2ea17c0113f0a.nq.gz
│   ├── ec53e6070f1b9dd1f8f11828e009fc91539c1daf.nq.gz
│   ├── efcdaa6e77b707419a5de6701127b44f6ef85fc5.nq.gz
│   ├── f844c1d370ba48dd002cc82cb7bf58e570c7d588.nq.gz
│   ├── fa814cf7252ca71fd243140008e8e6608670481b.nq.gz
│   └── ff559c29141d74bfe010f4cdc11e8e29a2941318.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c76026a27209e931062fe97a989504d85c14ac19.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 60 files
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

[networkx/nx-guides](https://github.com/networkx/nx-guides)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
