# Repolex Knowledge Graph of gabriel-vasile/mimetype

RDF knowledge graph data for [gabriel-vasile/mimetype](https://github.com/gabriel-vasile/mimetype), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download gabriel-vasile/mimetype
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8822588d35ff221d0a72627f27a94ba58f661d89
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8822588d35ff221d0a72627f27a94ba58f661d89.nq.gz
│   └── repolex
│       └── 8822588d35ff221d0a72627f27a94ba58f661d89
│           └── chunk-001.nq.gz
├── blob
│   ├── 020b5ee75bdc825cb64ce875b11d761db104a970.nq.gz
│   ├── 0b4c62f1c0cd063bb842b967a6c213331b9484c4.nq.gz
│   ├── 0c0df491324365c6ae963c033f209692fede8a77.nq.gz
│   ├── 0cc26ec01c684677c30715da9e64a75cc7cfc734.nq.gz
│   ├── 13b61daa5946b44e85a4a7c4f625df080d1ca18c.nq.gz
│   ├── 174048662d538cdecbca4cafd1b620052205d792.nq.gz
│   ├── 1d63fa3dda9171164d0f4d18945cdbe977ff231c.nq.gz
│   ├── 21134aba4b45415e2568c0a701104db429d59dec.nq.gz
│   ├── 23e30da2b9778160a9be79a670c221d9318194f2.nq.gz
│   ├── 2ba906c0befd96ff393e6c051cf91934ea95d69e.nq.gz
│   ├── 2c3d6d696427fbe13d15ce1388fa2b90d4831235.nq.gz
│   ├── 2d9e1a6baadf8a0af720178ce1c6436daba4b0ab.nq.gz
│   ├── 30c41ac04c0789fd2441ea1776e7c89bec02aef2.nq.gz
│   ├── 3373274ad9d7cab3d8218ccf4d85492c0d68aaea.nq.gz
│   ├── 35c3f911eaa7b3ac16c751956b23b04188f86f92.nq.gz
│   ├── 37ad6a9fb1488b0de939f9481ddcee4de7087cc1.nq.gz
│   ├── 3892826a7490edde95ed3b08bc9ae2f79b49b9a9.nq.gz
│   ├── 3979ed1f935858ed886fc784d2c574f4adf1f10f.nq.gz
│   ├── 3a86858684a46100f6c75c5e2fcc3a01083f80d2.nq.gz
│   ├── 3fa6711813c82cb29c4c76b6c66ca7c426e90b0c.nq.gz
│   ├── 4261a1d5225f7c08a2da5f1422ebaeab9ab227fe.nq.gz
│   ├── 4baa25767fc4e7a5af96c5497a50f18dbab9f0e9.nq.gz
│   ├── 50267e689bc01fc226b2a7c5edb1d473e3b9f6bd.nq.gz
│   ├── 503f0bea4ba592abcf14fb70c09b2bf246dce73a.nq.gz
│   ├── 53aed13bdf04d8a0ee2fd598c328eae1846dff22.nq.gz
│   ├── 55023baef6d6c3d543a7167d5ac13669846e715a.nq.gz
│   ├── 552b4ead90883e6f565e6f998cf3dcda478c153d.nq.gz
│   ├── 570889b7b1559d563ee73de7c264fcabe7546dab.nq.gz
│   ├── 5869cb8e2300a1fbc0c08394870e10fbbfd54ca2.nq.gz
│   ├── 5b30cd614d82c03edb1309eb2788b511ed573bcf.nq.gz
│   ├── 6103c12d364f984e4de1166051717a642a637f56.nq.gz
│   ├── 63bedf7436152a33920834288894fe5900363296.nq.gz
│   ├── 64dbf99adde74ce0d3c8ed14fa1331aa9d1c15b7.nq.gz
│   ├── 6fb62a72f2d03447c7231b31106ac6e2bb73574d.nq.gz
│   ├── 6fcbc4dc6df756e318c44f8db283e44c67034778.nq.gz
│   ├── 71c511585020f658e79ab71b709dadcb30ae8bae.nq.gz
│   ├── 7280cfa1454b64b7de857ce51cdf7b64c53d6a77.nq.gz
│   ├── 78770016f8c62e3afe699992b23683f2b180e55f.nq.gz
│   ├── 7918cf3889b003c76d9867002d984bcbf51f8b09.nq.gz
│   ├── 792741732b7cb564d6905606bda0429f858fcef9.nq.gz
│   ├── 79a3617fcf185a4266d077e230f46e2d3e5c7826.nq.gz
│   ├── 7d0b9c03b2b6b901febfaaf9805b7b25cc33e9d3.nq.gz
│   ├── 7d2dae6d006b0589a816f178db902a69ed941798.nq.gz
│   ├── 7f6e5e8bce83bbc8167a593584ec0a986df0dd1b.nq.gz
│   ├── 87ff697b9fcf31e1e1d0d3b6d8ec9502e4910670.nq.gz
│   ├── 9842fdc8b6b063acf567cee99ff75c017765f3ed.nq.gz
│   ├── 9f5f7d6b1acc87f85e9543ac4784fd49b9f28f92.nq.gz
│   ├── 9fe71ac9455aafe772d365238cdab90f29bbd0e6.nq.gz
│   ├── a11221687a738d44a3c3869986760bbdb539586c.nq.gz
│   ├── a11b6bf339a65406b74b1797c9eca1a067a290de.nq.gz
│   ├── a1d8ceb756b9c7ff4e7d98491fc503b0e46ffaa7.nq.gz
│   ├── a285001709d6abd4b29bbe4274dbdf82aa4c4e17.nq.gz
│   ├── aeb4321f9dc1667e3c6fa183ee43d71ec8ffadcf.nq.gz
│   ├── b9abc6dab1914def473acb4e16fc7b8bb9e56c95.nq.gz
│   ├── bb4cd781b6ecae70ce0ea3572675c2c6e1659fcd.nq.gz
│   ├── c3e80876738f11cdbdb4d4328df05fe72bf48a23.nq.gz
│   ├── cade91f18c26edd573a02620284b3d24873ba8bd.nq.gz
│   ├── cd9c7b697a8dd1c360a6c968eb16c7f9933adb88.nq.gz
│   ├── d60cd4e127efa075e015f5a0dfb2f1283f563e96.nq.gz
│   ├── d8d8298766f4020703624cb14fb26776e309b070.nq.gz
│   ├── e0aaf516234707d5a1d517e7e25d29e04d2e51ca.nq.gz
│   ├── e1dda7cf0649b29ed5992af00a22de1014462618.nq.gz
│   ├── e2c483143a94bb8a89f11a5675cd70911cae5aa1.nq.gz
│   ├── e689e92a362ed25a4d72cb7634db7b9b5f075f99.nq.gz
│   ├── f3bfa2ac37a887eb570799d56710563ea9d14cce.nq.gz
│   ├── f7bb230688ab3f5ae738c7805ed29205d79ee563.nq.gz
│   ├── fc642ef433c3bb4cf5ed9015be793debe008baea.nq.gz
│   └── fe5f613e5da73b7b4933e679effd04562cd1f41d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8822588d35ff221d0a72627f27a94ba58f661d89.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 77 files
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

## Source repository

[gabriel-vasile/mimetype](https://github.com/gabriel-vasile/mimetype)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
