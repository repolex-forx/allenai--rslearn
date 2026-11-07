# Repolex Knowledge Graph of allenai/rslearn

RDF knowledge graph data for [allenai/rslearn](https://github.com/allenai/rslearn), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/rslearn
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f08900abfcd514a1ec7470824541f3b2bdff73ac
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f08900abfcd514a1ec7470824541f3b2bdff73ac
│           └── chunk-001.nq.gz
└── blob
    ├── 0095fd5ec0c71e7f3ee1ca4dea1cb662ddf2c599.nq.gz
    ├── 015edf34ed8cd4de519977c5257dbb4c2763a5ac.nq.gz
    ├── 019cd73e8a0490b54eae86e83c938fed8b66cd11.nq.gz
    ├── 01af3349bca31ce155f85a095d9be96c06d46f07.nq.gz
    ├── 0211e410a268dfb4aaf48c8ca95138b9463ab389.nq.gz
    ├── 0221f81b06fe2f2397561c14335a8483e8e5f64f.nq.gz
    ├── 024f406b5801707e957985ee3053230fef611049.nq.gz
    ├── 02dd2ca60bd2861957c8c891c077a46a6abcdacd.nq.gz
    ├── 03391b870bcb21ff9920c64ae992e23d85ff7d2b.nq.gz
    ├── 03fb47795762bc507d6722c56802ebe8ffeecd55.nq.gz
    ├── 0505381f4e07cb697b6a340ea520db4edc6925c5.nq.gz
    ├── 052b1c3a64dfe8e512b38a55368ed317fe1299b7.nq.gz
    ├── 05632d106e4b6e09026bd93508a09e3815d04b16.nq.gz
    ├── 05a16c3b2bd7a0c6c5d476efc996cae48150552c.nq.gz
    ├── 068a288d736918d15b9bc13c030428ad3fb7b1a8.nq.gz
    ├── 06c11141145177543f73acfa481222125e192808.nq.gz
    ├── 07130837672cb0249977cb71dff863add6513e6b.nq.gz
    ├── 0874c55356895682e908c74e63276622208f1cc2.nq.gz
    ├── 09ba7e3d4c3851e411d7a3b30467f56e52ea6306.nq.gz
    ├── 0b199b6a48520f6b5c10b9aa21c75bcbe45ec8e0.nq.gz
    ├── 0b2b70a8268aa97b6ca22e978508f47075dadb2c.nq.gz
    ├── 0b3d5dbce1af4a622f2696f2d2fedfb9207daa68.nq.gz
    ├── 0b5cd2c12b220227cb3d4b7f01d6ddaa19aa2683.nq.gz
    ├── 0bb733e68433abb3a8f20054c776e3a74f14197b.nq.gz
    ├── 0d7179738a18f81e37327d9dc78e090e687055ab.nq.gz
    ├── 105e4f7ccc25eb31c4472495589a69ad776cdc5d.nq.gz
    ├── 13198c9d682c3e5db99abc5329b5bef5f94c6be8.nq.gz
    ├── 13b8cfa8fe19039d81d4193112af832d5462b4cc.nq.gz
    ├── 13d7a1c320dbc26779949a282e03c4d8eb08d610.nq.gz
    ├── 14c4477d0648d0c1e8cdc78c85bb8dfb1177e3b2.nq.gz
    ├── 14ecded8c585b216811611da781f773a5765da8b.nq.gz
    ├── 154be10994d412c08d12e7ec84431f8a3db8f601.nq.gz
    ├── 1583c50a46b52fd2bf0127afcfbcb203ec9b6656.nq.gz
    ├── 17fe65eb378f1192c788249e439a76b785946b84.nq.gz
    ├── 181a3094314c50b4229cbe32b33f806aec885849.nq.gz
    ├── 187443de80920ee120409b57bb55a536eb9e65df.nq.gz
    ├── 187a218baa24b5e1693235bf00fc95b4e96291ea.nq.gz
    ├── 187e56f4d606b02e2c06ed9f031b089adecdb5f9.nq.gz
    ├── 19276a130e516ccd6ad02a281615e5c66b4a8318.nq.gz
    ├── 1971e53681f566f2fb545c6a95d29f0f621ac528.nq.gz
    ├── 19a6394dc2a8b12b17a59f18e4e5187c5eee6943.nq.gz
    ├── 19e7ce27ae9274e231ddeed36a5ab6a653047c6d.nq.gz
    ├── 1a5d79b78aaaa0b67451c2d9f8e28a1e17136204.nq.gz
    ├── 1b5a537b5caf141e10383bf0e252d42f1bd3a580.nq.gz
    ├── 1b64e3415cee4324b5915548b24832eecda4b22d.nq.gz
    ├── 1caeb24b760fad504f0af2e79e7b119498a743d3.nq.gz
    ├── 1dc509eccafc2b54ebc33134320c4fe260c89f95.nq.gz
    ├── 1e234a731bf9f7dbf1024921d3d0b9e8610a62c2.nq.gz
    ├── 1f794470fb8e3cb2a5a6feb8b9589836c8c559e7.nq.gz
    ├── 1f7bd161e8d182f0f2c3c458c3120ac1bca6c175.nq.gz
    ├── 1fab4d5a173463584a1e5dba8779bbaf638c8eb8.nq.gz
    ├── 21792d71cde9d67993b8d678858c7a8c3499457c.nq.gz
    ├── 21faa590b4350f79859d68fd1ff3895d62af1505.nq.gz
    ├── 224b0e11844146d4548957b330af928b007254d6.nq.gz
    ├── 226f56c55d010184b3ce972bbd0872322c54d277.nq.gz
    ├── 22bc2f0504baa978f820266a57b77488ee13f635.nq.gz
    ├── 230a226074a8d61c6d84c5a864def6a1633d6082.nq.gz
    ├── 23328d291b63676b2ad2d3d929304d595752d26c.nq.gz
    ├── 2357543bcf0d85a34c8b4f22d3920ca122613ecc.nq.gz
    ├── 244a32bfeacb7d3abc5c385eceb7e22e5e7d4e0d.nq.gz
    ├── 246ebe9dd8c4f61fa05f92b52142ff92f0987117.nq.gz
    ├── 24e4c3040ab36fb9b3aa24b7fb494cc1fa89aa60.nq.gz
    ├── 25c9ab52d27e5db193e45f721896ec8c6871c151.nq.gz
    ├── 25d913f676f42fbb099170d5d57f4cb78ee6fdd6.nq.gz
    ├── 260abda5f7c44f223050124e809000fb989a6eb7.nq.gz
    ├── 27c6ef031baf8290578aabe5e64ae4a8012766ed.nq.gz
    ├── 27d5a538ac198213468b683784c1a7e034c83063.nq.gz
    ├── 2887ec9b50b52782765049b11e8d6aea562f6f25.nq.gz
    ├── 288d4b4ba00fa5b76d5b266cf83fc11cfcf16ad8.nq.gz
    ├── 28b411198ec77dbf18f7702b23c044f4a09c9a9b.nq.gz
    ├── 28bcb173b9f7b11c096a815d0b976e289d140edf.nq.gz
    ├── 2974bc435de11d57b910bed6da2c23b25efbc2f5.nq.gz
    ├── 297f339f0043d678465115522067bd88d3ecaf4c.nq.gz
    ├── 29a37031b18ea6fdd33083f5c61d7f44c88b4d6f.nq.gz
    ├── 29ac2d075cf8cbd87be8a5bbca9d7b77d2f1616d.nq.gz
    ├── 29c32528bbe67fe189d7d7acfe96103ae4c3afbd.nq.gz
    ├── 29f4536f351c738e8a652174041aabe9dda8b39d.nq.gz
    ├── 2a318c9213dfdb5b5820d0505d7f0e7fd03003dc.nq.gz
    ├── 2a463f99c0040fb3577f417a5e8e2332b42c0e53.nq.gz
    ├── 2a659a513518138f0e33161942bd644bbac5fb47.nq.gz
    ├── 2a9aa890c18b918752cb2289b7d16b7dc6de5592.nq.gz
    ├── 2b0e76418d417b5b4170d98a065624dd3cd46803.nq.gz
    ├── 2b44dfdac211bd9a3d2fdde49fccf6d4acdfdf8e.nq.gz
    ├── 2b532cf680be458b5e2aaeb45d2554f4e8db6b89.nq.gz
    ├── 2bd5663fbd7c9107e5091a28d0b906f4234b0ca6.nq.gz
    ├── 2cb5246e1dac522768413a593cfd864a4b8a9b0c.nq.gz
    ├── 2cd7b4bca9e0731699b66b7d4e9c2157422af641.nq.gz
    ├── 2d362c0186936c685ee19dce7882f3b74db75631.nq.gz
    ├── 2dbb3d8d9c2a055d3c7df9411be5a3d295ae525f.nq.gz
    ├── 2e6ae515b4b9b5336373faea90e579dc9206d467.nq.gz
    ├── 2f570afea459121e3839e565a1fd12e2bff39253.nq.gz
    ├── 2ff0b8a7b4c5d68a6a1c09cc70edf9b59b652f59.nq.gz
    ├── 30a50ef0c48b003cebd642a476dd89fdb0a4c3a1.nq.gz
    ├── 31c9dc4dd9e4720322f77081692ae89db671cc8b.nq.gz
    ├── 3223319d12c8e011a387977861b818345a8c9fda.nq.gz
    ├── 333ea5fe68c183e6015708bccbbfd4bc37f18699.nq.gz
    ├── 33416a0d4293018de4d8220692792b259adcd865.nq.gz
    ├── 3367ee262c34bfc1c8c32783cc83194815340fd0.nq.gz
    ├── 3380ef3dd5fdd4eb866a449a7476df9e61f582ae.nq.gz
    ├── 3385b70e3211eb7cd215c3e4cf96e943f52f97b0.nq.gz
    ├── 34c7ebcc9cc9d9cde4eebabc8fffe50729b2d637.nq.gz
    ├── 3530d18e644d5904ece054c21b74248a1141b88c.nq.gz
    ├── 36c6b5578f74ad2819c70bf7d7d2c56c262263e0.nq.gz
    ├── 37a3c4050a6d39e1484eca0b11d230515c7ffe41.nq.gz
    ├── 3823391879abf94e76f6fb3ef3c46620da7a0cf7.nq.gz
    ├── 382dfeec3c2a17c88a7fbb83f4517f9008b7ff8b.nq.gz
    ├── 38b9922cf966cfb8521fd1dd6812beb228348102.nq.gz
    ├── 3979f5e3151c3b93a1483ad499f5da7a7e21fbf2.nq.gz
    ├── 3a1f2343aaf2bba2116988d79cc1f23866e7afad.nq.gz
    ├── 3b82a86483a098f59bb94eed64feb4b8b04548c2.nq.gz
    ├── 3c00596d44f9022e729eda544fc0492bd08e12c9.nq.gz
    ├── 3c568b3d1e91148ba0e67cbb25bd9075150159bb.nq.gz
    ├── 3d9273aa61fac93b07a4cef343485926c6ca6ef3.nq.gz
    ├── 3e4a937a321e3fe35613f1ae3976279b96e12fa8.nq.gz
    ├── 3ea82d8461b8e5cd8fe9dcad6b73c3b2dc57c8ee.nq.gz
    ├── 3ed57989d89c0a112ac3bd70f1334fea9f20c68b.nq.gz
    ├── 3fa5ef38f285298cf98c491db9ac194e8e3b3a56.nq.gz
    ├── 3fa8d5f6be0510707ace6799dbf3349116a99e39.nq.gz
    ├── 3ff3f22738d56231af9ff5a3f5ce45e7fbf7561e.nq.gz
    ├── 417880f4ae8b62fab10c1dd0207f0e187ca6afa2.nq.gz
    ├── 41db910cfca76e5974ebe144e11e0b7eb8494af0.nq.gz
    ├── 422df2ac7a4ea7d3b154fe6f3fbed5bdd9247a20.nq.gz
    ├── 42d9aa7f926fa8fdb3eee775769fd8b6d1235151.nq.gz
    ├── 436b8fda22ba77c0963af7ecd3cd861c5dd0d08e.nq.gz
    ├── 43d86287200e44fbc29f3098a182140446629bb3.nq.gz
    ├── 449cd727b668d484d346b2963d4dc7f9436816a6.nq.gz
    ├── 44b4aa924167b4175a59b9a7efeb615f0ed582d5.nq.gz
    ├── 450e2eb3eff0c49f94b4e3622ff7f372a1a53dfd.nq.gz
    ├── 4690d43990f8ec89d43e7eaca14411ba446446ed.nq.gz
    ├── 477bf4b772c64dd319312ec038258129c5ad4653.nq.gz
    ├── 4871abd08c83a05cdd5cd5b89bc9cf812269fee5.nq.gz
    ├── 492afac0b31f6ef4d1e6e041ba44418d682e047b.nq.gz
    ├── 49980a3e38ebc87c832e0403d2a52b5b18a7b506.nq.gz
    ├── 49fded6cca5fb2f720b7f0c2869a3f03a83eab1c.nq.gz
    ├── 4a37e1f874854c41f4ad8aef0b89ec4e1dd7982c.nq.gz
    ├── 4a6f5e5bc62d2c7ab32d999bb4d12eacc520664a.nq.gz
    ├── 4b325a2a0898942f2ccb2beda758b429e1f1a5eb.nq.gz
    ├── 4b3d1b35ae72796491ad25b0c9dd834e698d351b.nq.gz
    ├── 4b9aa4d9071a76894f1fcd7590d72be19a55bf80.nq.gz
    ├── 4baeff94090b34e1b765ab456078ca7d10e0266e.nq.gz
    ├── 4bb64823046b566943b5f7d3752707539e5dfac5.nq.gz
    ├── 4bed7735de3dd79ea7d9af10acd480bad6cfdc9b.nq.gz
    ├── 4bef2f49b55bf6aa0a26441c6bc21cce0f6699f9.nq.gz
    ├── 4ca49c8404c0f4aceaed080f6728f11865569861.nq.gz
    ├── 4d6361172cc7a8c219ce620631a073d9cf48cd87.nq.gz
    ├── 4dae62b0bf2e44a0a9f455b62cc7c3dc5ef28b17.nq.gz
    ├── 4e7ec954bf334b7a0b16c68c236f3181663ab1d3.nq.gz
    ├── 4ec1ce000512881041eaca80c0f73f1c3c3a1523.nq.gz
    ├── 4f31b620c60e93b88c85aaad5c3be938ac86bf2a.nq.gz
    ├── 4f66668abe462153883f62923742f3fc6c163ce6.nq.gz
    ├── 4fb434c102061b2c3f7a47706e2ed22c33d7a318.nq.gz
    ├── 4fd8f3ccc380fc7d90bb368255289a4890b0360d.nq.gz
    ├── 509079c58460e35970064469bc2b3baf50e4b3a3.nq.gz
    ├── 509333f43b596f7b173246780e3014038aac420e.nq.gz
    ├── 52920e926d4019d268a0d993e7b9e9fe3fc06ca7.nq.gz
    ├── 53c7f5b9602a35947485eaec39ab9b91a3e44b10.nq.gz
    ├── 53e1c909f167963fe9352880c73621f8fe30ee4c.nq.gz
    ├── 53ec901a74d4a52ef7d6cd77b6ceb0384585a745.nq.gz
    ├── 54d43d3ea1c0b0d8d58393a2cd8a4f27d2ffab8f.nq.gz
    ├── 5500f5ffd172954a61ffb3fa98f3215ca3d97596.nq.gz
    ├── 5672802d53ae7042b72dc9d80928b01740948b1a.nq.gz
    ├── 5685597bf90f92f410e0ab928c243a35dc6461e4.nq.gz
    ├── 56c4a3a2bde3e8789033bceebd5d157036ad4e12.nq.gz
    ├── 573e1528253e2beea449384102b9f3c2017670ab.nq.gz
    ├── 57a679616a08ba8b66654e1afb3800f211904449.nq.gz
    ├── 58093113f294f741cf29dba622f6baf1e16e9aa7.nq.gz
    ├── 5827f2d99b30cb2402a129b9628f5a1e54bd485b.nq.gz
    ├── 5856b911c709ebf353903b22fe2c7ceba422c7f8.nq.gz
    ├── 589e925e87976ea2d68b9058669336b010f78157.nq.gz
    ├── 59066866d99471005dda0a6928045e21096fb059.nq.gz
    ├── 5934af22cf0eaccbb6c914388ac9da42b555a1a1.nq.gz
    ├── 5a5f728727a4613cdf3b4f8c0b3e78dcc2f8f7a2.nq.gz
    ├── 5b10a9f1a5b2dc5ffda83997be219dc06cb99bff.nq.gz
    ├── 5b3def1f29cb18e8d8b7830bb965d52e8e5d83e6.nq.gz
    ├── 5bb1f8ebabad90ce671a523831867bd33ca67fd4.nq.gz
    ├── 5beb1b4e3aedb5441ca2f2e4ad4d6e801756c8f3.nq.gz
    ├── 5c647deb29392c64263b02a6a7ac3357ac649911.nq.gz
    ├── 5c791ab8668181d7aca0e0fffc6c9438ae808498.nq.gz
    ├── 5cc7a80e97458a41762ba77fdea7c60867161912.nq.gz
    ├── 5cd62966687dd1dc143533f6a26c717b79bcf950.nq.gz
    ├── 5ddbd28ddce6294b538d14c835744645da171e8b.nq.gz
    ├── 5eb6a9d7cbb516bc4b89e104fa72737b1305681d.nq.gz
    ├── 5f4d61a8788a69475dc273959f029c9665ab2733.nq.gz
    ├── 60407fd42c0d6a688065913b263f1001f329e667.nq.gz
    ├── 60d0749783410bc67c5ca6d58b36aecd5b75c6bb.nq.gz
    ├── 615a1b66269525f0341877b8998d5a010885edf3.nq.gz
    ├── 6229d221100ab71c62a0532885857bc135915aa9.nq.gz
    ├── 623477262f40a5537456b7ad9a8a8f3eb29bbf69.nq.gz
    ├── 6278c4fb3983c8ee25d68373fe4e0495b87da5c5.nq.gz
    ├── 629c815d4f1d2cee4a938cc1eb9fd64882f3ee04.nq.gz
    ├── 62d3c063df30eaa941b20bdb74af80b26000ea2e.nq.gz
    ├── 633566c7fef60bfca4c710ecb8cafc2cbbcdfba2.nq.gz
    ├── 63e2b3b616d1735229cb9f32bc6ddf472747316d.nq.gz
    ├── 6416c99ed41db3247034e64b53a8f407633e281f.nq.gz
    ├── 663b0870a0a01a809eb439780199e2ce22f93d74.nq.gz
    ├── 6704c7dbde2734dcfe637e28f3cb1128fd19a91b.nq.gz
    ├── 678772c6e00c417d601180ea571ef090b0930458.nq.gz
    └── 68776a8b975583515757e4f8276b8585774aa1a8.nq.gz

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

[allenai/rslearn](https://github.com/allenai/rslearn)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
