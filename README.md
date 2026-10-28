# Repolex Knowledge Graph of dask/dask-mpi

RDF knowledge graph data for [dask/dask-mpi](https://github.com/dask/dask-mpi), parsed by [repolex](https://repolex.ai).

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
rlex download dask/dask-mpi
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 66080ec0dd57228922a2ecba00fbb190d8bd53ed
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 66080ec0dd57228922a2ecba00fbb190d8bd53ed
│           └── chunk-001.nq.gz
├── blob
│   ├── 0735684fd97cb23ffc46f64d9060e456f8bdb2b5.nq.gz
│   ├── 08d3ce9684e5729111a7c8c50fbaebca9bcdf257.nq.gz
│   ├── 109b5507888ba681d5872d7c70834ca94ceed0b7.nq.gz
│   ├── 11c9f59d1426daf01f15af6ecefd58169b73dad8.nq.gz
│   ├── 121c85c536fcaa7577885f366bc544cc2297aa75.nq.gz
│   ├── 1acb9bea5f93727b85bfa15963aceb05aeb387b7.nq.gz
│   ├── 30bb8bc17933f7ab7c3f4259d5d60af02b0f0254.nq.gz
│   ├── 359cf1e4f6de9ad33ac0dbd3f3d2770150251e39.nq.gz
│   ├── 3b78d565d3cf15fbefef09345378476bf95eb4da.nq.gz
│   ├── 3fdc4eb232057976a1f7093a899605f463181e3c.nq.gz
│   ├── 40c423381e9effb0089abeb3d8281681731e34a9.nq.gz
│   ├── 430b031f4e7eb180e77f8c2bb2f2317f32e815ec.nq.gz
│   ├── 47df2d25451860d457c1b6a655878b84758f5783.nq.gz
│   ├── 4a2f75401f57636cb4185e819e2ab76d097a1766.nq.gz
│   ├── 543c6b13b473ff3c586d5d97ae418d267ee795c4.nq.gz
│   ├── 556a42e912c9049e81c4fabcd199362f2c2c9a49.nq.gz
│   ├── 56757c464946b2a1a337517f8d37f23d9646420c.nq.gz
│   ├── 5be66975aad1e80c395367f4e093fe1d4043ad1c.nq.gz
│   ├── 603eec48a278570818dd2138e249c8d5526e96fb.nq.gz
│   ├── 64a8ce450818a6648771d71187850dbde84d6ce9.nq.gz
│   ├── 6544015a68c9f98e05c115ef4072e97798058931.nq.gz
│   ├── 69fe55ecfa9aade66e1412aef0ee7d04a9bcde86.nq.gz
│   ├── 7af4e9fafd1c19e3899c94f152304b3a52baa9c3.nq.gz
│   ├── 7b5c47561276a29de49019af4ae51286f5ad043a.nq.gz
│   ├── 7ed6926fd7c8ce96021d64d0d280ae353716d5f5.nq.gz
│   ├── 8167e65e2a0b5c43a47da1a4456f9681f1859286.nq.gz
│   ├── 85150bab9bae216daf280894bce3522f33132ce9.nq.gz
│   ├── 8dae11694e87e241e46721f0b29a7ae84acba7ab.nq.gz
│   ├── 9284c1abf689a4ed8a125d67dcc8faa634a1a119.nq.gz
│   ├── 94dcd776bf674d53326bef20d39ff1cc8fa7fc13.nq.gz
│   ├── 96e3b4d188b41f4a9aec773b1e2c2bdd30baa869.nq.gz
│   ├── 99b74fac7b8c08d1f1c7ac6debba350e75319cdf.nq.gz
│   ├── 9a63e5938742563112296f05f7019ca7dc46326a.nq.gz
│   ├── 9b501be13c6a905624d89630e109e10d27fe8c08.nq.gz
│   ├── a552b814aef930c3344657da1cb2e98329338e21.nq.gz
│   ├── ab4175a59fe6a4d47de60f899e7442bb1fde9585.nq.gz
│   ├── b1a5b9c04a89d7fff5cf678daca7ee649f76b409.nq.gz
│   ├── b828f037bc1985945dbda4d6143f507907a2e27e.nq.gz
│   ├── c390aa21fbbf7db8b2c79e7750f7b5d048497748.nq.gz
│   ├── c527b6495dac30d687cd29321ae94dd760fbbb1c.nq.gz
│   ├── e11bce216a57d082da4323f1699b75596d8558da.nq.gz
│   ├── e2cc32df57eff08b3d7d6fc6be3f740cb40a1a2a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea6a7e7c042bd26c2ac84540ca820540fc9383e4.nq.gz
│   ├── fcc6ef94c7b7fb857c16d4695c12550316a321ec.nq.gz
│   └── fde7bafad4619019a8676a26c2e3a8aa207ad7f5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 66080ec0dd57228922a2ecba00fbb190d8bd53ed.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 54 files
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

[dask/dask-mpi](https://github.com/dask/dask-mpi)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
