# Repolex Knowledge Graph of pandas-dev/pandas-dev-flaker

RDF knowledge graph data for [pandas-dev/pandas-dev-flaker](https://github.com/pandas-dev/pandas-dev-flaker), parsed by [repolex](https://repolex.ai).

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
rlex download pandas-dev/pandas-dev-flaker
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7336459987b92961cfd950f86ba2ec2de702daf0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7336459987b92961cfd950f86ba2ec2de702daf0
│           └── chunk-001.nq.gz
├── blob
│   ├── 04ae291656e220478cfe6d8837815682d9e9f777.nq.gz
│   ├── 06b99ee44141d7c3c0c085dd7c0c46a81e123eea.nq.gz
│   ├── 07de459226eee5629a8fe68eed3d021db8355fa4.nq.gz
│   ├── 0adae3197dc9505639ea63e4e2d8bc8a6d1e2d03.nq.gz
│   ├── 0c5a37eb0adeb312718e533d0a4fbcbea6880056.nq.gz
│   ├── 129a170db12a21eb024c2aec23c1e60b0ca689d8.nq.gz
│   ├── 13b644bd8493569bfc681ad6b735ec7996e266ca.nq.gz
│   ├── 16b2165bfa9b93fab8b8079be73187cebf57d3b4.nq.gz
│   ├── 1fce97ec8d231694c1339160fb2fdadc5ad893be.nq.gz
│   ├── 20e4c0f6227d0e72afa7027cfad65fc400ebfb16.nq.gz
│   ├── 215e8cb6200bd590599febbe59e8b63a95367639.nq.gz
│   ├── 2a8590c0edcfad297155fa74c24bacd2deaaebee.nq.gz
│   ├── 2db2b14692cdeff39e6388503aa5f7f63bd1fe2d.nq.gz
│   ├── 2de00c3204fe28fb289fc0af1f710a03cde0bf16.nq.gz
│   ├── 316dc26d266e759cf1804368f99dc53e929c6b0c.nq.gz
│   ├── 346ff8df6a8f5d1603a426da07259e97db183dc7.nq.gz
│   ├── 363ad66339301dc14f1e2b3399d2e96159ba14c0.nq.gz
│   ├── 377c48b9ae140d42fa9d7ee535a0b9d97b420d99.nq.gz
│   ├── 3a1b06c6a09e6e62e20af2fc55e5e642b857f8c3.nq.gz
│   ├── 3eab1b7ab3d7e519c6f0884ab1bc4b8f6a9fc1cb.nq.gz
│   ├── 414829874b9dc8974a64515240ad0fe89c98c077.nq.gz
│   ├── 47af94918e1e3f0691b0434d6c305a18b2aed7b5.nq.gz
│   ├── 47e0d43c8e3196f89eb2cf2c8697c225019279e4.nq.gz
│   ├── 522fbe20b89911bb8d68b4a684a51225dd571764.nq.gz
│   ├── 5511c2316c6d411dcd3cafa5e88c74f2d036eb8b.nq.gz
│   ├── 567b46e8a5eafd1bf5c950b032e50e6cdc61327f.nq.gz
│   ├── 59f6a48d25ae677ced70f7c873abe78fcd65e3fc.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 6436169c046834fe90d890dc15607140243a54c5.nq.gz
│   ├── 6460c821cb782fd0bf79ff7d42c88cfa326067b3.nq.gz
│   ├── 6616ae2236f74e5ec9998f7aafce43136d135b5e.nq.gz
│   ├── 6668d43282d02facb1e6dd52159d86c976267e3d.nq.gz
│   ├── 66b410b4bb2c8a88adabe88ff752a001de659ae9.nq.gz
│   ├── 6beee427b92cd125e320b48587d9cae178549688.nq.gz
│   ├── 707a393c4847739b0833feb0b028bd5e4d6405d3.nq.gz
│   ├── 725f1887faa20e962cd6fe9175013a7bc2e94a18.nq.gz
│   ├── 72ab7a78bf0b54294f9296fe7401cf59348e5f38.nq.gz
│   ├── 73fd90e287e797478c8a35db9ab92cf970f3e237.nq.gz
│   ├── 76954a5a339ab03a07bce28961715f047771160d.nq.gz
│   ├── 778d4bdbc52294d644eb85098cc1f261f448e7a4.nq.gz
│   ├── 77ac6f988b4eb6d403721ff38dd2c033f58a54d8.nq.gz
│   ├── 822257935ca7a9b29b46e8a96f7b38bdfd865131.nq.gz
│   ├── 83c39985387b25d453f41ef5ec6840fde5277976.nq.gz
│   ├── 85aaf0ef87694222dd369edd63562eb56d48f86f.nq.gz
│   ├── 88064ab7cda9949ae7a11d8e97de9070e79349a4.nq.gz
│   ├── 8c20f482abcdc8766c2d7fe3074a9454ad01b440.nq.gz
│   ├── 8c50532c64852eed81ee0f3953bd5fa8d7786b6e.nq.gz
│   ├── 91754c601dd6b953eb9fc12932832efd5d6439ee.nq.gz
│   ├── 917cc75a8d4121ac9cbb8ebdce8f1c54e9af238f.nq.gz
│   ├── 9b7013f273b9a6c3157904bfdb17622d7486cb6c.nq.gz
│   ├── 9db8677cae1bebe59ae2be6d237c5c03df57b371.nq.gz
│   ├── a348fda6b66388a96ae5618ffd373a8a985b8419.nq.gz
│   ├── aae605efb1e5670090c9833d82fdf2852caa0c3e.nq.gz
│   ├── afe119fe22617d5d98ff2a052f1cdbead4bd56e6.nq.gz
│   ├── c2923901b67b27e28b29e02638a884ea596b8017.nq.gz
│   ├── c688f31f373462f85d32838142a0a4cc487a48e8.nq.gz
│   ├── d1e31acf09b6a4838019537fbf8c3895c091c34a.nq.gz
│   ├── d5fb24a7ab7b12b56a9549f5eb51761068208f88.nq.gz
│   ├── d8272915397c6151ddc3807957e77a7a71fc3ad3.nq.gz
│   ├── d96e883b6846863da92f9bab3dd06eb54432e332.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ef56468409eca1d4677b2ebd45ec66f35a5a8174.nq.gz
│   ├── ef5fe804f4a67c60258396f73b27c3dd707d59c4.nq.gz
│   ├── ef751fb522f0b27526573bd1c075d41b3a6f99e5.nq.gz
│   ├── f082e3142dc6d5d329535a38655aa3664fe71540.nq.gz
│   ├── f1137e4c00d192989d8915f591e164c214a6c28c.nq.gz
│   ├── f6bf673f5214afed1bb25d87a8ded025334e8464.nq.gz
│   ├── f76bf285bbbab52faad7b4a5b8a82c739eceffcb.nq.gz
│   ├── f94497dc7f560eb4db1dac834635cad54c21f7c3.nq.gz
│   └── ff152baa7a464c9161c7a96caf6605d201197ba8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7336459987b92961cfd950f86ba2ec2de702daf0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 78 files
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

[pandas-dev/pandas-dev-flaker](https://github.com/pandas-dev/pandas-dev-flaker)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
