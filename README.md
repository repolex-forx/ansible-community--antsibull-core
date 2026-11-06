# Repolex Knowledge Graph of ansible-community/antsibull-core

RDF knowledge graph data for [ansible-community/antsibull-core](https://github.com/ansible-community/antsibull-core), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-community/antsibull-core
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3e98c82aeddc19ed79918617629faa45200a8624
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3e98c82aeddc19ed79918617629faa45200a8624
│           └── chunk-001.nq.gz
├── blob
│   ├── 03fe7ff4e6579bf1d45918a14a176135c160c793.nq.gz
│   ├── 0fc080126a06e1b64f172bfb1a63d302a09e1ffc.nq.gz
│   ├── 10f9a15ea8b4a13e94a51fd59ccbb1803467f7d9.nq.gz
│   ├── 124cf1d72cbd4d18c38be45649daf45ab847f81b.nq.gz
│   ├── 16a66abc478a977ce92da988e3427cbfc1a11ed8.nq.gz
│   ├── 177e7d0e8ca66c8aec6a464454ba6f6a1b8795ef.nq.gz
│   ├── 17e307dae5982de6ab07fb2edbcbcea8875d6507.nq.gz
│   ├── 2071b23b0e08594ea6bc99ac71129ef992abf498.nq.gz
│   ├── 2f0cf2b277469a7ca346a3faae632198023e3904.nq.gz
│   ├── 334905d8b801db0430293b96f2d3a8c199b81653.nq.gz
│   ├── 3569c52401113a5f0b326a57aed8e979565da967.nq.gz
│   ├── 3e53c1e9222240eef5285cd2da86333323981596.nq.gz
│   ├── 477ac0e9a491b47b1d86a55f06e74fb123d52593.nq.gz
│   ├── 48629cd39469aff6418ac08c846cba3cdf6e7897.nq.gz
│   ├── 58d1271d2414cc1101bfb731ddb084da9fc57d11.nq.gz
│   ├── 596e04035ae18f56e4ca33481c0292045d4e0334.nq.gz
│   ├── 5aae1fcdd50eafd824af152f01d670f33e8b9f10.nq.gz
│   ├── 5abc4cacd7f2754b0498b2a199fba68db506921e.nq.gz
│   ├── 5ee7812edbb236187b2434d8d01342f71c10b922.nq.gz
│   ├── 5f9753967cb6c8b1f4bf9623fd47fd34df4e3127.nq.gz
│   ├── 61054a4495f05802fab8d90c1fb96f5ceb8b5be5.nq.gz
│   ├── 62a9501b41cd118b1c83a7f1e42efb6fa881983d.nq.gz
│   ├── 673cc77d0f2a8148b6efe39c6669a6d29406680f.nq.gz
│   ├── 694b8700ba1d3c073e21cb89be4d7e088394d28a.nq.gz
│   ├── 6d8c6929a3eb1e35a11303ce4eca7c2f97822d4b.nq.gz
│   ├── 71bc4fe30d05c61bd73ce69d093954f4e7a31af4.nq.gz
│   ├── 7319c4621d5e04782d67d763716581251c4b55ad.nq.gz
│   ├── 732eca507f02ece375f27bddf37baf4db1de6ee1.nq.gz
│   ├── 7fca5f5ec4c416f226081cd7bd07c1eed435beed.nq.gz
│   ├── 82ed60aedbca48897605629525c4a29d733a4088.nq.gz
│   ├── 87e97fa5a3fb237adf6a457e5c0beaa2bbdf73d9.nq.gz
│   ├── 8afa92cd2bdd458db27cfd6b6d707002adaebccd.nq.gz
│   ├── 91c1918e7f727f022e2b0b095832b7483a0e2068.nq.gz
│   ├── 92db0315f519b5bd308a1986fd40d4ab3be2b871.nq.gz
│   ├── 98e69da7dcff9e190d62125167dc60a6bb0a4191.nq.gz
│   ├── 9bdfb73485cbef993e22b285361731a42e6e9468.nq.gz
│   ├── 9c81dae2149079eb0fd97281ccf1dec21f819947.nq.gz
│   ├── 9d6c246f8e315ba34bcb812210c1cb0210a87994.nq.gz
│   ├── 9e3120ead994a53e158a80465fddb885f1ff8ce3.nq.gz
│   ├── 9f00f1bd4310c02f60482a5078942e19a44f0c92.nq.gz
│   ├── 9f6712a49beb8d0efb0fbd1d3a35b96dd5c2e36c.nq.gz
│   ├── a0e2cef538961d71f0bdbd78b4e090c01115c594.nq.gz
│   ├── aba2d2378b461be6cf25230a41703611e083ebb5.nq.gz
│   ├── af310c2301bd852db8af944027748bb9d0446654.nq.gz
│   ├── b4aaeb15545e86fac367127a5e66146dfa8077f9.nq.gz
│   ├── ba08282d4df0ee08181d0e562807b2f8e01b78ec.nq.gz
│   ├── bfd6c450b3bfb9051acb832b45e0893a904bef48.nq.gz
│   ├── c29a0fcb9056b984fd5fd33207e22b5d2c92f8bf.nq.gz
│   ├── c44771cac1f9e1e156feb36ac7ddf2b785af6eef.nq.gz
│   ├── c45a1a04a847c4b69eff56a828190e78bda9c595.nq.gz
│   ├── cea103f6a7b61a66f191d43ed2d77f8f9d6544eb.nq.gz
│   ├── d7622f58082fb477b69231e54900225d7e8a4070.nq.gz
│   ├── d780567a0bcd00e1043120796cf05ba8bcbf86b0.nq.gz
│   ├── d7dfc378634f775eb7ad040476f1d19901d3f3b8.nq.gz
│   ├── dbb6d9ef19d95fa6378030794a7d1e33b3f4c6ec.nq.gz
│   ├── e2dbf8f25426407bdb283a81dd7e7a79bba2b6b9.nq.gz
│   ├── e34763968c262de5bfa4cf0e0bc33d6edaddc9be.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea5b60640b01f74e295037aa8a6b7d4ea278a739.nq.gz
│   ├── ecd00ceef55660007308298daaecf6764aac421c.nq.gz
│   ├── f079ad06624a975d6cabb72feeef8466b2ebcb87.nq.gz
│   ├── f19058d8c36d966f204a95a341a5301ff7f7be10.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f4490978d47621bf414cb74594a72c13f784b162.nq.gz
│   ├── f71b322d2aabd560774185ebb7c3fec99c47ef3e.nq.gz
│   ├── f9a53e36cc94d809c674dae2223bfe12d941b1b9.nq.gz
│   ├── feb7f46af16d9ebca6264838a442618e9b6c9ec6.nq.gz
│   └── ff432a08c52053cb980a6c60b768fdb7c8bb442d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3e98c82aeddc19ed79918617629faa45200a8624.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 76 files
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

[ansible-community/antsibull-core](https://github.com/ansible-community/antsibull-core)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
