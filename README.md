# Repolex Knowledge Graph of litestar-org/litestar-oracledb

RDF knowledge graph data for [litestar-org/litestar-oracledb](https://github.com/litestar-org/litestar-oracledb), parsed by [repolex](https://repolex.ai).

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
rlex download litestar-org/litestar-oracledb
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8708da9bac815c324c895a676bf0a9e97d79c516
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8708da9bac815c324c895a676bf0a9e97d79c516
│           └── chunk-001.nq.gz
├── blob
│   ├── 010105cf3420a808f9bde1ef95c7882dfb27bed7.nq.gz
│   ├── 0d6fbe4237423c93aa058f8b02a71dc33ac02649.nq.gz
│   ├── 0e7be0638f89a816bc866e07fd9fb693cb9ea702.nq.gz
│   ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
│   ├── 12cf6e121369dbb9df823a32d1ff76f9503b42f0.nq.gz
│   ├── 1a51b8351f03627a4936d8d8701be29335106537.nq.gz
│   ├── 22f80e3184642f9013e0c4486e3e155fae30997c.nq.gz
│   ├── 2437ec43fc54b0ae741f8f487dd6251e21f62d27.nq.gz
│   ├── 29a2d1e2c6833ff6dc0a38ebaa45e28a1c718997.nq.gz
│   ├── 38cf51ef1b37a839534bace1757825e80212ecff.nq.gz
│   ├── 3c44f69761753e23e3f95c46cf6f4495f9e1447d.nq.gz
│   ├── 411bc9da4f893193fc16b7a54782d720fe7f7e63.nq.gz
│   ├── 4154704f7b0261b27f23172c8fb610208d35cb56.nq.gz
│   ├── 442f7583ef07b7d3f20006445ba3a6f8122373e9.nq.gz
│   ├── 4b6b7c181972d463e85ba10b2cd1d6ab949fdf97.nq.gz
│   ├── 5153070a2671210abdff3173e733363dd5aa4e8a.nq.gz
│   ├── 586cbc25096495940eec5638c455fc438039b4ee.nq.gz
│   ├── 5c3ae8734480c06df67b3f96cf15529f6c88aa27.nq.gz
│   ├── 6c944d9ac8802b786d1440345a42052e998ac98d.nq.gz
│   ├── 6e669401d089458da957a8f9015f455bacdf5f8d.nq.gz
│   ├── 7bc7f50c6a7789e9e8a6aa95b131582662aef5bb.nq.gz
│   ├── 8a9c8fec0ec0139d6d3e97a2ace224ce2ea83733.nq.gz
│   ├── 9201ef4c614eadac037863fc018f6fb3c7b802e6.nq.gz
│   ├── 994f85c941cde1877fccdf230f425f6ae2b91ce8.nq.gz
│   ├── 9bc63e071ca292d57add0cae79a210b1c4412001.nq.gz
│   ├── 9e5d6c16f69b10a3346b58dba5cb83c7dbb395b6.nq.gz
│   ├── a0eac83b7583be85f6036e6faf2071de419e4eb0.nq.gz
│   ├── afad7979037f58fa92f77c3febf6524e3f3e7d2f.nq.gz
│   ├── b1ddcee9dfb6f96360d562c7d828f3da51aee3a8.nq.gz
│   ├── b4491ff3676ad4ddab44598029f3dfdec778ffb6.nq.gz
│   ├── bbd440e7a11cd492aeadbc4fe999f354366866df.nq.gz
│   ├── bda8b992b641d0e55107d17df08516bf39683366.nq.gz
│   ├── c9188e9997a742103a1259f0bdbd7d18a1138f64.nq.gz
│   ├── cad8e843b9e44fbdc3b47b923557e3559c191f1a.nq.gz
│   ├── cfe59fd76291dc412b945823da15b8d55963a107.nq.gz
│   ├── d3130034510fa870ed1c7b0a7fd5ff01d361a874.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── e641790670ce638cb4ec224b8351f96c468eebaf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ef1921377e37dd8397e89bced757f91fd0a63fc7.nq.gz
│   ├── ef9a798206e1893ff88645ba3d09f3a04450f7b9.nq.gz
│   ├── f4f5d1c291462ec21a7cfa9f69229d575390af94.nq.gz
│   ├── f6a5ca609bccd554496273b5056fa3c246b2a535.nq.gz
│   ├── f9532907dcdec92a9de3f577ca01878ba8ce1674.nq.gz
│   └── fb68f58cfc05508852cb0870bf928bb6468889c5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8708da9bac815c324c895a676bf0a9e97d79c516.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 52 files
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

[litestar-org/litestar-oracledb](https://github.com/litestar-org/litestar-oracledb)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
