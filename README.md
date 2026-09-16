# Repolex Knowledge Graph of twitchyliquid64/golang-asm

RDF knowledge graph data for [twitchyliquid64/golang-asm](https://github.com/twitchyliquid64/golang-asm), parsed by [repolex](https://repolex.ai).

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
lexq download twitchyliquid64/golang-asm
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8d7f1f783b11f9a00f5bcdfcae17f5ac8f22512e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8d7f1f783b11f9a00f5bcdfcae17f5ac8f22512e.nq.gz
│   └── repolex
│       └── 8d7f1f783b11f9a00f5bcdfcae17f5ac8f22512e
│           └── chunk-001.nq.gz
├── blob
│   ├── 04c084ea25178605105613b9a22fe08896b7f73a.nq.gz
│   ├── 07c340668138d1503e36959be1ee974961062fb1.nq.gz
│   ├── 09d520b4e9bec62ce9aba25cba47b6118034928c.nq.gz
│   ├── 0cca752332958bca44ab205a96502c02f4877edb.nq.gz
│   ├── 0ce620a9e9539a27c1cd5927f398f52cc7ef7974.nq.gz
│   ├── 0fb28b2919a30e0c7a2ef0fb0eaebe19f79d7fce.nq.gz
│   ├── 122b87ba66e1094200f279ea2f179f31bf0db174.nq.gz
│   ├── 178c8363d95d8a39b74167636f3b4972ccbfa975.nq.gz
│   ├── 1906810e386eaeb2cc62022ce24258dbcaa475fc.nq.gz
│   ├── 1906c5fb9c8e49b1f709cdea98295fc39b2a5adb.nq.gz
│   ├── 1b1c394038a7d9cea376bcd17357c0de06f129ac.nq.gz
│   ├── 1e0a9a73f95daac862fa9c874fbfd87df7d8f6f2.nq.gz
│   ├── 1e33f1e3207efd59ee331492a41816e3adcabf43.nq.gz
│   ├── 218b7eb3a004d61b3c3cf7e19b16eb540058c64e.nq.gz
│   ├── 21ff0f56e6a6597ef122b995a86e98e80b804250.nq.gz
│   ├── 230a01fe07a0914a4813b625e12e7b45ca91370d.nq.gz
│   ├── 2771ebc0df6aa2690fd1ca947ccb0cecb14e2002.nq.gz
│   ├── 2a42179a3686b20e0b757d6cd52e02967d9dff69.nq.gz
│   ├── 2bbb64b9dcc9c5d73d83e2e8c6827c1ca3d51cfc.nq.gz
│   ├── 2c7b66e4d481e6f6e75d3bc70d994a7ed310284e.nq.gz
│   ├── 2fee79d38a633ff84a0b8108a4b901a5536edae4.nq.gz
│   ├── 30e03001a3481f34e09a405435b91612126a215a.nq.gz
│   ├── 3303549aa217b808187502641a4989b06e6a457a.nq.gz
│   ├── 3604b291757479442680447213a7943b6b3bff62.nq.gz
│   ├── 389de5867faaa9139d7b98e0b1aede02f417b83c.nq.gz
│   ├── 3da155fd48073144de741eb31b9836bcccac83b9.nq.gz
│   ├── 41cf9c8b6c22ceb383246a5578d63d69ab2005d1.nq.gz
│   ├── 43a79db715dce84a2416c591434805fe5b043018.nq.gz
│   ├── 44b303f60f19ecec1deef8f7defe5aee1fcc149e.nq.gz
│   ├── 451333367244f29b6c1d8490c9ed496c04331a03.nq.gz
│   ├── 4624973ccdc6bba63c7eaf85201fc1acfbc452fb.nq.gz
│   ├── 4699a15d3bec9963077365265cf1212daddfc24a.nq.gz
│   ├── 47932684dc84b35e7b20a21e06b3f0ae4e04820f.nq.gz
│   ├── 4b43d74f26951cf069ce8943f0209246e782289a.nq.gz
│   ├── 4ba52c7785c94ee67e5d8af129a1193b82264857.nq.gz
│   ├── 50e0698a3f3b3550f3cdea27ed768aeae9fa9def.nq.gz
│   ├── 511aa65a2abf17bf39522c90e5d0fd862f7dfc03.nq.gz
│   ├── 582e70d40237d9907b256c9a2cfb6404bb5a5191.nq.gz
│   ├── 59c55642168e432cb6203972e2037cf90a636dd9.nq.gz
│   ├── 5fbdd9fcdfc233076be18f95ae60cec91ed9bf4e.nq.gz
│   ├── 61bc24699eedf83b3a701f7b03cbbd995ebda7f0.nq.gz
│   ├── 63a4e9e9d718d8a67d3520072e07f10ef04cc3a2.nq.gz
│   ├── 645e98a57444ee7582d3af368d6bea41e0abfa7c.nq.gz
│   ├── 6a66aea5eafe0ca6a688840c47219556c552488e.nq.gz
│   ├── 6c9336f31cb8081a9b8801577e8ae73e6117a41e.nq.gz
│   ├── 6c991121e72d5d222984ca38cc52db6e6b2ad73b.nq.gz
│   ├── 6cff23584889adcf9d21cbb3abfc8826a006bb72.nq.gz
│   ├── 6d092c629a24869ea71dfbbedea8c25bd63e6f26.nq.gz
│   ├── 6e601df82e3060f8931a27f472b70bbdec8677b7.nq.gz
│   ├── 71232aab13fb5ed85f4a11c5b184dbbd71be78c9.nq.gz
│   ├── 71f0dd97a824845d3e2030821ea6476f9b05d1b7.nq.gz
│   ├── 751521754472f6cb092c66795c3fcff0c5b61c0f.nq.gz
│   ├── 764fc5bc6a855c9f2b2149bfb22d4eef2233ffa9.nq.gz
│   ├── 7760a4483cd329303dd05dd88a444218d6224149.nq.gz
│   ├── 78fcd55f740d9a71fb848f4272dc43c6e7b71064.nq.gz
│   ├── 7997b194248b43705dca897ed5e6b1a2f7132d90.nq.gz
│   ├── 79ad2ccf748036af2ee04473f66d687133bb43f0.nq.gz
│   ├── 7af9dbb23a7431ed815a683293c5d4ffee9fa1d4.nq.gz
│   ├── 7d0b75bf46415292b6389af461bf35d446520816.nq.gz
│   ├── 839db889f0c5faa9783dde231056eaef9ed77558.nq.gz
│   ├── 83dfe71e07173c98c0eaf232b6688cedd204c6df.nq.gz
│   ├── 85074a20251d43ce9e0f0346fc30070a2c69291d.nq.gz
│   ├── 867d0ab069c9c209fb5451377d0a5ddcd2cdaf51.nq.gz
│   ├── 8a05133e90254a95811cd20b56fbf9c0230c9e9b.nq.gz
│   ├── 8b2f097d535398642b8531fb984c9c3937a99922.nq.gz
│   ├── 8b7b9e9fa2553334a335e52ab8c90e6a4cdbcadc.nq.gz
│   ├── 8cd80b1c03c634cab912f143d0d12dbcfc64dd3e.nq.gz
│   ├── 8f8b8dbc488e419b4bdb7dce4c6d02b72f463e16.nq.gz
│   ├── 924657fb31687bc977996e025293fe30ddd465dd.nq.gz
│   ├── 95b8db3809b520e98b23b6cfff18e45e47a3d19a.nq.gz
│   ├── 95c077c0473749f2bd81b0644d05515fb1b85e17.nq.gz
│   ├── 96c9f788d9c78b12a609f50eba5b6e59bacc1bac.nq.gz
│   ├── 990ff1888de6aa1fb97684cd4710986f1921130e.nq.gz
│   ├── 9b5997feed321ba5ea1b3ba595f6b95c3aad46d6.nq.gz
│   ├── 9c9b4d584c49f0830536ea8564014787457e3f2d.nq.gz
│   ├── 9d3030a68bc3bb56dc94e565dd579c77f8f08ead.nq.gz
│   ├── 9e192330d30e6da2add238938a749ef2166be287.nq.gz
│   ├── a2d1fd9a4777ed3f498ddd3aa6470a1fb8785736.nq.gz
│   ├── a439da36a34ee80ba06625c29c7c5fe15f84c4f9.nq.gz
│   ├── a63213b1901c2273a615c4af8f084f3b80de8d52.nq.gz
│   ├── a7f8546692b26edd03a79cce8821a6d84f15c654.nq.gz
│   ├── a9bd32aef6df4968a2740fc1b8b85abc4fa50d18.nq.gz
│   ├── a9ca000f511876f976b2c53a1a41017816110a96.nq.gz
│   ├── ac9da32112a1ae377a4be7eb3824cb12ad159845.nq.gz
│   ├── ae02aa6e8e700a5944a9163bc9083b594f259aa8.nq.gz
│   ├── af8857124cd8b9e8c382c3772c84c96a6d844e1c.nq.gz
│   ├── b0606beb31dd7b30f6741d7009496ffc9853ac3d.nq.gz
│   ├── b15cabc871d8e2de56961ee15d72d8137c8dd887.nq.gz
│   ├── b6816a56e0bfbf1ad3675ba60d98dceccf737677.nq.gz
│   ├── b73f7041d14f18faf47bcda37a577584af1dfeef.nq.gz
│   ├── b8ddbc99d4bb8549be0ce90714f5b50ae7a977a5.nq.gz
│   ├── b8ff4699d1548cc544ea32e4f878a2525fecbfb6.nq.gz
│   ├── c27b3b986d8b8169102dde85e0706f7b05115bee.nq.gz
│   ├── c30069673092bade5d465f92cc3101a0eb074125.nq.gz
│   ├── c4c251490da7c49de4dfda578f887ffe0385c75b.nq.gz
│   ├── c9480bf2f010790dfef754ec47da143de64563db.nq.gz
│   ├── d2cec734b1c1b140b01be2ad8872163c99d43702.nq.gz
│   ├── d2d935bd4f72bad5f9492aed5000f21e367cb0a5.nq.gz
│   ├── d9a33577e0c80c4d52b393d9ddb10963f7626fde.nq.gz
│   ├── dbe9b406ddaa15e6919c36c56966a20f30dc4d0f.nq.gz
│   ├── dd2ba4b0e846de1ae7d2c5abf82daff03a319afb.nq.gz
│   ├── e2716e50629ed13126a636f374eaffb165fbf4a0.nq.gz
│   ├── e4f17536a5802d2b43a9b33c5c55fceb327c41ef.nq.gz
│   ├── e7d612aeb746f9237ffe93279b186edce70b5770.nq.gz
│   ├── e8687363defc502c17cdb97660b7c4ac886d799d.nq.gz
│   ├── ec91857d742bf5b11e18a96cc2a45738ca4051f2.nq.gz
│   ├── f029a3c396dfb33dbb0fdbe981d8a20be5eaed68.nq.gz
│   ├── f0bcce58c1589b8d17d785e2e41631598cf3bfb1.nq.gz
│   ├── f436521fec3ce8d417bd368b06456f47dc5b8991.nq.gz
│   ├── f43c67ac2d8d629ba9b028f858676ab0d0cbcc8e.nq.gz
│   ├── f56d87b12e79985eb23ead91b231a1b26d0561a4.nq.gz
│   ├── f7e4e33a7aa139d19bfa0ef7870e469a0c3e9d1b.nq.gz
│   ├── f7f17fcb672eec9ffbf6391b7c62981cdaa94e48.nq.gz
│   ├── f9d17a3b99ea558cd228dae90ac9ddf602b76e94.nq.gz
│   └── fd2d5482dba017f94fc9e069d7390155c96b6b98.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8d7f1f783b11f9a00f5bcdfcae17f5ac8f22512e.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 123 files
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

[twitchyliquid64/golang-asm](https://github.com/twitchyliquid64/golang-asm)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
