# Repolex Knowledge Graph of ansible-collections/community.healthchecksio

RDF knowledge graph data for [ansible-collections/community.healthchecksio](https://github.com/ansible-collections/community.healthchecksio), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.healthchecksio
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 46035ace3efea706d7c9c953227f8bd4b7813385
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 46035ace3efea706d7c9c953227f8bd4b7813385
│           └── chunk-001.nq.gz
├── blob
│   ├── 0164155b81025416095f31a4732098ec238e6476.nq.gz
│   ├── 02ece5972811cfcb64d7c4dcfc47a76cf87bbb09.nq.gz
│   ├── 0326492726c0167cb475ec5bf1e924e57dd113b8.nq.gz
│   ├── 05c687935a173fec186a17a4cbf2ce2d00313fd9.nq.gz
│   ├── 09b8b3d7b9732a505cb7dd31344f274a4b43feeb.nq.gz
│   ├── 0d56704170dfa4ef6846f3c9a25f86e25ad80390.nq.gz
│   ├── 169f276df5ad5d3469ba26d85bf6f14598d5dfb8.nq.gz
│   ├── 188bd44fd875e97ca6bc65c762715f44c3eaae70.nq.gz
│   ├── 1ba783cd237a107f5414470adc4df4aae4fb3fbc.nq.gz
│   ├── 22b3a6a6f92e8a7a4d09097c362d571794ddb11c.nq.gz
│   ├── 267f314483ed17133086dd964f191ea0bf5018d3.nq.gz
│   ├── 28ba68659d5dfb61dad2827435c44556fe43b8c7.nq.gz
│   ├── 29b8f0f022019ad5201b952db834449032143243.nq.gz
│   ├── 2e53f2e54fbda027befb8d3e7b64dbd5906b3b3e.nq.gz
│   ├── 2ee3c9fa9b21eade729afb639808ce15cfbbf6b2.nq.gz
│   ├── 3079e489b2ef94866a1a04b65fcab0f1ce87e8c5.nq.gz
│   ├── 33030f6050896c1e048ed8b8872672e208e95ebc.nq.gz
│   ├── 3d8b13cdfb1d2b1bb531236366477604f5bd5451.nq.gz
│   ├── 3fe67f93fc503a1c479c1dcda87b569ca2e17af8.nq.gz
│   ├── 40a5506639ff92a86e8b26eadfb47ccc59f1e1df.nq.gz
│   ├── 41b8d0afa9f4f993ce2c08433b80ad3d5420e87c.nq.gz
│   ├── 4437415b6e1ae9712791763d5226757a237c700d.nq.gz
│   ├── 45752bc504f759db4392dea7d6c8a0c39645a0a4.nq.gz
│   ├── 543422ba548852c4b22fe601365bfa55597200da.nq.gz
│   ├── 57a7faa4b0c5f487b1abeb8dcfcd6afb9e0ad9b9.nq.gz
│   ├── 589bec07e7af825d229df80597c743b58e9d2161.nq.gz
│   ├── 61cacd78eb4cf8408d28c94d3d33f2461d9e164b.nq.gz
│   ├── 6752c8b8d9fddc00ed20f84334db9e53718c9764.nq.gz
│   ├── 6e17cbe4d3cdafa62835613cc92ff18f5225327f.nq.gz
│   ├── 734857639de46bfcf6d5aef5279b57e8883a3f32.nq.gz
│   ├── 7e26fbcfbb493dd91c6074bd5bdf329a8e27c934.nq.gz
│   ├── 81839b146f92001e3be186b1e92e21ed167f29fd.nq.gz
│   ├── 81acebd8c090e03fed53df6874db36cc89e530f5.nq.gz
│   ├── 840e178872a9ac1f785314ff8275e33744214ee3.nq.gz
│   ├── 84937b38461d0d58f9ffb6ad1c1ec8d7adaa1d9f.nq.gz
│   ├── 859c7e3d0259c9b0d955b5220fa7af3eb47b4c96.nq.gz
│   ├── 85bc2768d63bac7ef56c995c09072e4c3c3d6246.nq.gz
│   ├── 8c5f724ee0a2b64cab4069e1b999dc4737c17dca.nq.gz
│   ├── 8ca412b15cf144001f6ca43c2e799f1a7c0af846.nq.gz
│   ├── 9302fc0eb9010b5045940a980c6af1c95414ab5e.nq.gz
│   ├── 97176ee5595f0586e09a0c4ee2d53e1dc6ae4456.nq.gz
│   ├── 9b7bac1f6f2931587d75d13cec8b04741e268319.nq.gz
│   ├── 9b88e7e7b82737367785a57cbbabe2abf6d140c1.nq.gz
│   ├── 9dccf7ef174657345b77b37626c52cdc0390117f.nq.gz
│   ├── a1ada66964dbfe46a0f548a92925fae857e79963.nq.gz
│   ├── a375785604a26addc11d77df446d040f95c35761.nq.gz
│   ├── a43718d50a672dc0b45d40f4092fd3db2b7d27aa.nq.gz
│   ├── a9506fde03e5ce1ffdb846f2c939f1a08ce8715a.nq.gz
│   ├── aed6ef40165563960be0e93977719b5869091fcd.nq.gz
│   ├── af24ef8128e0d8c9f6c9af221efa67efb68cc3d0.nq.gz
│   ├── b09a4b5e3afb9bd7a3e1df8077a16e322f4d9c35.nq.gz
│   ├── b0f2435436a0b793474ccd9de06d1f51665b2db3.nq.gz
│   ├── b29a345445d019040f50c06108396558d5865ed1.nq.gz
│   ├── b4a17dec0383181a3caed73fc87775df337d0eee.nq.gz
│   ├── bde018249bbaba676048c5ccf4642292f86232c3.nq.gz
│   ├── c4aba11f9e262ba5cc01df0c6c3e5a5bae603843.nq.gz
│   ├── c733d46248b1fc62fd3ec595e01767c3836836a7.nq.gz
│   ├── ca6cb62126c2865478749ec3dd71661a12618336.nq.gz
│   ├── d249c1d7242abe565af590e4f94908310efdc8e7.nq.gz
│   ├── d5865e7372ee0dc821d1c89672091f197185bb94.nq.gz
│   ├── dc3d23fb89c73c5adb64f4c30f8c50063c7e5db9.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e90bba99b6a5184e5c01b918d1818ad393faf26b.nq.gz
│   ├── e98c9be383f8e42219a7f1edb2c2d2dd89a26c24.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   └── fc661127234d0acdd2bf90ed61aa1d667f6efd53.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 46035ace3efea706d7c9c953227f8bd4b7813385.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 74 files
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

[ansible-collections/community.healthchecksio](https://github.com/ansible-collections/community.healthchecksio)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
