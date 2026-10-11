# Repolex Knowledge Graph of pydantic/httpx2

RDF knowledge graph data for [pydantic/httpx2](https://github.com/pydantic/httpx2), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/httpx2
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0286b404fb72391c615e2f8d1b48b35eee76c297
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0286b404fb72391c615e2f8d1b48b35eee76c297
│           └── chunk-001.nq.gz
└── blob
    ├── 0000f39bab8e8ec6646fa38318a1707626f7ede4.nq.gz
    ├── 003675d0748dac5584af60f8d1eea0d51fc7ef8b.nq.gz
    ├── 004c311c0f89b18f4b471035122e0ccdc84ef36c.nq.gz
    ├── 008d295d4edd0db730e2eb115b70d01d56a057ff.nq.gz
    ├── 00ece19ffb459324d64e1a7d8382e39dfa153f71.nq.gz
    ├── 015c58af79ceeaaa78345b5fd0a59bb62313f7b7.nq.gz
    ├── 0272f36d992d70cfce9b278109353222b7e29434.nq.gz
    ├── 0635b2195b6bfcd48401de12dc27d649eb0c656d.nq.gz
    ├── 064c25a64559e688ade1467cd70446bd1923f237.nq.gz
    ├── 06945bd5d66df55000cc9e32735b18f1c8cf9b50.nq.gz
    ├── 06f1aafb89dd35c69a670a9c1116bd01e11d6116.nq.gz
    ├── 09ef9d1db4f02d9bc803d32a62f691fc3ad0eddc.nq.gz
    ├── 0ae2720bbc2caef7d238557758295f7b1c3f9d07.nq.gz
    ├── 0b957f720d316b979b1f30d346f2e3d4831c8ee1.nq.gz
    ├── 0c0971c92479f634872de097e4b192ed8501fed6.nq.gz
    ├── 0dee968c8867240708a8b28441a77ad05920cdce.nq.gz
    ├── 0e66bd1ea2366aea4c8ebeb857e7e5a30f093342.nq.gz
    ├── 111e2cf436aa566fd5818c2d36307032a267eed6.nq.gz
    ├── 11b9a5d4eebc8db1dbecbadc1f49bfda0c346231.nq.gz
    ├── 1203aabee98a01165c86943fe9a4b4b6244eb846.nq.gz
    ├── 1325c7341e44a9508220d392e5b4a662cbec4c5b.nq.gz
    ├── 13b51406e9059b65abe673789e7711fe8cc67b1c.nq.gz
    ├── 13f7bf1ca63c18b1af060ed2a8cb2fa237379d3d.nq.gz
    ├── 14312095b38a9e6d9faa3b9c4df0106acc853fed.nq.gz
    ├── 14ad0299075d50d582186914856a4bfc152f7c7f.nq.gz
    ├── 16c270e892f3954b62c154baa2f0cba8ee3bf020.nq.gz
    ├── 17d48c4f93d5546b39d82d12739876b619e1035d.nq.gz
    ├── 18967b8a061fa9bfd4a6fe6e9a0602226a404453.nq.gz
    ├── 1ce9cb05f629aa36b395e60e9384161f426c6cde.nq.gz
    ├── 1dd71f7211a7bb5c3c202cd05e4be8886d042258.nq.gz
    ├── 1e9bcbb3f0071500e52b6f052eb9476940727e74.nq.gz
    ├── 2103d36e3416d7c000a0fd5ec26c390b8beb6e91.nq.gz
    ├── 22a8ae85bafcde1512672fc58ba00ecf675cd512.nq.gz
    ├── 2367fc0fcd5b4709db80cac5913220db866de284.nq.gz
    ├── 23b0ee02a488b0f2b49bd4199709daba331b0b03.nq.gz
    ├── 267783c4cebd7bddc15512b6518b2bfc7582c2c9.nq.gz
    ├── 283c6eabf65344a946fa788dbe9b6a904320f2d2.nq.gz
    ├── 29dafcc063b4ac1c59b269a2495b1222842c264e.nq.gz
    ├── 2abc2bc1ab7cb1923da1bb6da06379c699c88aa8.nq.gz
    ├── 2b74151b4fd0166c40e68f87149bc548018a7fdb.nq.gz
    ├── 2bc347b0dc3c1ca1922de61336090d8f634bf558.nq.gz
    ├── 2c5e398009048e5197a0bf085b5080af0c154d76.nq.gz
    ├── 2c65610579eaae8a99b7b1790185e5ed5284a7ed.nq.gz
    ├── 2fc944521fc05e2d58666b71a3c00158158bea0a.nq.gz
    ├── 30e909016a8d46633597e26bad88fc732bdfc02f.nq.gz
    ├── 315e0944fbd24eb3349915746329c7b3afa79c2e.nq.gz
    ├── 31c027e720e73356b1539886aac63a38b7454e04.nq.gz
    ├── 33f25db347c62204d0d5568b2df3379c580d501f.nq.gz
    ├── 34980557598ac51096778d67de6ffb8d2b6d1bb7.nq.gz
    ├── 34d52debd89e647ab550fa3b89aacb2344c44c4a.nq.gz
    ├── 3612868f3079fa8893c617c5d00a065ec5e8e7f1.nq.gz
    ├── 3635da6bcf4d796829f45c64b7af24f1eecd60e8.nq.gz
    ├── 3644fb7c1c4a55d5101b0f294680f6e30fab9d1a.nq.gz
    ├── 3699b55054c5ade0623a81d6e6b4f7888f96e5e1.nq.gz
    ├── 39374a9de705d8af190302e5173bc27882e5b6dd.nq.gz
    ├── 3acb2574f121ea039217b046f1e8fc124f381577.nq.gz
    ├── 3b667f50a71808c06d6b87ad53a23f3a935e03e9.nq.gz
    ├── 3c1663c055c87e1f33fc71d1b3bbdab0abb4f8fa.nq.gz
    ├── 3c283dbce76496de333883c74573aa14beba80fb.nq.gz
    ├── 3c7b45c6e6fe6ed3d9ab034cd5d0a040806ce35d.nq.gz
    ├── 3d0cac7d9d8cba7048d91d03dfeb1eddb01b8d40.nq.gz
    ├── 464d5fa58da08dad4638bf60200f7c022714c521.nq.gz
    ├── 4816b8d6bb99bc66cd9dd2c7574534b2bbb2e120.nq.gz
    ├── 49e14ccc8ddce6b1390b122f4a9cdc18cd1a41b4.nq.gz
    ├── 4a9d9bcffd9136ae6fc70000eeb4573ea2e32488.nq.gz
    ├── 4b978543c5d42b04c188b66f229d87856bf942c0.nq.gz
    ├── 4beb0cf6a71ad262c7ef75ce8dc89511391be892.nq.gz
    ├── 4f8c36fa91bed3e4f96526cb04ae339b4b37a839.nq.gz
    ├── 502529426e6e0912613a4c205460f38ffd07153f.nq.gz
    ├── 50bce83373d3f65a10e214874669521a48c63e17.nq.gz
    ├── 5353a4ba3c7a1414347e8fb9048e8409b79539ec.nq.gz
    ├── 546f974617f9fdfd4d4a4e14314cf0578b646b64.nq.gz
    ├── 54ce5428c4b86361b075ed7b6b6f5e26aa936c95.nq.gz
    ├── 5575bee704567189e6d68b1c8a708505aaa6e3e2.nq.gz
    ├── 568b9e663d36837f5b493fad93c601ab69ebc14e.nq.gz
    ├── 5a57e038da9d36e31753208ac2d226ed0eaf8e77.nq.gz
    ├── 5ac00f358ccc088973d93ca5b1a0d3066416a4db.nq.gz
    ├── 5b7ecb5f7b5a3bddc327308b15da3faa8792a6ad.nq.gz
    ├── 5bed947fde775cfca3198796e8f92c10e20f20aa.nq.gz
    ├── 5cc80cd10fc85d036955a50af07a471c2be78b00.nq.gz
    ├── 5e18a13c5c38a95e1441445f8c052791a02d94ae.nq.gz
    ├── 5e5f6b68be369230264f6bd766fb09ef7746209d.nq.gz
    ├── 5fb762746792be2a3ced76f9f1ac6e36d43ee32a.nq.gz
    ├── 6048447955400ddaed7fb4403a1e74e522c37a5f.nq.gz
    ├── 6112f3bfe17c496c71b4fadea0ef1b5bcf155b68.nq.gz
    ├── 62fd7d71ec9bbbd1016a1e67effaa5e41a83b20c.nq.gz
    ├── 64cf93b33a6319511cc1c69f503e2f8ee3faead4.nq.gz
    ├── 666b7886520063866eb8de2630b509e51d2d80fb.nq.gz
    ├── 6691a9fc09c4adac4e71e1949cf68bb0fe0eae86.nq.gz
    ├── 693b7371022d62d4d95646bac44496e97749fee0.nq.gz
    ├── 6ce30e2b1a41b056fadcb051a950176cb042c180.nq.gz
    ├── 6e5d919192afbc02540b1259aea0e042617f4788.nq.gz
    ├── 6ebb2767b58f11ed0e7900cf9386bda863de6372.nq.gz
    ├── 6f009c1353c65e14336a6212f0489dce5523e68b.nq.gz
    ├── 708eea9ae9e7be8386c872a01226c52e221fb8f4.nq.gz
    ├── 70d0931042124afa9b4635ea022b7a148b02535b.nq.gz
    ├── 71928c694e3f27eb04ced7f81cb5b7f21ead8e91.nq.gz
    ├── 72dc4ad7674544d77d5ef955eb0c54b8f91c74e4.nq.gz
    ├── 73aff9cdf41912a7351cc0b0081d546c5a0f03f7.nq.gz
    ├── 73b302db28ff9293e0055be1cdc17ccb81480452.nq.gz
    ├── 742985b9b5211beb48e3606a66f22654fd58e4cd.nq.gz
    ├── 75025cc54cbb7e9e8fe46a7423845477aadd9466.nq.gz
    ├── 75198dc34337136492e09f94155b63e56c99cedd.nq.gz
    ├── 76585ea2c77e9a6cd9599dfd135d955a8d2ee46e.nq.gz
    ├── 7a3b0a8065c15ba826e1506a6fbd0c6ed84bc7c9.nq.gz
    ├── 7aaad5b09b158377c56d609beea245d758b33176.nq.gz
    ├── 7ae1264b69b7fbcebcada25418d10443c0c3c192.nq.gz
    ├── 7c1a8587145a1ac0fa58e2cdc29b91d2c6da368c.nq.gz
    ├── 7db82d1042b1dc91ada84af68114170bbbd5895c.nq.gz
    ├── 7e2f29c292207717bb9d8627b63a2d345cd2ee76.nq.gz
    ├── 7e801baf153e700aa4fe79b585675fe003092d81.nq.gz
    ├── 7fb2c145ec68485595e6bf8c841dd42b982a355b.nq.gz
    ├── 836d5a67fb6fdd14d41f8736ffdd4dcf7dfbccc3.nq.gz
    ├── 845b25137d0266b2e16e91830fcd43db3e4f6cbd.nq.gz
    ├── 8545b0912f9ef8643e9f8caf1bf58c573c11dcc3.nq.gz
    ├── 85a5140f8a8109dda5ca34a82871162bc8f70f0b.nq.gz
    ├── 88e61a11bf877529df71203f7864af2b6a250677.nq.gz
    ├── 89e64c078fc3ff0fe338354a3ec43219286e07ec.nq.gz
    ├── 8aba629db4faf31e37de89d4265c8fed59bedc6a.nq.gz
    ├── 8ad87b39f7c15672232e13de3db7df1f2a450152.nq.gz
    ├── 8afc6a92d433ff174f3451e7a749b27e41260a0b.nq.gz
    ├── 8de6a5a2181c76d22327773967bdc451ea0928ef.nq.gz
    ├── 8e33ec7042c710cc5aedce6653e78efb366d4a56.nq.gz
    ├── 8ec045b6d625845c199c7fbe9336278b1dc5f525.nq.gz
    ├── 8ef49e0f0c22cc6629faafa56dd9d0d313c4b638.nq.gz
    ├── 8f11f6e8b1cb73616ade447adba926472f79dc2c.nq.gz
    ├── 90fa5ffacedb68cd76e92fd09a56bf9a5996f7dc.nq.gz
    ├── 9411148aa265382e9d00fc4b6f438b4fb03628fc.nq.gz
    ├── 968371e05a2e1ac3b511f22ca6f1ce05e0368192.nq.gz
    ├── 96b4d76ce039a6f0a12f350c14746e4b57066952.nq.gz
    ├── 973b626624e671847a4799d2b844638b7f05f95f.nq.gz
    ├── 9778d17cc33df3d1f9c0c4e0f69654f9f318774d.nq.gz
    ├── 9926dc1fecb0e5f43b2c2fd29b6e62287fee124f.nq.gz
    ├── 99ab3bf5a85a18cd50cd7963ab5c63be8042d98b.nq.gz
    ├── 9eba67adb251c831da9933e83c0c27771f60e62c.nq.gz
    ├── 9ecf815b3c7a73d90253917f710a71367fd9a746.nq.gz
    ├── a1a9310db35366a0c01d41c2b0dfe9a751bcebb0.nq.gz
    ├── a536f3a397e98259f769630f69b1afa718c83036.nq.gz
    ├── a54d43b75cf6af20ee36e28da6a1287fbef0eb9f.nq.gz
    ├── a6051bacaabe3ca46e2c9a8aefac1362f159e138.nq.gz
    ├── a76baf6603e8585b5687c52db7e918ce994ecc01.nq.gz
    ├── a7a4ddc20ea6d6f1bceefc06cfa018ef18282e6f.nq.gz
    ├── a7ea99713cb0d98e792bd309a85e1a51d078d13f.nq.gz
    ├── a8ed55829af9f5e1af05a3d72158ef6549e3ceb5.nq.gz
    ├── a99677eb60128916995a6908dc404a2f52718670.nq.gz
    ├── aa48c9a7fc3852e1db3ec1ee4f1a5dd6167910c7.nq.gz
    ├── ac86390a76c7814178ca9ec6675d46e1b6196a77.nq.gz
    ├── ad7cba50d080a660bcbfd78230460e3cd56e534d.nq.gz
    ├── ae514ef9c98d16328da80cf0e3d009e95979fe0c.nq.gz
    ├── ae84d938447ac88f528d5db58df522447c3b6a3b.nq.gz
    ├── b0651d2e6594a4aad4dac677fe5879c25a363ccd.nq.gz
    ├── b3f8adee03c7ce19706a5aa0b9bad325960a2d01.nq.gz
    ├── b49a576e11190e46599eb2c10c95063c1f2240fa.nq.gz
    ├── b4aa31cb73147c9bdcfbe092ffcfb2ae507fdc68.nq.gz
    ├── b4c0e4fb38a6f1b7e00d7fa18fb42edb7ae737e4.nq.gz
    ├── b68e00d9d9f259ba71b7d4741d64c558510f5865.nq.gz
    ├── b750b8e9af95672c618b5268bef9ff92ef18869d.nq.gz
    ├── b7b566f8109a7b961a3705ae30f66edcca52f390.nq.gz
    ├── b91d608e68864ee36d74333209622cf26ded13b9.nq.gz
    ├── b95fcff3e327665194e16f7a2d5a164988409b45.nq.gz
    ├── bc57d1e22b3595cafe9423c1252fb20329016891.nq.gz
    ├── bc73e805c4d0ba71630fccce284f26d6a25b3325.nq.gz
    ├── bef44d200d10773c693fe854bb3834fab1d3e21f.nq.gz
    ├── c259393f0bc07c6646833254dbdf41e920d4441c.nq.gz
    ├── c2c9c5b79b0ba1af508f239d290a93b606a6fa9c.nq.gz
    ├── c3385d0c4b0266b864eabdc2c26a972900929547.nq.gz
    ├── c542edeac3b9caf1ef4f688b9a60829d3a195efc.nq.gz
    ├── c63a1d19dfc14e286135796ca4d815f179523b16.nq.gz
    ├── c7f4f228f3621bec8a0996521609a8d8c3d3e524.nq.gz
    ├── c8e4f0c9a45135867948ceed47bb15bf8c3acb98.nq.gz
    ├── c937023fda834aedf081eff63686a94779093468.nq.gz
    ├── c946c9e655d453f82cd4f11371cf5e218cd158ef.nq.gz
    ├── ca5f235a592cc1b824ab6185a548f1f66e4e9d1b.nq.gz
    ├── cbf885357463a0d3152b5023f97fd170e64d9ea9.nq.gz
    ├── cf94bf5e333243ba284452a50f29a07de6e29f60.nq.gz
    ├── cfdc1f9e2c03947d73ae13db5617ab263cf7ec12.nq.gz
    ├── d0087b19610f4610ffb5b1747749815c1a78f2ce.nq.gz
    ├── d16789664ba91eb5ab7bb4086bf355afb4588b6c.nq.gz
    ├── d418da121bcecf08ddf8ecfe0afff13a1a1ad669.nq.gz
    ├── d4eb209169ac2fd01696770acf91ea748b6a889b.nq.gz
    ├── d710782cd72cdb6ffbc8544492b77d9a76286328.nq.gz
    ├── d85a7c93d11b711fd9ed8a78a90ff5426106dc5a.nq.gz
    ├── d8bc68153d0e1bfcd86f87773c6e4518d7b9ef8b.nq.gz
    ├── da0d72dbbc80c7b0e6d730370330ea59b5b8a5c9.nq.gz
    ├── db5508fcef6094eaed7912d4185b7db318158c89.nq.gz
    ├── dc740457def06e1243fcf233dbefc0b0bf386af4.nq.gz
    ├── deb7f9cbfe5003f0a00ffc8de84c3730108ebfad.nq.gz
    ├── df2be6aa62515ff301bf8792c78c435c3224c5f5.nq.gz
    ├── df3a50000ca94be9509dca822d6945aab9331305.nq.gz
    ├── e05140c779c2cfad18edb077bc90a46a48f2a6fa.nq.gz
    ├── e102c518d3edffb5d2f39cfd19f935430e323123.nq.gz
    ├── e22ca3c3eec893d274430b3f2bf15e51588c09d6.nq.gz
    ├── e4a6d7b4fe5cebcb7e0d47a33250706633cab058.nq.gz
    ├── e53f3940a2aa9dc04e2e5dbba4f98e39695d4518.nq.gz
    ├── e5530a08901b8243663c95647398c296fd815b1c.nq.gz
    ├── e5ec013f9f9950bc1cc51d6517aa5ec197b7f917.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    └── eb6f4b60288b99f81043a0f58828c129581c415b.nq.gz

7 directories, 200 files
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

[pydantic/httpx2](https://github.com/pydantic/httpx2)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
