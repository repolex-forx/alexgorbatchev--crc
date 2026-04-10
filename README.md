# Repolex Knowledge Graph of alexgorbatchev/crc

RDF knowledge graph data for [alexgorbatchev/crc](https://github.com/alexgorbatchev/crc), parsed by [repolex](https://repolex.ai).

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
lexq download alexgorbatchev/crc
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 538ec51e410431362ce2a8869d1dfc31e601e120
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 538ec51e410431362ce2a8869d1dfc31e601e120.nq.gz
│   └── repolex
│       └── 538ec51e410431362ce2a8869d1dfc31e601e120
│           └── chunk-001.nq.gz
├── blob
│   ├── 01787046b129518e6939876ee9033aee79d239e9.nq.gz
│   ├── 057aa7dfcd91b7c33e81dbc05051ac6299de1bd5.nq.gz
│   ├── 0838600dc3560c65b0f34100e7b9c90751001049.nq.gz
│   ├── 084cf7181a15e0b8c49a3870797de025290be8f9.nq.gz
│   ├── 08cfe2a01c81f668618a8615412055b50026b5dd.nq.gz
│   ├── 09c119007bb60a928da85ef9192f82a21ec8ee0b.nq.gz
│   ├── 0fc04870a8a957d49ae2c09879275dca3f46813e.nq.gz
│   ├── 104188daf20b0b47ea0379e23e2893498d0a4c96.nq.gz
│   ├── 10c0e44b65e26e4ed767e97ba2411c037d5cc93c.nq.gz
│   ├── 149d2967cca41256d7c04afe84628678ddda7890.nq.gz
│   ├── 1521c8b7652b1eec8ed4fe50877aae880c758ee3.nq.gz
│   ├── 1758cd0608beb2ce522d35b5014d0bc85d4dade7.nq.gz
│   ├── 17a525f8ab8795803b2ede1d69818ca72f84fae3.nq.gz
│   ├── 1a05832ff3542cc7cb847fbda5740bb6d60f0f93.nq.gz
│   ├── 1ae1564123c8637f828a16bc8cfd94fc6e541167.nq.gz
│   ├── 1b3f5bde0e03dd887c351b09418ee68e5e35235c.nq.gz
│   ├── 1ccafafc4fe3819376945b2f292dc3cae3cea108.nq.gz
│   ├── 1cd945a3bfd97ab9befff9b9e468ef791062d59b.nq.gz
│   ├── 1ce46f61507de1a9f4c9e6731eb0deea434267ae.nq.gz
│   ├── 1e219d58d24adedec17f4be65e2c77575d32aa28.nq.gz
│   ├── 1e3c7aba73f2856b73126f1490957574358e2050.nq.gz
│   ├── 1f51d144169e455d93283a79effb3aa58a3d4300.nq.gz
│   ├── 1fa129b4b1598b74a5cd18c89b47763b43f4301d.nq.gz
│   ├── 201ca9ef07ae135fce3851f6262a4bdb4f46122d.nq.gz
│   ├── 20f7c46b6d7ab5210ca28840cc949895ea4bd307.nq.gz
│   ├── 2332796ecc83e7105f5786771b1ceb6902e38569.nq.gz
│   ├── 236c9023e94fe93ca0a636e849bc37b3dfa023fd.nq.gz
│   ├── 2373b2c147992acf930758b329c6c87eaadf6761.nq.gz
│   ├── 247210843ef4dd5a2ebe85ced2f2f206432d0865.nq.gz
│   ├── 25e71cbfd9711d3fcde0de9fc595e50f746f565f.nq.gz
│   ├── 27f1d06fc1a94a33381f05093c457001b6a048d4.nq.gz
│   ├── 291b619c9eacbbf366c42af4a616916b668df1cd.nq.gz
│   ├── 2c65aeb99eb53049b9d576905c9d66236109b244.nq.gz
│   ├── 2d94dfd3e1693a81cc0c541298184c80f558dcd3.nq.gz
│   ├── 2dda4d6c527906d926fb1da7418bd163358033ba.nq.gz
│   ├── 2e713944cff483a53fe3396f0b5ff9bd43c609f8.nq.gz
│   ├── 2e9086f79867ed9719ef2daf38a8b1fb4344a1c5.nq.gz
│   ├── 2f1dbf867480f30eca065b05be45a1bf885b647d.nq.gz
│   ├── 2f2753487cb4b7e6dd2bbaadcf493c9a8b6c7c9f.nq.gz
│   ├── 309ee783fa1b2ea2da974f7a2947cfed4d1f5a69.nq.gz
│   ├── 3320bb90ab69c1dd37b37aa3466be0d5928a4a7f.nq.gz
│   ├── 3416822a66ced35b75978a9efab3da9bfeabe5d9.nq.gz
│   ├── 3cd8a0b13dc3bc9c4eecebeca04c68ba1880ef23.nq.gz
│   ├── 3ce7b3558163e41dcf554a09befb7d248e1cdc40.nq.gz
│   ├── 3d43bb36bc95c2b5b6a8b679bb9e4872bd401708.nq.gz
│   ├── 3e102edb9a9026a492d1136b7509fb2d835d9c7c.nq.gz
│   ├── 41dda1500d987ec8f8ee397875c74e21082e1fbd.nq.gz
│   ├── 42275b7cd96ac34c375e88f076335006ed06168b.nq.gz
│   ├── 4400e22f4a32039443a96c5a59fdc25de9b12a61.nq.gz
│   ├── 4a610db81bbd3fae0abab129316f1a41a7920364.nq.gz
│   ├── 4b5c9a14e153a5d653f66f1edde32446ae547564.nq.gz
│   ├── 4be348f33186f1fa7060baff1f4ba314d945c69c.nq.gz
│   ├── 4c8b9e8dd85d5d78a07314a55fb8fe68b1f4034f.nq.gz
│   ├── 530451fcaee4ae3d68632759bfa03fbafbed0010.nq.gz
│   ├── 53752db253e3b4b5e3f17633c0f358b6d7cdd166.nq.gz
│   ├── 559e51537022552dd7d1ca9fd573e59609acecb5.nq.gz
│   ├── 5610900f76e9ccc212840c915d6bbe124bb69b77.nq.gz
│   ├── 5733034e4c1f69e7816aa463bab6dee265477289.nq.gz
│   ├── 573ef3e25f6db9e2cc017ed6b817eb43df9bb1fd.nq.gz
│   ├── 5886f367d3c0ddb7761aa2b8c59ac2ff72cc82a8.nq.gz
│   ├── 589ae9899953f9e65ee1599f1e5f8f9e57d4f914.nq.gz
│   ├── 58a4538cee061f5cdc9eee36be8df62120ecb72f.nq.gz
│   ├── 5cc27ed961bad196c8f31c516a18730906b9135e.nq.gz
│   ├── 5f3e2fae3e1ba0cea0e966b289529fa6bf2e74ac.nq.gz
│   ├── 601f0fce6fd32e65ba294b7278f6c126208e23f9.nq.gz
│   ├── 62323db69cca3e882d66720748a42ce6b5db2228.nq.gz
│   ├── 63124ccc477504adc872994659867809aa8afa92.nq.gz
│   ├── 637cec14d5d894f2a373680021202c563a9529a4.nq.gz
│   ├── 6788850d3c74b672d56a88a857d6d3b18e1f0d2c.nq.gz
│   ├── 67b1cfe0b64bd4e0e8eb7646619d6854bedb1267.nq.gz
│   ├── 6809be29c93a56bb740f31dce504aa4e43cdd0d9.nq.gz
│   ├── 6830528880d27814c0793c10c35ffa35b4f203b1.nq.gz
│   ├── 69fc044eaedc9904f11f00086aaa0d113e63e4ef.nq.gz
│   ├── 6a73122b0353f3f392a7618b7cfeeff60da6d3d0.nq.gz
│   ├── 6bdc069a1e9de957cee0abe77fc2e4879aba5176.nq.gz
│   ├── 6d9586bdcbc5bb4e5fe036344c97e26abb9e7d6a.nq.gz
│   ├── 6f8213036f68a9e2a04dfc15f757bd83aad41a27.nq.gz
│   ├── 71d9edd2ef93425e2402980a09be78ab51d8790d.nq.gz
│   ├── 720ea245af90444cda9a575b94b7ab76b6b0be4e.nq.gz
│   ├── 7273bcad551779db79a086f742e89518a8a73a57.nq.gz
│   ├── 7772f1eaaacd5877c0daa1385b41d52f36ec5d05.nq.gz
│   ├── 782c1c005b0e142490a011b939e1590c0d0215c3.nq.gz
│   ├── 78baee3180b15e67c534ea6f11ea767c20a8f210.nq.gz
│   ├── 803dcc44feaedb768ebe495a05d35a3e1889cba1.nq.gz
│   ├── 81aa8590b42d6af30207d698a42f752217870c33.nq.gz
│   ├── 837a11e0873fc1cf7853f3ad5133e93d281715be.nq.gz
│   ├── 8382ba62b6ae2d92acdd73a441ebe12a8c6e6a11.nq.gz
│   ├── 83a52201792dc5cc335912bce60ebaca8e0347f1.nq.gz
│   ├── 8534af31fbb0a10ae4ffa3a834a08ce1fd24c0d9.nq.gz
│   ├── 863fafdb6b9a5e5baa68ee2ab8bbd21ddbfb9195.nq.gz
│   ├── 86f322b6dc8004c096c0a7577e4548957c7f36e1.nq.gz
│   ├── 8a20d0fb51b77bb186513c6f5d5a923a0e7d8f29.nq.gz
│   ├── 8eab0e593380e19f553d2c533f409387a2420b4e.nq.gz
│   ├── 908212f411c7b7c5f851462bd6848f1bb36d6913.nq.gz
│   ├── 91ab499aa07949e43860d28ed92b3d38ea8061ea.nq.gz
│   ├── 9290e310fea408b68e2299abfecbe7070b19bc82.nq.gz
│   ├── 93b9eb8327ffbe782d21b7c8c2471905ab494c2e.nq.gz
│   ├── 93da4a9668017f524e1d39c514d751bff7650483.nq.gz
│   ├── 94bb24cb2867ca0786f803cafb67391878698336.nq.gz
│   ├── 9599d70a8218a7bfda831f3378575bbf54c4f846.nq.gz
│   ├── 987164f9cf4bb7dcb48434637ee08dd3900f6c89.nq.gz
│   ├── 9a05499e3a2a2b8cb163c37847920cb45adcc808.nq.gz
│   ├── 9d1299fc4c7dba62971a2f801d72be4f62f7d85f.nq.gz
│   ├── 9e8925bf0539078236ed789d7aa778f8d2796e6e.nq.gz
│   ├── 9e91f15b665310054bd666a342c00ffa6d3a1436.nq.gz
│   ├── 9fde032681e37d014f1f3205f72eb0ffb9a9375b.nq.gz
│   ├── a1e89edfb6d1ca81093eaa3fcc8dfdf0fa366cdf.nq.gz
│   ├── a2b917d46fc5b1c353be98ae6c0c9ae5cff075c1.nq.gz
│   ├── a31dea531d317a16078c235f2a3d7706540470e7.nq.gz
│   ├── a6f8f4c13395a4f8192ee99bbdca0328c66dc5d7.nq.gz
│   ├── a8974fb0b0f1d409e89738e9ddeb3669299271cf.nq.gz
│   ├── abbe5376732b58c1b23d4328ba510b0fa79ee77f.nq.gz
│   ├── ad06c13777a5131f9fc1be60b1a7e1321c4f1ed9.nq.gz
│   ├── b097d8c423a0f34558188cd50971e075bd0d5a92.nq.gz
│   ├── b34c9a2ec38bf2449ff9484a952ece88ac9d1ea4.nq.gz
│   ├── b37c5538d518ad0b1a3f4152c60e1c05f651de0f.nq.gz
│   ├── b4b09c82979b7d4dbabe87bdd88312d9f3dc9889.nq.gz
│   ├── b4c10d087511e0aa1c82af677593b3bcedde9b27.nq.gz
│   ├── b6ee4fe58a2d08af7196ff2c0b9534535d025d28.nq.gz
│   ├── b8f9512b80ac44ab6586bd94066248c0db760aac.nq.gz
│   ├── bb433ae42f729083d15409a9edfa1c84ce0623df.nq.gz
│   ├── bd2edf225aeab059a367e016c4d2d2b333f7e5be.nq.gz
│   ├── c1821815bf6509a163eb5992e0947d65b4179e0a.nq.gz
│   ├── c440b491fa1bdf69ff45586933fead859b899f20.nq.gz
│   ├── c49097c5770c612dea7b71f24c1447047c23f6f4.nq.gz
│   ├── c7a06f7e11f9e249fdcfb7882a3dbd2a80e804c4.nq.gz
│   ├── c7f51ce7d63f3b9b7b8d478e53591277e0e7c039.nq.gz
│   ├── c8981c2f3aac9dfb55b54a3610a50dbc17b493a4.nq.gz
│   ├── c97bc73ef6ae2939bac49a2caee0a8dbe21b55cd.nq.gz
│   ├── cdce51dfaa66f71110b790aa58469846ca406713.nq.gz
│   ├── d06c254a7c000d03c3ff90db58931dc1d452122d.nq.gz
│   ├── d523003737d701ae66cbdba239ded05b609784b8.nq.gz
│   ├── d691999cf6df35a54166917f7bc44086f39e425e.nq.gz
│   ├── d8d1e7cd71cde6a6cc2c7d10ee13322ff4d0b645.nq.gz
│   ├── dab6da75b7b69d943721c20cba7be202669d5357.nq.gz
│   ├── db7f13adabe57b52d1dfbbf5b1b6c47c6ce6ef60.nq.gz
│   ├── dbd43486fe00210fbb900c138691c6fd78a8b48c.nq.gz
│   ├── dd4eadf2fbf612b9df0afad124b43be583b2065c.nq.gz
│   ├── de9656755b0078a69327a58cc0932a170999fa9d.nq.gz
│   ├── e29f9bb446e24304fa83d598aacc048dacf8b248.nq.gz
│   ├── e2bd6b7f1591c8afdaee8b276d69873a0e8be9f3.nq.gz
│   ├── e37e886344d1fb676d5a9f174fb7b684aa18a438.nq.gz
│   ├── e4d4353730bc34324a6ecf45dbce34036f0e393f.nq.gz
│   ├── e79ea7a5ac1dc2656662f75cd6f814c3dace65a1.nq.gz
│   ├── ec56b14a0c4933deaf4649020a517482800be040.nq.gz
│   ├── f053ebf7976e3726d11f3c03fade2170903889a5.nq.gz
│   ├── f07a5dd8ca7ff61d2ed76fb3b945d5aecda4c255.nq.gz
│   ├── f382d6bd85d0c8626000b9d3fcf405f414690395.nq.gz
│   ├── f5e98faf97ac9cf99bdb8266d5ea532f2bac8c75.nq.gz
│   ├── f80aac2912e8d0f5ee39929356267a2fb9725bc5.nq.gz
│   ├── f858767419508218a2d4a6cfdf9acea90c539875.nq.gz
│   ├── fa6b05671100f75146cd27f9e8587feb100fa0a7.nq.gz
│   └── fc239f972ed6deccb5307b4dbbd52801f3bc0653.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 538ec51e410431362ce2a8869d1dfc31e601e120.nq.gz
├── filetree
│   └── 538ec51e410431362ce2a8869d1dfc31e601e120.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 163 files
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

[alexgorbatchev/crc](https://github.com/alexgorbatchev/crc)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
