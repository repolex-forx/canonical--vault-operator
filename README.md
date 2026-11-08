# Repolex Knowledge Graph of canonical/vault-operator

RDF knowledge graph data for [canonical/vault-operator](https://github.com/canonical/vault-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/vault-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 14b4bb942f40564b4e2512ee039ba0f745ac949b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 14b4bb942f40564b4e2512ee039ba0f745ac949b
│           └── chunk-001.nq.gz
├── blob
│   ├── 00eabd73fd5dfa67a9940ba021abf3c008147e19.nq.gz
│   ├── 02a414e61d8b482debe324dacccbfa2f6cce16d3.nq.gz
│   ├── 0434ebb4e7d29713017c724a2a21cf833f03b83e.nq.gz
│   ├── 136eb0b2cd3b5f7e72c7a2b2a23613456c28ff03.nq.gz
│   ├── 13af703428e23ce7d56cf7a1bc7061b64a8f6a18.nq.gz
│   ├── 18944d166a1c37a34697407aecbaa19d3e40996a.nq.gz
│   ├── 190a91de300d085fc3086ea59459dba758284943.nq.gz
│   ├── 200db95bec45d9ea2d3459ac14d75cc63dc0a78f.nq.gz
│   ├── 221e926b81eb35bd6699b428e7a400676b0fa868.nq.gz
│   ├── 2eae080ded555d42e52f538acd12604ddc20e1a6.nq.gz
│   ├── 2f02df065bae8b0e08c3a777016d91248013c329.nq.gz
│   ├── 38945df62ea35c49748755949e31c982c94523f1.nq.gz
│   ├── 3c89914157c82ecde527e96f3b960584a39965a3.nq.gz
│   ├── 3ce0dd076d9490bfa0ae2f6f2152eb86a5e9a829.nq.gz
│   ├── 3dfd1517ff25735400630fcc72d5bce7c567560a.nq.gz
│   ├── 4802e6f484dd4eb89f25d8cfcd294699e149f9a9.nq.gz
│   ├── 4ab99049e3aab0292e6c6c93b71cb59e6b529492.nq.gz
│   ├── 4b5d2d0953169c9a807f97261d357ebb05f16052.nq.gz
│   ├── 54d71694aad2642f0ad7b3d466e2eebddf2fa169.nq.gz
│   ├── 5701e06c4b89039154f8c851fe0f971d62b78eee.nq.gz
│   ├── 5a7871ab80d73ea04effc031c926ac461869ec7d.nq.gz
│   ├── 5bd48d1b4e1be036af9292632cf3dcc59e49ed17.nq.gz
│   ├── 5cd0ffd4b26fd51a7638ab84829f17f52033523f.nq.gz
│   ├── 633f0cbee373e4d7ca15e17035136e6317d71e78.nq.gz
│   ├── 657ab197d9d531d605575d9c179ecac6f8a54e10.nq.gz
│   ├── 663d08f5d8684d0a20aa39437bbd04fe27f7af3e.nq.gz
│   ├── 6b8ae973517d53fefacbc8d223ce382b23000f12.nq.gz
│   ├── 71cd8b62c9268ce50c362f8848ddbd8d1516fca9.nq.gz
│   ├── 72cc9a26556fb6ff437b85ab288d0f7b4493a8b7.nq.gz
│   ├── 7be8f69076887eefb5b56f7251d53373bfb78074.nq.gz
│   ├── 7cfadad2a6eaa17d972db4c4f37884bed1e49452.nq.gz
│   ├── 7d7829e11331a45730f21b4b60091485f34635a3.nq.gz
│   ├── 7e679b33905a9a8e92fadfbbfd0f004e927ab018.nq.gz
│   ├── 859ab2bd46724cb5a2160482734ab5e1e003816c.nq.gz
│   ├── 8d771e187ba4b2ced1b643c804548e5c014bab70.nq.gz
│   ├── 96d605be8046662a55e98e2d8ce32ac9e31a137b.nq.gz
│   ├── 9841311346737214f59fd7c9e25ffb284029f3fa.nq.gz
│   ├── 9c4d2fbfef883078e7b136ad459dbf42ae038091.nq.gz
│   ├── a1efb8dcabeeffb0a8d14edf134b614f2e4b04f8.nq.gz
│   ├── a78e669672532398c5ab2c952fb4b3d07b312ead.nq.gz
│   ├── abc851f3f9b3a87c12f8a84b59aa3d2945a6c32f.nq.gz
│   ├── b18c271342558e21e62fffc99a48eef8aa3b8510.nq.gz
│   ├── bb7ac5ed576740b2e600a00c621f19ecd4452bd3.nq.gz
│   ├── bf4ab18b4a64bf523efff1f6e350237e7519e853.nq.gz
│   ├── c81f048ab6a6d5f3849970d305fc0828612cb88f.nq.gz
│   ├── c9dff112e7f0e8af001212498491301a31fffac5.nq.gz
│   ├── d04cc2853243b0f2a9099a488efad17aa35798ac.nq.gz
│   ├── d54e174965cd46628cb383227260a3687f776d53.nq.gz
│   ├── d55649a6dd70a628586f3dbf9b9c0796c27cfd8e.nq.gz
│   ├── d60c06711bdd3c7d9fadfad72a68fbf954240055.nq.gz
│   ├── d6b02ffecc30187ac5f09fad6ca67fd8b52f0b46.nq.gz
│   ├── d6fc628ae64d9ada4ef2dedf0a96d8189a361698.nq.gz
│   ├── da38ad47055f3b7afa333b123515988cb887b4f0.nq.gz
│   ├── dc556088f3fee7020f995f3a41ce126cf971f632.nq.gz
│   ├── e45ba95b0ffd24acd2db4b9a65b72f342e291b94.nq.gz
│   ├── e59369c0e16e4a42792f516b395ab184c0112a5a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6cf2e45f2feb0a8b5442ffa2e6f9cf1bf102e8c.nq.gz
│   ├── e6ddd0b76e39aa9d1f72910ec8d831e2c3ebae9f.nq.gz
│   ├── ebe5b8a417e307305673c59612b4aa3c93f8a865.nq.gz
│   ├── f1f53efb0aac01b28b7c57fc31285afc9d140af8.nq.gz
│   ├── f5614aaf6b449c7c45703795fc80e276c60877a1.nq.gz
│   ├── f6cfa0602fcd7f8104296210c367dab0eda167e4.nq.gz
│   ├── f72fe2030d0c0cc59e92920b7e321aef275132c4.nq.gz
│   └── fa6c4c4242ddde9c12673e4e2dbd1fe818b4c73e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 14b4bb942f40564b4e2512ee039ba0f745ac949b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 73 files
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

[canonical/vault-operator](https://github.com/canonical/vault-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
