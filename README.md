# Repolex Knowledge Graph of cohere-ai/cvm-measure

RDF knowledge graph data for [cohere-ai/cvm-measure](https://github.com/cohere-ai/cvm-measure), parsed by [repolex](https://repolex.ai).

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
rlex download cohere-ai/cvm-measure
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4f1303e281986dee98e7e098db594779f040a190
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4f1303e281986dee98e7e098db594779f040a190
│           └── chunk-001.nq.gz
├── blob
│   ├── 00294b25e8a2ac5d7b1377afb57e70cdc88d1fa8.nq.gz
│   ├── 0034a5019b9f41238e4cd0a75592f2dc77edcfa2.nq.gz
│   ├── 01c4319db9dcea382f8fc0120f0d7253e37a6d0a.nq.gz
│   ├── 03c6a77adfe5a9950ec8376c9b29de1f2cdadecd.nq.gz
│   ├── 07101dd75ed4847511bc96a17989e171106001f1.nq.gz
│   ├── 0ca1b086b60c3d573c2a618c508bebe297730bd4.nq.gz
│   ├── 12fd084ee2a3a2c9441d0dfe996979d24cdc9f10.nq.gz
│   ├── 1ee91221969c450f7283977f97586c3442b2de88.nq.gz
│   ├── 2005505893184455e94f4fefd52d0388df271e50.nq.gz
│   ├── 28653a3f00b84f4c67e70ab9ef29cde8d2c04d9f.nq.gz
│   ├── 2fd8e85c509e00f9686b918a142bd6753db70aad.nq.gz
│   ├── 31877e8bd765e931718e4772c7073aa13b2a8274.nq.gz
│   ├── 396ad4902be38db7f1327fe9a49dd05add19b889.nq.gz
│   ├── 3aa5c12e51b98ee5f7ac4b3a066d2a658570c596.nq.gz
│   ├── 3ac303e6d8a2100b7d8b8275e9dcb67c6f35d550.nq.gz
│   ├── 3d224a22e2259e028777b9c7ce412a03f8135826.nq.gz
│   ├── 43b22da841cb5cad6cbfe3438937fcb6354fb4f6.nq.gz
│   ├── 4624dda3ceaf538697711eb6ed47c5b4daf40f6a.nq.gz
│   ├── 4e4a5b56d2acee9870a895d7923ab7f61e1bbfc7.nq.gz
│   ├── 4e4f1d3fcc86c7907fd47c5ada6cd50f9d7de1cb.nq.gz
│   ├── 4e8a7abf47d5bafbea64b52939cee41be5ecd9cc.nq.gz
│   ├── 506c8530f659924ecfcf7e7021ce60d7f7878463.nq.gz
│   ├── 5156cd5631db898fee2ebeb7404ae06c0c96c363.nq.gz
│   ├── 51d80d939179bd49ff5062ee33aadc7e8691abf6.nq.gz
│   ├── 5765b1bf234f341042cfe63b344015ff0339716e.nq.gz
│   ├── 5e473c5cf04c92cb6295bda450c2e793ad121f0d.nq.gz
│   ├── 62b546530cc91d02868c3f9b3440eb5ea6251421.nq.gz
│   ├── 64b8f3ddddb5bada13b69227ee5a192a25cc5c09.nq.gz
│   ├── 66de86621b958a32d91f391e76185ec7ecfa50e7.nq.gz
│   ├── 6e794e75db5078a930967e37bebe1dcf3a8a68b8.nq.gz
│   ├── 78d41129f7cf65de63174f8c7a9ca255c6464818.nq.gz
│   ├── 7953b1601afa6dbddf83a6187c207f8f11cbd195.nq.gz
│   ├── 8347a0bd6674b1a03c9953a1f99ce918a6c8d6a5.nq.gz
│   ├── 881fcf7562bd58f9d7c995247baea6caf4af9b97.nq.gz
│   ├── 8849c89955426b513ecb5d2a1184e2edbcadd83c.nq.gz
│   ├── 91af0a4e03a423571cb9d54a0bbd861a5edf903b.nq.gz
│   ├── 930b61f5e996f2a73aabc707e565045900193907.nq.gz
│   ├── 99df2a92ace384fd2a4703d755ef715236429e78.nq.gz
│   ├── 9de34c7b6114e4ff8e6087b5686aef9e85bc3b93.nq.gz
│   ├── a98758c310097b072ab3d7e7aa8253a42e7cdb7d.nq.gz
│   ├── ace72f810b20517c95ed6b22b349a71a07959fbc.nq.gz
│   ├── ad5660094248c92f6352780ed7c5c896d197f7ba.nq.gz
│   ├── c0b8fa5fcfea59fb15fc068db5d3f184550065bd.nq.gz
│   ├── d3bb8de59ad45fdd3f054edb5fc347c66efe2ee4.nq.gz
│   ├── d5517a5554e36f8b91ec61b7b6bfdde6f2c1424e.nq.gz
│   ├── d661a6e65ec8bf6052de3314f489f834ae071def.nq.gz
│   ├── d6bae493d7f1659120dfed43c4412a8de5027cc6.nq.gz
│   ├── d9358b19f1fa5e17a3a0672cd03e1d6b155ee8c9.nq.gz
│   ├── da0aa7c4c234657f5e91399ab1bd1583862c87ff.nq.gz
│   ├── dcb01d83efff6c15cc2ca50d0641d0bd0c5b4088.nq.gz
│   ├── e69bcca59b1ec1a7a26dbd39b710aaf60decb663.nq.gz
│   ├── e7da15d0e6d9ccd3e958824686ebd3d163fd418d.nq.gz
│   ├── ebb073c4c38fcb9905a094dd54dab0623bdc7c9c.nq.gz
│   ├── f2a4c68134e3f607a7c4f5b361ffc3fd9252614e.nq.gz
│   ├── f331def684fdb22a031589b822dfa5e070b9f08b.nq.gz
│   ├── f7900dc0a0b2dbd0ec45f8aac25d7fc7e3c09292.nq.gz
│   ├── fb54bb90068a977e30334af9e99ae2b826fbd360.nq.gz
│   ├── fca0aa2a3b594087345ed67fa1e3d9850cf6ad11.nq.gz
│   └── fd4b8cdb55319d01ca3f4b0ad5c2db6f83463c98.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4f1303e281986dee98e7e098db594779f040a190.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 66 files
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

[cohere-ai/cvm-measure](https://github.com/cohere-ai/cvm-measure)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
