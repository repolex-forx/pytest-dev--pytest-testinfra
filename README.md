# Repolex Knowledge Graph of pytest-dev/pytest-testinfra

RDF knowledge graph data for [pytest-dev/pytest-testinfra](https://github.com/pytest-dev/pytest-testinfra), parsed by [repolex](https://repolex.ai).

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
rlex download pytest-dev/pytest-testinfra
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 04cccc3969ab786e88e2d67462c409c8778005e8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 04cccc3969ab786e88e2d67462c409c8778005e8
│           └── chunk-001.nq.gz
├── blob
│   ├── 05d87813e2356ab6b2f0f3439cfd97614858b3cc.nq.gz
│   ├── 09929fe4369c3fb7055194ada0edabde29216d80.nq.gz
│   ├── 09bb87883273036f4faec3005ed1dcc6b545a1bd.nq.gz
│   ├── 0af7a84fbeebf22c69931efa6b90480e337286bb.nq.gz
│   ├── 0db1e290fd50bf37c3fd04e32784bcb18e915315.nq.gz
│   ├── 0f48bc133741bf69b58a6dae5f205ca1d1e1511d.nq.gz
│   ├── 10d5c12021cd15330e9c3f1f03ab0b7c6afa3eba.nq.gz
│   ├── 113201916661712ea7c2ae425940775a44f7723c.nq.gz
│   ├── 11fa6141ce4d3221741c9aa108d1ab6c67f258d3.nq.gz
│   ├── 12afcf89466c400795bcec0873deb1608fbff38a.nq.gz
│   ├── 20bb601fc7ee6fa9d2a12da11b8934e66d9cbdb7.nq.gz
│   ├── 212ed230151f624bb6350b2f5cfc008b1b84a9f0.nq.gz
│   ├── 24e666cb15fcc4406b1b23ca13de030f3e509dbc.nq.gz
│   ├── 25a3530fe92a4418d708cabdad110022235fd3ed.nq.gz
│   ├── 2a5b001ff1bf1888084cada1b247c1be9e3b0e5a.nq.gz
│   ├── 2ca2798c6ffe3e9a4047441a31dc90d58be07eba.nq.gz
│   ├── 2d33daae5d53a4ed940c1d74a80fd0b09a5fc53b.nq.gz
│   ├── 33f18878754f5d5840b5378978a711c4affebf15.nq.gz
│   ├── 3417824380b70cf99a0b40bcd0faad1873c6f159.nq.gz
│   ├── 3814ffbb0dc2c16e3c5a3f5c37ad9eb7d1f9d2aa.nq.gz
│   ├── 43feec6d62612021489549f6ac484a5a71f69590.nq.gz
│   ├── 45be64ff0148abef1c899d6392b70fd59a47c54e.nq.gz
│   ├── 48d46b844c5d4b37b56818e7b9e2fb5b234219a2.nq.gz
│   ├── 49a1727dd73336e5005424a2b9889aa5d825cf05.nq.gz
│   ├── 4b2d8d2b51be547eb6aef11b18181c887dc1b38f.nq.gz
│   ├── 4d11d429e7fde9d42a6b7d5e47d3a7df63027b0a.nq.gz
│   ├── 51275176b911bda04af7ad3f88734b2a12f02aa2.nq.gz
│   ├── 5248ae87306ad3c0e9379d12f29a7d248a13d9b4.nq.gz
│   ├── 5ba17a12c0f0bdf46d8b2be0e9711f0a18bf78e0.nq.gz
│   ├── 5c683c505f6afc604bb3c000fb43656d708b10b3.nq.gz
│   ├── 5d8bf3a181f8646ef8572bcfa0ffd461bc6dceaf.nq.gz
│   ├── 5f0b5460ab541fcb4d9998b960cb043dd99b8308.nq.gz
│   ├── 649c03b4f6ce2ee3315816682a8a460ffd7b6d77.nq.gz
│   ├── 67db8588217f266eb561f75fae738656325deac9.nq.gz
│   ├── 684a53b525d792533cffe0e627551d6e5dfe4caa.nq.gz
│   ├── 6be6c5d0d55f65464136ba96651b093beccca294.nq.gz
│   ├── 70b17179157d55dda9fe9063ef90c805f132cfcf.nq.gz
│   ├── 7281eefa0a6611cfedc974136b2845acc2abc4a0.nq.gz
│   ├── 7a32b1d898831ab03ee9d7b5614873e1cac584f7.nq.gz
│   ├── 7c5809e3dbd478aaa081d9177681b9873c76528c.nq.gz
│   ├── 7f461bc29d85aa921bad8db2030dbfdad7adbc5f.nq.gz
│   ├── 847127a5d0122644c31abf4cd0327a086256bde3.nq.gz
│   ├── 86565a47d56a4179995d4ec8b6600b4378661448.nq.gz
│   ├── 8c37d089c9da2b30c3130033ae74a9bfe1fc11bf.nq.gz
│   ├── 8f6dcd467c77844b535ca6e95b34172421fab03f.nq.gz
│   ├── 8fa0ef97cb767ad611c825c93ceb1b573671eda6.nq.gz
│   ├── 8fb68a31cfc353a78ec75734bf56792144b316ff.nq.gz
│   ├── 94df79cbdc83aa34531ba25d9eabdc4aa3050376.nq.gz
│   ├── 9702d6a4202dc32cf4c87bbaaa4c340d54aa233b.nq.gz
│   ├── 996af406ac83efa3230a138a076996d527d89a33.nq.gz
│   ├── 9bf9e7c85adf6811a52468819796794532ea07e0.nq.gz
│   ├── a2f76f5c0dc5d1ed742bce7a51c28525ebeb31f0.nq.gz
│   ├── a40885307a8a8002494837f796b0dedf9c68af3a.nq.gz
│   ├── a4392e3251bc07ca25afc82495fe7e6f1c44bfed.nq.gz
│   ├── a488c1e9391130977c5a45eb238e832e7e5f51af.nq.gz
│   ├── a70dec038b3c80f6b5cc1ed1df488a596dcec308.nq.gz
│   ├── a74f2a79e64a018a98945f9673dae42e7f416e50.nq.gz
│   ├── a78449648db69686c35817d9a6a717fc09b69a6b.nq.gz
│   ├── ac1c4cdbbb8ff066dbe11ac7d69418cb184d62d6.nq.gz
│   ├── b106d468262203c673d2882db2ea56e06f88d5e8.nq.gz
│   ├── b54f10fd85bf472d8f9d4c8b6dfc3fe0bd3e5c82.nq.gz
│   ├── b6e3378b9d38245dc71c72a6333ed137368f8444.nq.gz
│   ├── bb4ba1c1ac24364ebcc4c4ab123ea044bb57aa73.nq.gz
│   ├── cbd57f9d8bee80967aa08da786aa68508df8b32b.nq.gz
│   ├── cbfb2e6ec824834ae00676d6390840fcdcc19174.nq.gz
│   ├── d1fc5aa4dc18b0b19c3c53ab2504b93a68080b06.nq.gz
│   ├── d3066a2dc4ca1d5a67abced6ff2fc4d4a8031637.nq.gz
│   ├── d6b4d5f82a885f0b73e4316de11a1ea2268afc35.nq.gz
│   ├── de9213a42426e16d6f2e4eb29a7b2e6f8406e954.nq.gz
│   ├── df4ad796a956e552bd62047c39466a261cc7fb0b.nq.gz
│   ├── e09583d42008dfef03c430a98998b8888e6e54d3.nq.gz
│   ├── e494947dbace5804d934ae51144da39982e04c30.nq.gz
│   ├── e5d2fc12dea6ecd1c50c60584796d17e50fdd572.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7ae5d4a67b07a33e9d2c82ee4ffbe776d56608e.nq.gz
│   ├── eb7b1421738c5a325b6f9fb7e5ae83314ed32ad2.nq.gz
│   ├── ece7fcb4888909e79921f16b9c8bf6f999edd16b.nq.gz
│   ├── ee373d6c2faa10385fae5dc4c0bb71db8b10d829.nq.gz
│   ├── f0aac37d4fffde5a6efe8d404e2097fc712d8e54.nq.gz
│   ├── f39f4274d9db2e0b7b45777b745c05a611065556.nq.gz
│   ├── f80f38fc18ddb1a8f0381c5be92dadfd6da76f8a.nq.gz
│   ├── fa3ed2de3295080ad7ee5ff420d0d67137f49cae.nq.gz
│   ├── faa3592d8c3d4e66fc45f793ecd7ea1bcc025f99.nq.gz
│   └── fdc1be7ee79875de582241d5c438632194278e6b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 04cccc3969ab786e88e2d67462c409c8778005e8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 92 files
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

[pytest-dev/pytest-testinfra](https://github.com/pytest-dev/pytest-testinfra)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
