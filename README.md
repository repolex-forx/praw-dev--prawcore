# Repolex Knowledge Graph of praw-dev/prawcore

RDF knowledge graph data for [praw-dev/prawcore](https://github.com/praw-dev/prawcore), parsed by [repolex](https://repolex.ai).

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
lexq download praw-dev/prawcore
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 82bfa5a98aeafe7e73c5e11fc87a7ee514779b9d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 82bfa5a98aeafe7e73c5e11fc87a7ee514779b9d.nq.gz
│   └── repolex
│       └── 82bfa5a98aeafe7e73c5e11fc87a7ee514779b9d
│           └── chunk-001.nq.gz
├── blob
│   ├── 0081b8c642ebcc16a8d35a47974bdd50c008ca0f.nq.gz
│   ├── 026aaae3e2bcccfb7efc268629075f52386b0462.nq.gz
│   ├── 0dd1db524a0972311c8c1d9657f93f47d2422731.nq.gz
│   ├── 110e3e3c8b4f89613cab952d2606700618347316.nq.gz
│   ├── 1214b4b8af26403498e6024d9a9800a4ed9af48b.nq.gz
│   ├── 163df0a321610ffe4de57ae11a6097bae29caeb1.nq.gz
│   ├── 1692916bc280541b1adfeef6ebe7650c84c50536.nq.gz
│   ├── 192391e32aeac6e6d166c6daa29fa8ec9bfb1677.nq.gz
│   ├── 1cbbb0916816f66d34208c195a1c32e88e4cc8d7.nq.gz
│   ├── 21a41b25d689b87cb3fc2c3d122b15d98c16e558.nq.gz
│   ├── 23edb781b299f7a4c682aa5b7cd65d3aca8d0251.nq.gz
│   ├── 253580d6a5b3a7c6d58a039fde19d4e5fedb75a2.nq.gz
│   ├── 2b016dc92ae30edea2c3684ec1d58bd1e646bdc5.nq.gz
│   ├── 2c03e3616cda3534dda3217a12c669082a6b833f.nq.gz
│   ├── 2ceffcc29468b9b1ad049923dc7ccb037037187d.nq.gz
│   ├── 2d963bd2ab1522a2287dedcf86e71dd875e427d5.nq.gz
│   ├── 3110018fc198fae70e689be54b84f5d7dc102325.nq.gz
│   ├── 34b7ad96080c7c9bda924c60ae30c53d0c05804b.nq.gz
│   ├── 37d7c8cd1051d2f673a2e25731818c95d8b1e9e8.nq.gz
│   ├── 382de555f5d270f26fe0713da403ab1d98905ea7.nq.gz
│   ├── 39ea9666b7254fd8a7cf87f78cb1b98cc8996d9e.nq.gz
│   ├── 3bd7bf7228890af40a7955bd85fa567362d5443c.nq.gz
│   ├── 3c39f53f547ce57a184590bed6560633c3f544ff.nq.gz
│   ├── 4247708c1ab280688b1e076f87cf6ad6a8d2d206.nq.gz
│   ├── 4573911a4185bd32cb7c86bf390d87d6a8ad1d09.nq.gz
│   ├── 4703d312a2cfccdaf11cfe59dec9093cef70f943.nq.gz
│   ├── 47c3e0871d44f2c4c2318b09696f33783a6eeafb.nq.gz
│   ├── 4a4af15765d2233b680db9baf374b66068ce3457.nq.gz
│   ├── 4bc9c7f95e3aef0cd6ece4b5796c7a3ee1621310.nq.gz
│   ├── 4c056206c5089bd6e4700f0c2667d5e72b188aa0.nq.gz
│   ├── 4d1af2bc2c6495fb6d8767b36ce68bb838c26be1.nq.gz
│   ├── 4d1c0ab114a6860afea456ef80269d5000993da5.nq.gz
│   ├── 51a1c22116371cd62b709d043e64e6f41710d1a0.nq.gz
│   ├── 5c33d91af97337c76eff537b91f729bc24faac94.nq.gz
│   ├── 5dc8cfab653a12b95c13f5af65b14c606d57a65b.nq.gz
│   ├── 5e459bb41590766fef24d00cf67c3a9bead17f1e.nq.gz
│   ├── 6026d0b2bbb9ffc8790217a1c1bc541aca71cec5.nq.gz
│   ├── 6290846ad661654f47f536153d92053bf891d05f.nq.gz
│   ├── 6890b91e356191a9107092f4fc0cd82b25a404f9.nq.gz
│   ├── 6d933806ea6b4dad8fd3f8b7f7a5b5d2bc15bf2d.nq.gz
│   ├── 6ebc30822ec1a358f3da9f30f093f3f7afecc502.nq.gz
│   ├── 6fc4256657429d2b214d6d1afdcf488fc5c7df64.nq.gz
│   ├── 723c01f15d922af262f6cdea9c742151545ab572.nq.gz
│   ├── 749df66fe0b3465ec88482973323703a91c46dac.nq.gz
│   ├── 7d04ce3c0e3877003f661a2479134b48d4d25fd9.nq.gz
│   ├── 80be0cfdf51b4a2a20ae8ac08ef78da30d9d5c53.nq.gz
│   ├── 81a932a704c89c1698960e8d23d7de13f0845c48.nq.gz
│   ├── 84539d07d216d4e1f8cfdfa1ef3d63cc9508ee2f.nq.gz
│   ├── 86dfaf7bf22d66adb789324c352696b55fdf8c2a.nq.gz
│   ├── 8875bf7d1bdbbed278c05b14834551c93e914200.nq.gz
│   ├── 8a8387486f3c469a2d11a9c43c9bbebbf64e6636.nq.gz
│   ├── 8ac63437998b03e900ea78ee1adce744fa9c4046.nq.gz
│   ├── 8c6f265b0fb57e81bc67e2c18274af9126db27e7.nq.gz
│   ├── 8cd9834e90fc5c9bff76996bdb18c77ac7cf94e7.nq.gz
│   ├── 8d2e6c5b48e3dd1326e8d5e97b821d707cecea40.nq.gz
│   ├── 901860b2ab0d41f3af6860a8d390250cf0d2bfa7.nq.gz
│   ├── 92541769bf88fe99d1b9621ba0b8dbf7e14c6077.nq.gz
│   ├── 97e18ec5f974b1d8fb0b38e20d3d9a23f8c663a8.nq.gz
│   ├── 9ce7fc09be37b12f0e8a1b1a8c6df3fd84c9dc7e.nq.gz
│   ├── a0faa275d90c6423a9b1169a34d32688ea95c591.nq.gz
│   ├── a2579d3decbef4d82fd403bae2cf8c93b60f58a7.nq.gz
│   ├── a64e6495e199ee6d95fe2c9f86d0c72ee94c9a1e.nq.gz
│   ├── a80757fb0c288bf348fd4e7545dd7fb838a805fa.nq.gz
│   ├── a8e6d3e6e44577e211ef234ce9c8aa265947c1e4.nq.gz
│   ├── aa93251a881752f067a4ad19ebc43f4e8e357543.nq.gz
│   ├── abd2e5876f0a80b7354e564b69ce6b34a4dc024e.nq.gz
│   ├── acb735b13e237b82d5b311bcb405f13850e5ec99.nq.gz
│   ├── b1dd481db42d72e71f7b8801887b0c6f9daef7e4.nq.gz
│   ├── b2bb0e486466768ce4a65d51719bf053892412a3.nq.gz
│   ├── b39bebf55bdffcc33490152d377127bcea335faf.nq.gz
│   ├── b4f00df594c727802461a4f596586a4fb7973478.nq.gz
│   ├── b6367683a1f135e3f62d0f3c967994bb8003c506.nq.gz
│   ├── b6a6215d3b23a14d486474542397e9cfd79bf8f1.nq.gz
│   ├── b79ad857c0411ed6b499c183c74a47a4f59406fd.nq.gz
│   ├── b7c18f177377f5734eb1d16339eed120b6f1e927.nq.gz
│   ├── bc8c869a59bd6364dde32884f38b7784ba51919e.nq.gz
│   ├── be7adbb2d478197c27dcb67bbd5967b91ec2333e.nq.gz
│   ├── c17558135cc1b6c73747184fe72c36f6fc1eed9e.nq.gz
│   ├── c7695434649c5d980b69d0dbf3df9e61273985dc.nq.gz
│   ├── c9bc1bd591a4bff630bd4968127f840eb2bafcbf.nq.gz
│   ├── c9ebf1c740097d9fb5b562026c391dd1ca02a253.nq.gz
│   ├── caa53886dc86d87f2f20dd61d34cdfc14ebf2882.nq.gz
│   ├── cee9a1f61e6b4468036e2d793fa0a758ffbcdcf5.nq.gz
│   ├── cf112ab8f3f1e924b85e65301b5f2f729c47eb29.nq.gz
│   ├── cfb96d702164dc7abdf913dbfa8a5cd7c309b8fe.nq.gz
│   ├── dbf2ce300b76428f40833253b035cc73570bac47.nq.gz
│   ├── de23f06f631eb7a8abc3ae7ab50e661606dbe32c.nq.gz
│   ├── df30b4fc43c191b6e4f85dbf3e823ac9a49292bf.nq.gz
│   ├── df4b53c39bffa108367baea6958e057cf25d9bbd.nq.gz
│   ├── e034eab1adbda83bdc866919346ce47143e8b082.nq.gz
│   ├── e15742b66f8a45a066dae6a93226792e64291cf4.nq.gz
│   ├── e19731818f6cf62d846fd50e16ac957a7b8ce458.nq.gz
│   ├── e1d9f752ae0c93d74c38fb60325302c0fa9a8cfa.nq.gz
│   ├── e2283a83fa58e8233c5faaf7eef6191ad251c3d3.nq.gz
│   ├── e78e629cb9ce4d7f03b456c09b5a06762188ed47.nq.gz
│   ├── e7d9d6b6dcd0590707e1b41e6a60da5ab4ff576b.nq.gz
│   ├── ee94dd858ac3d504da99db38c40c6211d5b3570d.nq.gz
│   ├── f0de6645394f4a74010f43020cc39021ec33a181.nq.gz
│   ├── f86b0fffda2fb8e59a4487ef8f134da5e8d72491.nq.gz
│   ├── f950fc5846a1bf35a23857598c741c199a66111a.nq.gz
│   ├── fa0f0cb6234c8fb9273d53e4dd229038f7d3426b.nq.gz
│   ├── fc0c6dfee44dbfd5c15441c3fc80a244f27bd756.nq.gz
│   ├── fcd2a43a0d56843b7717630966171c12db4499e6.nq.gz
│   └── fd8205686ca48027215c5257d013d58e4d69019a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 82bfa5a98aeafe7e73c5e11fc87a7ee514779b9d.nq.gz
├── filetree
│   └── 82bfa5a98aeafe7e73c5e11fc87a7ee514779b9d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 114 files
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

[praw-dev/prawcore](https://github.com/praw-dev/prawcore)

---
*Parsed on 2026-04-17 by [repolex](https://repolex.ai)*
