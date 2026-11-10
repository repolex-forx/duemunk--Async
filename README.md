# Repolex Knowledge Graph of duemunk/Async

RDF knowledge graph data for [duemunk/Async](https://github.com/duemunk/Async), parsed by [repolex](https://repolex.ai).

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
rlex download duemunk/Async
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0004dec3c32d4273df79d0e84d6590945cbbb656
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0004dec3c32d4273df79d0e84d6590945cbbb656
│           └── chunk-001.nq.gz
├── blob
│   ├── 05626af52a3a617d4c9e5947dc2c37ae67f511e3.nq.gz
│   ├── 082f8af22c891d4d48d2b3e9731b14814acf6737.nq.gz
│   ├── 0a5197e0234863b3c12b9ce26eb442f81346b505.nq.gz
│   ├── 0d82202a286f63bdcdb504937ccb50debd03dce2.nq.gz
│   ├── 0f17fcde8a76fca16c4f84d46fb26641c2cf3283.nq.gz
│   ├── 125694a8d73316248b935ffe6defbc670c0ce22c.nq.gz
│   ├── 13e4bf772b6e86ac99dfc8046f202f01c8de43de.nq.gz
│   ├── 148a0dde03faa1d5c8db31a9741d35791c8fc9ec.nq.gz
│   ├── 1848b2f846e720412ec088abd3f24237eedcc9f2.nq.gz
│   ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
│   ├── 1ecb10d91328fa50a0c1a52ad1a864447567bf9c.nq.gz
│   ├── 21195e3c681fac23759e3a79eec3d82a21094de1.nq.gz
│   ├── 2243fe6e27dc60546f37eca17f97ed75802d224f.nq.gz
│   ├── 25f64f47efb94e0be9e14a0f89901e7b8a988570.nq.gz
│   ├── 269d83d3337b1db4efe5bcc2fb41c0852506a1d2.nq.gz
│   ├── 2773c32178ad9240f0064ccd24f0a3c8782ddf4b.nq.gz
│   ├── 28223d12c9aecdd47974646d6531f6ed782d27c5.nq.gz
│   ├── 2b3f1c1ad2ac813ac841a54d8b393b363d72e82b.nq.gz
│   ├── 2c3b0ba43eec192ef82871bf70d3cf3df9f6bb98.nq.gz
│   ├── 2c71a63e67e9a2f1946567d1a96f8540e1c190a4.nq.gz
│   ├── 345301f2c5cae62d2d814ffa977dbc2ba74cc092.nq.gz
│   ├── 38f3d8420f79eb79a3ce1bb828506724db5375a5.nq.gz
│   ├── 39c3e3d9a6894e10430be6b0ecec251ec98aa82b.nq.gz
│   ├── 45367acc35c7113e0b4797c244bf621ad73abe18.nq.gz
│   ├── 49c597f41252feea54c3b11cc10a739f6f7c75d9.nq.gz
│   ├── 4a026aa2ce08fd4ae97f6aedf7fb9e969f2f0b5b.nq.gz
│   ├── 4d6ffebeeca2ad73dceba438e380e42e559ad672.nq.gz
│   ├── 4f338601b8a403a088351880c74fea0b9988bcfe.nq.gz
│   ├── 523589f3e638fac7caac977b7ff0cb526976537b.nq.gz
│   ├── 57ada9f9d59f688e51c347028163d0b0c1522abf.nq.gz
│   ├── 5eb1188bf3e038884299e04d67b7f7a8ad120d86.nq.gz
│   ├── 5f577acab6ea6bf1f4a33b6e4e80a1acc0d7ac08.nq.gz
│   ├── 604d0cd1dece6907a89b702f2b4a6b639286a7e5.nq.gz
│   ├── 686b2b73c554e1d70474964bc22220bd9129b2cd.nq.gz
│   ├── 69f1e2b6e2151a64e77d33f6bcdc993c3b1aa712.nq.gz
│   ├── 6c6c23c43adc88621ce3abfbd1585c8792bd165c.nq.gz
│   ├── 6eceb7fb8e8c334149de23845026e98bcdfb3b1a.nq.gz
│   ├── 755a34202281219f8a1eb285460c4a23665888aa.nq.gz
│   ├── 76f7dcdfa326af57e44015b97d0e9d4e1c7e88ff.nq.gz
│   ├── 7a623998616371bf62f55224811bfb9cbb7acc27.nq.gz
│   ├── 7ac9ee313eeb49745a3492c469ab34ba66030561.nq.gz
│   ├── 7c23420d026058e6193fbf4dbcd4b8ce56d50440.nq.gz
│   ├── 804d5bfb7e31d6e6e227ee697642c83c20ee8224.nq.gz
│   ├── 81ca8c6de99beb551542084a037d872e704ee03c.nq.gz
│   ├── 82a0958db202db8153b727209b55cec4a0e9fc8b.nq.gz
│   ├── 84ba6676f315cecf284f8f35443f40e193e4c278.nq.gz
│   ├── 8edaa25fe3e773ed04bb33e5da9222d8d58a1816.nq.gz
│   ├── 8f952c4dbdb074fdc96446664491b3774c26792a.nq.gz
│   ├── 90af628578b2b41eb55140b086c644136b716dc5.nq.gz
│   ├── 919434a6254f0e9651f402737811be6634a03e9c.nq.gz
│   ├── 951f17e7f0205781a02f465464d2b6e2418e7244.nq.gz
│   ├── 9658026797b0880577d0893ad19253ad7e07f07a.nq.gz
│   ├── 990a9b5d19445b243e49383053805d2aa0d0088e.nq.gz
│   ├── 9a2297a5419c0750f8e3b78dcab56950e526a6bf.nq.gz
│   ├── a0e14cf78c8970304ba28b7012e9d1e545c6eda7.nq.gz
│   ├── a0f8f439cedb1e5080d019807a4ea1e27de6f2d1.nq.gz
│   ├── a7f8d7bb768383eb31d260abb53600e68918f8f4.nq.gz
│   ├── abcb467c858ccaf10fa7c5420f75fb5bb6971643.nq.gz
│   ├── ac279f86ababf3ee12649631955b533effe4ff68.nq.gz
│   ├── af40bba18d2c2a8bd62b9f444378100481492ce3.nq.gz
│   ├── b26537ef407b349d3ed0b3516e8541bc4a1649f3.nq.gz
│   ├── b2f20573e2e896831b7acb1d13cb37d5a63dfe16.nq.gz
│   ├── b39673b4bea191af82c7129530035e95cd87e2d1.nq.gz
│   ├── beb2a2441835aeaf9ee2ba30c557a8f2b6e4363f.nq.gz
│   ├── ca7f76ed5394b26107467b2003157dc7e7f0755a.nq.gz
│   ├── cc5daf73e390d69514f0be5453a59cf7dbcfdd70.nq.gz
│   ├── d06a3749b7885a6f43c2d6b766b56796e2bbe4bc.nq.gz
│   ├── d433ed075fa3782ab80e7246943c68e4e39390de.nq.gz
│   ├── d4fb151a7a884fa3e0527476f348349bb48b186c.nq.gz
│   ├── d54abad0af81d97fda689c5579ca1a7499d3f222.nq.gz
│   ├── d70d5a9cb48810d5624bb1ed7df0dde1576448f7.nq.gz
│   ├── e1565cadeae259b4c7ea9a1fd18df2a4834852b4.nq.gz
│   ├── ee731568bcdb48555abe519db49c9756014d2a6e.nq.gz
│   ├── f381b0c41cde0f69e64cb56e009f8bbedc2aac94.nq.gz
│   ├── f767a49c0629ce0138d50c3ccb8cbd47d6cd050a.nq.gz
│   ├── f900279d841cdf8632c39a6fab79b3ba8c4eab7d.nq.gz
│   ├── fc100d87a21627324c401eb783908573b9433d2e.nq.gz
│   ├── fce114001ce9b4cf3b26aac1c60348d13fecfa4f.nq.gz
│   ├── fdf4f16a2b908c305809396b6fad8cf75733d621.nq.gz
│   └── fe3e1fa5e26a7689e8682c3bf45f4fb7aecd3fc2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0004dec3c32d4273df79d0e84d6590945cbbb656.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 88 files
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

[duemunk/Async](https://github.com/duemunk/Async)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
