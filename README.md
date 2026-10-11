# Repolex Knowledge Graph of tortoise/aerich

RDF knowledge graph data for [tortoise/aerich](https://github.com/tortoise/aerich), parsed by [repolex](https://repolex.ai).

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
rlex download tortoise/aerich
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6333068e09a3f14b45699487846714de525c735e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6333068e09a3f14b45699487846714de525c735e
│           └── chunk-001.nq.gz
├── blob
│   ├── 029f14cd459973bf914a7619cad32b00456f28be.nq.gz
│   ├── 03fe32a1efab9f26df4316b7f3edbdcfa499f7e8.nq.gz
│   ├── 06b3c14116444342612550224963cc4487289c73.nq.gz
│   ├── 08c2b223ad9feb57da0450254ce0cf94f9bbcaf1.nq.gz
│   ├── 0b366bafe298fffaeaca638a879940a5d8d01280.nq.gz
│   ├── 0d38dc24a6d77d1c36845d5cee4b2aad9bddea8a.nq.gz
│   ├── 140ccd62eba332e6ed9137b3834d2576560e451e.nq.gz
│   ├── 141c81bc53f5c6768a0ad4924e713b80deb1394a.nq.gz
│   ├── 17597607ee3a351f4a701d0a48dd0b40917af7b4.nq.gz
│   ├── 1812cf7a8cf6abe347428dadd70526ff6203842a.nq.gz
│   ├── 1872fb850f78a5af9650ec810246ca3199e953e7.nq.gz
│   ├── 19d4fd055d3b3311db51ab2b6fbd5848c7570f43.nq.gz
│   ├── 19f67013085d817690ccbd8d5acd586c0c82c3dd.nq.gz
│   ├── 1a7f0874647639f69c7c0b58aa3352bf93ba4112.nq.gz
│   ├── 1ec34d0abd73f4a9a273b9c3b28f8f42c2561d34.nq.gz
│   ├── 1f4c4d43b2672dd5d08b5ddcb25edc352ca5705a.nq.gz
│   ├── 20b7ad414e488b760d7097267ca58d5b78045337.nq.gz
│   ├── 221b050c2072bf3c89c34e186ced3fcfef2169f4.nq.gz
│   ├── 22d133ce09a4151b41a186277f0fcfa61a85995d.nq.gz
│   ├── 22e902c08231fc052cd64ba26a0a3b736b323a2a.nq.gz
│   ├── 2481952536880591a23389b2f1a82b0b1f19db35.nq.gz
│   ├── 250e3b0cef683c42a7891bade2a3dbee13a83942.nq.gz
│   ├── 2886cd631607c0198924d92d5cf8e208bcceac11.nq.gz
│   ├── 2956a3a15fee0cf6047dc343fb85f52f12422ae8.nq.gz
│   ├── 2e9762baad0d325a5d8ae573c4bc1e084551a46c.nq.gz
│   ├── 3157981c4f79da202fbde001804b693ed2a8a2d4.nq.gz
│   ├── 3181d5d3c4bcfdc6f421e7ece92ba8ba22749ce6.nq.gz
│   ├── 31d71a864da409d03ebbf6cdd6864afd03854b76.nq.gz
│   ├── 3228cbd3d5b62c5369610ee432803e7adc8f00e0.nq.gz
│   ├── 3283a509693c79f29d04353f82137e5e28a0272b.nq.gz
│   ├── 38d1edb5aaa712a5b9bed5a6c429a16e823da423.nq.gz
│   ├── 395a1bec8928c489b558d1158dc8b732ec745829.nq.gz
│   ├── 39bf58f1bf5bc1388f7ff55f2da4f960150e943c.nq.gz
│   ├── 3a27755c3080535b5bb347193ac807c89294b58b.nq.gz
│   ├── 3af9eab4a1a79bac6d530180946d74e1fe358a32.nq.gz
│   ├── 3da2d3d3231e9310382072668785b185e2b6e52a.nq.gz
│   ├── 42a89755370659f317e04563f2594de4164eaf94.nq.gz
│   ├── 4538b41a35f6fe5ff6214532e6286b70eb8b5e19.nq.gz
│   ├── 469604acb033e463ca9a996a16506fa38012e2f1.nq.gz
│   ├── 475c7f61c9b3586e0514ee9fc99f002be562067c.nq.gz
│   ├── 48e85e85625f7a1f4c3739482d752c9f202646e9.nq.gz
│   ├── 4e28416e104515e90fca4b69cc60d0c61fd15d61.nq.gz
│   ├── 4fbe80a8f35e6302ed833c157053238654b898a9.nq.gz
│   ├── 51802d99a3d1aaa4cfacfc1713aeda8d1701f0d8.nq.gz
│   ├── 51bc6efa3bfd712c3327979d182e9f88a606a0a1.nq.gz
│   ├── 521a1c1b9c7f580511fdb585fdf48c89cc378cca.nq.gz
│   ├── 5290f5f4c544bfa7de1d3a0a30236ffc63a855e7.nq.gz
│   ├── 52de0f74d2add6bd10941fb2d442c60cd759d0fe.nq.gz
│   ├── 5367bc6316eaebd7fdd4e8056bc0ebfa656c39dd.nq.gz
│   ├── 5405b9760c2e5bcb2979e49bcd8c31b5f2ba8f4a.nq.gz
│   ├── 559126373eb207bd204876099cd4e7f25b06e750.nq.gz
│   ├── 56945623fd77e61b30ce5c6cdfd0ad36dc40490f.nq.gz
│   ├── 5b72211856810da1b6f596f99c7012ec057140f9.nq.gz
│   ├── 5c336ab4938c319fbfc39fb8a56877373fc7d4b5.nq.gz
│   ├── 5e506ff37f76ae4581d3d0a30522fbd7882f5b83.nq.gz
│   ├── 60328e312082774758794314943af7c84883e42a.nq.gz
│   ├── 60f5c9b08bc9dfd937de66d6992611e4bb4bb223.nq.gz
│   ├── 6311a0dce63824caaf2c50d053de8203a59a14d8.nq.gz
│   ├── 635e1dc4d0fd3c24b69376286a61cc0cec83d7c1.nq.gz
│   ├── 6465497f352c95d8b86f1261c451c8185037f391.nq.gz
│   ├── 653de795c714930cd354d89b199bd7b4c1347a99.nq.gz
│   ├── 65be6e2458249fc92a26ed95c268f8b04dee7f7c.nq.gz
│   ├── 67c1890b6961f99acb406076c453462f1bf0864e.nq.gz
│   ├── 6991226eda76416ad5ce4809d444934badb0ec7f.nq.gz
│   ├── 6a2a501c1cf608b99991099295761749727daaa0.nq.gz
│   ├── 6b5c889a5bbeaec59203fb36525bcbc0b8762fcc.nq.gz
│   ├── 6cd5dad2b3424cf149afa3fda29bafc3942e23be.nq.gz
│   ├── 71509d375427564bb8ef1ddf7bc6ec7c7ad23d39.nq.gz
│   ├── 74fba9a65bbeda644c80b233bec9a15a35daea4a.nq.gz
│   ├── 75126fc69924e6d6aef3597f488e634cd3c6a2d2.nq.gz
│   ├── 75cc53c4e392d44a5d9789ea679c42418425ffc2.nq.gz
│   ├── 78201b133882c488731001bd279ac8af4dbbf1da.nq.gz
│   ├── 7938a5dbad7514022b4ec1c1c21abaf164664a6b.nq.gz
│   ├── 79e55f56a63937ef4ae4b4b097fcd7d9adf06a44.nq.gz
│   ├── 7abf75c550617a53217c08ceadab3a13589e044e.nq.gz
│   ├── 7b63f4e3e4adcc56feee05c29ff6ef9ab65fc197.nq.gz
│   ├── 7d38e827079cb359129f33cd802a929ee6f4ce4b.nq.gz
│   ├── 7fec7aef9a94ffa391be46ad4644d864636bc6f3.nq.gz
│   ├── 8092cdda546950c71882bb6f45a6888dfa847849.nq.gz
│   ├── 83959f8cf4e5d82afb1cc426a8ebb579e057b48a.nq.gz
│   ├── 840b60e93f4828775dd4462e84050eb0aacb7dde.nq.gz
│   ├── 8419ac2a298b24ce80f9e398e9520eeee8422b12.nq.gz
│   ├── 85b80fb21871884022785732b20904ce843184c9.nq.gz
│   ├── 8698a09b048de4195fda370ad6aba4e8cf5b4eeb.nq.gz
│   ├── 8760bd7e3ba0382f87988f860d3e6f85d3e1a6f1.nq.gz
│   ├── 8a0f1c0153000aef71ab93944f9198286fc32502.nq.gz
│   ├── 8a58ffb7b97e2fd9dfc1c2a498affe20817f7fba.nq.gz
│   ├── 91e85363b24184794a37896e1c8738334ebeefae.nq.gz
│   ├── 92ad59dd52a1f34863244931efad91dbd4bc3250.nq.gz
│   ├── 934944c2681f47f78b0b7c498c5528a49504f750.nq.gz
│   ├── 942b70ce6293eb84bf879938c3b0c380422addb8.nq.gz
│   ├── 95ca39ba6263aa185e98739ee4b7fde9b3d1ba2d.nq.gz
│   ├── 95e4ffbcbb41267f8a1dfe8052b929f933e16018.nq.gz
│   ├── 9b1e057a7404d1cef892bc27afa0889d6ae4ff46.nq.gz
│   ├── 9d8f36f94ff039dbde6b72cb22d786044ec13f7d.nq.gz
│   ├── 9e747ae65a06aef92082f112510afb7ec63b952c.nq.gz
│   ├── 9ebe309b84fd74015c0750a82b6765bbdaf50166.nq.gz
│   ├── a2c80023bf16a3b3a3b45c75e21e6080454e8906.nq.gz
│   ├── a2deba48c4cad84939eb5b0dbf5ca37702f91763.nq.gz
│   ├── a510b5e2487edab39f6f888883d0130b63e6b596.nq.gz
│   ├── a81daea651bb9ef66c6117d3ac986cbb69e75c2c.nq.gz
│   ├── aa3f5dac61a22ac72ce8328713788e4463df5162.nq.gz
│   ├── ac8d67be68a4edd96e8a252772e68377d100fdba.nq.gz
│   ├── aefbbde021964f802cd8d2f8de002a0cbdf0164b.nq.gz
│   ├── b0a7280885474fd8d87480ef83d4777c1ab064dc.nq.gz
│   ├── b12cdc4d9ced452e2ea8997517aa596a73182ac8.nq.gz
│   ├── b342560be56cbf7887b8ab3b5a24c030e8a900ff.nq.gz
│   ├── b4b3df88be45aed8f9c51f70be672cd9c53bb3be.nq.gz
│   ├── b5b4a3d5f7e9e90680162f8f96b455c035b25059.nq.gz
│   ├── b799fb7793e11281f351e622e02d3e89521758f5.nq.gz
│   ├── b9417f19240238705c5180f3088db94fe470a317.nq.gz
│   ├── bc4d0aac6ac0fe649c3f427e67b949b3e18f1ea2.nq.gz
│   ├── bd78d02e0ef8a771b9d7fc69a08e68f80e7dc474.nq.gz
│   ├── bfefc9faa8e8749d591b7b33b784a1d8563d9f6e.nq.gz
│   ├── c4feb39c651a6d5018dd0340866f6e3a3f1ffd85.nq.gz
│   ├── c66f78cdb5d1c39b6f65d38340329a316c3c079b.nq.gz
│   ├── c7dcd7e4252942423a52642a9996b36be4cbc26d.nq.gz
│   ├── d002fd02cad1c5ca91e36f927687236861c4e61b.nq.gz
│   ├── d10f77e7ea7d32565f63cae516fa0a1d778c8c7b.nq.gz
│   ├── d182f89ff11607747998448a0482eef362296e5a.nq.gz
│   ├── d237a9ff9f4901ce1c9056fa7049bb0b3789d9d0.nq.gz
│   ├── d3879e8708c371c0347cbc49760ba865b5947428.nq.gz
│   ├── d7e48a4b046c0cdf51af92dd30f17164fcc19a77.nq.gz
│   ├── de162f005705d2b5b2d9b343d76dab08b55fe761.nq.gz
│   ├── e11b5ae156a282d95d52b323ed829a1562dd0412.nq.gz
│   ├── e371a53a70b87cdcee19484b3f79769efe50c293.nq.gz
│   ├── e6755e22653eca410060c4494e2f3a0bcdd6b2bf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e74216bd48be2dfbba0e23063a18de130375f7c9.nq.gz
│   ├── ee1733fcd8e0877af32ba5f09b70c4684a7f97b2.nq.gz
│   ├── efbf62464155e9719f4b2a0cc5d74aab6441e53d.nq.gz
│   ├── f0e90793aeae5a52d34753a2cef3c4c01f293e2b.nq.gz
│   ├── f392c388e7c99e21e7f0ec51141fbd5d42201173.nq.gz
│   ├── f3fccd12680984fc495a8fb1eb26024f466f6829.nq.gz
│   ├── f41aa8ce383f62322925df4d15cb8d13edb3cf2a.nq.gz
│   ├── f5c0642ebc62fc04d80af6eb36320c9a4eca46db.nq.gz
│   ├── f75f47ef016b6b05d83d6e995d80c0cdeb1a938c.nq.gz
│   ├── fcf6205a3ebbb4f8251af9f2d405ebe2fc8b9a16.nq.gz
│   ├── fefe8a5fa9e19843ddb9f2a732f65a548cc717f3.nq.gz
│   └── ffa9115de23ce0b7dfb0ec38a62ac0488b1e245c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6333068e09a3f14b45699487846714de525c735e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 148 files
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

[tortoise/aerich](https://github.com/tortoise/aerich)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
