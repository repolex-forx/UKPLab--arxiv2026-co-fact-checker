# Repolex Knowledge Graph of UKPLab/arxiv2026-co-fact-checker

RDF knowledge graph data for [UKPLab/arxiv2026-co-fact-checker](https://github.com/UKPLab/arxiv2026-co-fact-checker), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/arxiv2026-co-fact-checker
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 00a2dda07d0dd56d5bdd055e046dd74bcb159620
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 00a2dda07d0dd56d5bdd055e046dd74bcb159620
│           └── chunk-001.nq.gz
├── blob
│   ├── 00560c9a5b74be0fdde98450ee9ada66dd5860ac.nq.gz
│   ├── 013ee3629ab5788940b0610c0eec2c692ee2dd2c.nq.gz
│   ├── 063426cd44eae4bc48d89b3e1cba396a6408fb12.nq.gz
│   ├── 0c11100612f6cad90bd4db1974a8be690206f786.nq.gz
│   ├── 0d03bf268c448d14aeb9becbc045bcde4ae6c9b7.nq.gz
│   ├── 0d39a67c24f01c1af1e9cb675f380c3a1d1b2422.nq.gz
│   ├── 0d9360dc35d158ea1ccd025d9520994762579eec.nq.gz
│   ├── 120c6893b8af8f69dddc51b2734ed561b78c6091.nq.gz
│   ├── 14411fd93d699377c6e17280cabaf9a39d67dbdc.nq.gz
│   ├── 229edba242bb190698662cdce6bdacde9f0769fe.nq.gz
│   ├── 23b0c70b3600d408c64442b6e01cbea68f77e59f.nq.gz
│   ├── 2636b1bb624a39f0b93fd5aa0444a7412f0c9763.nq.gz
│   ├── 2c0a27ead02e888f6b0c55adfcf7604b46c09e1e.nq.gz
│   ├── 39ab5ada450edc8d0d535739b906b09c2e137727.nq.gz
│   ├── 3dc429a6613bf85898a47643fe31d4439fe9d973.nq.gz
│   ├── 3f24746874176fa3bb23a4545121c46fa219d601.nq.gz
│   ├── 488589572887b06b32a4275ff58b878c9ccebcf8.nq.gz
│   ├── 4cef27e61ea9ac6f982e68a89dcb12432298bb71.nq.gz
│   ├── 5dcef726f671e400c7a0873dc8e9d9f061889630.nq.gz
│   ├── 62ebc68ea25824756d7ac2647cb109bdcc3b51a8.nq.gz
│   ├── 68eb69b23434984ce6053d307b6b6b7f709a7e7e.nq.gz
│   ├── 698e9f972a96948e15606d89ceda254e571d2692.nq.gz
│   ├── 6bdf65cbce530390872a406f22d346334a40b3a7.nq.gz
│   ├── 7102f571cb7ad7b59815b0e94aac0cc56dfd78ed.nq.gz
│   ├── 80f9dedb22582266a9daa4b5a74a2b7ef60f99a4.nq.gz
│   ├── 82abe83a624d1c31d40c0111634f4b33afa8e059.nq.gz
│   ├── 8871abfdc9c3745a372d1b55952f4d24481e3ea0.nq.gz
│   ├── 89f79d04b69ed907c42ae436aa16e9cfa7cfd9bf.nq.gz
│   ├── 8a32ee34b1603953ed79a91dec01453f67fb93c4.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8b14d41f730e3642c5986d15e956bb8af5134367.nq.gz
│   ├── 9b3703a912d40f58fb0fb57d20742e53d9fe7671.nq.gz
│   ├── 9ccc7363dcc9155dec920e64a9820737d3fff0e3.nq.gz
│   ├── a70d291241eea483a3e2ca58d7c779b17cc164b8.nq.gz
│   ├── b83bfc8df96506f27e5723ba5b66e6151a688d25.nq.gz
│   ├── c08a79032592be8f5e7318991b0242323389469d.nq.gz
│   ├── c6718de5c5ae59d2c22141a147f5afba41af9cbb.nq.gz
│   ├── c7a351776c6d721e4c4b745d42d4091fc5346cc1.nq.gz
│   ├── cc98b6933cd0df2705fd39225f24282258cd3685.nq.gz
│   ├── d62fc66df4b9acdd5381753fde4173a5775b1ddf.nq.gz
│   ├── ec87d8c46aa2275ef943853293164ab44b8d7d10.nq.gz
│   ├── ed3a9d377ba3c30e6eb8b2a35e08e8dc814a0725.nq.gz
│   ├── f47c06cc18baa434989aa2d46756a0b678957242.nq.gz
│   └── fc6c1358535eedddb23b1a33fd4221f3fd17113d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 00a2dda07d0dd56d5bdd055e046dd74bcb159620.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 51 files
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

[UKPLab/arxiv2026-co-fact-checker](https://github.com/UKPLab/arxiv2026-co-fact-checker)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
