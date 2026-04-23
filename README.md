# Repolex Knowledge Graph of tokio-rs/tracing

RDF knowledge graph data for [tokio-rs/tracing](https://github.com/tokio-rs/tracing), parsed by [repolex](https://repolex.ai).

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
lexq download tokio-rs/tracing
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 54ede4d5d85a536aed5485c5213011d9ec961935
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 54ede4d5d85a536aed5485c5213011d9ec961935.nq.gz
│   └── repolex
│       └── 54ede4d5d85a536aed5485c5213011d9ec961935
│           └── chunk-001.nq.gz
└── blob
    ├── 002c5ffd807d51132f2ba68fe1c71b6140677d88.nq.gz
    ├── 008bff4dd0259287e80f2c1c45af58ddda0e121b.nq.gz
    ├── 00a7d38d3dbd52768d25167b8b49f03c9ecbacf7.nq.gz
    ├── 017d42ff1053da5612fae1343188ec3350c1afc0.nq.gz
    ├── 02e16bd0318a20aece70528a7143ef1e4f0e7580.nq.gz
    ├── 030129da2b66124146ef5a4a81bd34ecd1521329.nq.gz
    ├── 031b7a354099882d0f52139f60be62112982dd43.nq.gz
    ├── 03b3e18afb00b3a6c1c7509da5c51c70ef345bc8.nq.gz
    ├── 03e3dbfa4516170c80779b5eace2a6fc548e8373.nq.gz
    ├── 045216721ce2041d69a71310c095f72673604704.nq.gz
    ├── 04abd59175a3678e0eb54523dcdd59da85882516.nq.gz
    ├── 05fa1042563842bfc464cb29e7bdb7a5531f0720.nq.gz
    ├── 06455c39b5ef8ff789f14374d44a26df00b0668c.nq.gz
    ├── 06bb78c5cecbb575886d4c2e50a46f5af94d1ea3.nq.gz
    ├── 0701cf1fd1374cba35d382345d91c130747c1901.nq.gz
    ├── 0739dd312e93c36b6af59e82a8b1f41b7f8c2bf4.nq.gz
    ├── 0ab6648d813dcda0ec04d2c781b12012c11df958.nq.gz
    ├── 0acc30563265197d2fd593f3bae360bb17a1e319.nq.gz
    ├── 0ba2e10c8b0dacfa7044037599ebbd30ca64be6c.nq.gz
    ├── 0c2ff87641425dbfcb9c1d88a3c1f2c676e3f162.nq.gz
    ├── 0cd6e7fdc52ed56b2a63776f33a2cd36ef7277ed.nq.gz
    ├── 0e70287d3e8b661b5ca62986ae1fe0cf6177a2d3.nq.gz
    ├── 0fa601260ad5a3ef48d5cb7e965a8f1a6e1b5c03.nq.gz
    ├── 14481c0a1ed490459a035b61d1b3091ef2edd6da.nq.gz
    ├── 148b192b34d6db857e86730cf6b6c366cbd5499a.nq.gz
    ├── 14ae02caaeb08b1f8a4346ea7adf11292a55ccf8.nq.gz
    ├── 14cdd8a45fde120ef24551459b582e844926aa0c.nq.gz
    ├── 1532082d57cd4ec0cf3a389b2e63499a323946af.nq.gz
    ├── 153ce16b4876f0f4458ff57165bf9704f7773f93.nq.gz
    ├── 1540941f2f13b53f1cacff0b1b1beae4ab14fede.nq.gz
    ├── 15577c6969147b424685c54531d2fc777c9f8850.nq.gz
    ├── 16034a50967b7541a3536ab17458a4885acf8913.nq.gz
    ├── 1649325482192c710763725c3f46852c047d6b73.nq.gz
    ├── 19283fdc3168465bd70d83f74647c97e93fd1310.nq.gz
    ├── 193044d7806e72c50d7e4cba35da3ad993b6def7.nq.gz
    ├── 19ff5e153823f9362451266ba66eff6c117327b6.nq.gz
    ├── 1a0f15139e989f0c6a68acad7026998ad1773550.nq.gz
    ├── 1a8d7aff79903703c24874a167550216837dca56.nq.gz
    ├── 1b9862879f98bf87cc6a78e4250b0daad9c228f4.nq.gz
    ├── 1bfe26ce09c40224d8a510988339233fc7f70275.nq.gz
    ├── 1c2625d7147f78be3f2f4fc2455ec2341dcb22a4.nq.gz
    ├── 1d463e6f02ccde7cb80698ae98cdf3ac79e28c2c.nq.gz
    ├── 1e646cafc1e07e5e6b65f2f4870b5a62281e6c58.nq.gz
    ├── 1f2a062f3ae2c7ceae2bc8d71adfe52e9b923890.nq.gz
    ├── 2039358e907f17c9dc464cdbd8ed1f06f90e62bb.nq.gz
    ├── 2069a19adbbe9c1ee47dea05c71eb08fc83d20f2.nq.gz
    ├── 2086f97a7eccabd8040061bc8a432c9d27cc45b2.nq.gz
    ├── 20969a093e0d70fd6cdf56578e6c46dcd21f9064.nq.gz
    ├── 220358d1c067529bf9011d2f3e67e01e8814ed94.nq.gz
    ├── 2207b71f13302aaf10f097f9d7a30de71cd28465.nq.gz
    ├── 241509d9791a260292a7515749bd5c2c8e7daa1e.nq.gz
    ├── 2437d8c3b965c814d12ca2f0b6335ec5f75e9ead.nq.gz
    ├── 2561b4fc0e90322eb61d1ba569d0a2e6117ba1eb.nq.gz
    ├── 25c44f862b94b24082f9b6be7841cf489a7981a8.nq.gz
    ├── 265d4a88656ab8d142d79cd6eef161e6176870dd.nq.gz
    ├── 26faecfda901c02726d1401fd2c6d3cf9a24c33f.nq.gz
    ├── 2769dce4b7decdd548f7c200cba4fc8d4c93ffef.nq.gz
    ├── 27c99e56eeb4bc1c885fbe06c3d6592b58ffd52f.nq.gz
    ├── 27ff409e18c3f20da54c48f5d09599cdba56c405.nq.gz
    ├── 282f93bb7503063dba122d3ec81a62ca40699ea3.nq.gz
    ├── 290b85ae1b56e3b5ff6d01fd8131a0355dd50b3d.nq.gz
    ├── 291eb812be89f738e01ccf197567be22f48bea91.nq.gz
    ├── 2b20bc540191be3076fa5ea576a8bd2648c2dba1.nq.gz
    ├── 2b68577b22c72dbae00b31e9ebae52d6d87a7810.nq.gz
    ├── 2d0a9d6528f4b6e0979346cc8bc5cabb0a9fad3c.nq.gz
    ├── 2df77cd03dd11ce0ec27e7d5658da22639925ec4.nq.gz
    ├── 2e04bc3f1df63035e7e860fc7b9f5b36667e05bd.nq.gz
    ├── 2ee77e5cb2a164897adcc190e2bb082859b67790.nq.gz
    ├── 2f04a1652d1d8d7dece740bb3e146b6a80ca7ca5.nq.gz
    ├── 2f166cec4a5bc64abf06ce0b7e39be28fa90022b.nq.gz
    ├── 2fb5021fa864da5732322559f0fd489a35e66950.nq.gz
    ├── 308b8529e623adf03ca9c11cb6f818c30b437062.nq.gz
    ├── 3371bed5ef1238b509d316b54ee909b6282c8780.nq.gz
    ├── 33cf03520f814446f4f5e410f18fedbd81d3cc2e.nq.gz
    ├── 3420f0b899fabc1b9ce1459258f86133453548b0.nq.gz
    ├── 3453cd1db1c17f2eb83b4a2d6cb1704e4a45b12b.nq.gz
    ├── 34f8e944f3f831a91a3a5d0a465e2bae83278a02.nq.gz
    ├── 355e3b4c3516e2df77e46ddbf9122b5dc9ecdb20.nq.gz
    ├── 37bfaf15d9157a43597832e039708e12f0c12c8d.nq.gz
    ├── 37fe0eb820ceaf98ec729e7bb390466f7d595398.nq.gz
    ├── 38041fd4b58350bf4d156ce378f44208dea33867.nq.gz
    ├── 3820692a86257b7d18a5bfc63acecc7d8de9ef79.nq.gz
    ├── 3934a13267c7c2d2bf80f7aeccf4389c46a69ae8.nq.gz
    ├── 3a0882dd277d17b2065fdfab9f84b38e05c1a242.nq.gz
    ├── 3abaa807aa292c2bb4e2c264b24581cbda08b36e.nq.gz
    ├── 3ae6d7c498fc4f870b3718024f788b96d82647f9.nq.gz
    ├── 3c32ef1691768f3f77ac95c92ace1ad2eebf5cc2.nq.gz
    ├── 3d84056d8c93bb5fa29b0eba51c40438b3fc6bbf.nq.gz
    ├── 3d8b02e5da703ddad6a3cc14bbb7bccf4e0b7bf2.nq.gz
    ├── 3ed4795751ffc5943d9484fbda404976683358d5.nq.gz
    ├── 40fd7c789c9878d3f42513509cffda709d2bfdb6.nq.gz
    ├── 41bb138edacbaf3e377d6bad89ecde69b68c232c.nq.gz
    ├── 423ed547a66d0183ac666716cdbe02bf02310c90.nq.gz
    ├── 42aa308f6b7339c3e908a50b87af291f0ed9fcd2.nq.gz
    ├── 43198645b7be8544e6e79344a9bbd1df7d1e8e23.nq.gz
    ├── 44271a8974d77b79c29e087859a6f31f68e470a9.nq.gz
    ├── 459b76b67be207977c3f2e79c8432f492eb6edc8.nq.gz
    ├── 46fcdfe08784e9dfacd635bf49eca4003b233d3f.nq.gz
    ├── 47214439f64341b5133b30f420d31d241ea2d3cb.nq.gz
    ├── 49c6e730a827dd8b19e6478a4391da4b0064b585.nq.gz
    ├── 4a5b8b7715ac8b270174860060a1eb3b4e37e67f.nq.gz
    ├── 4a5edbb3d33600189f79b5483cbac1aa0ad429a9.nq.gz
    ├── 4b19bb9734cd3560ab24f0a284938c8d3c8ac324.nq.gz
    ├── 4c05f027325506e265d8ca490e93c2c52518eb56.nq.gz
    ├── 4c1be56869f82dd81e6fa0eef6ab6510a052da1b.nq.gz
    ├── 4c6ac409d89a0dd3e062614b5c418c531bc71409.nq.gz
    ├── 4cab020c9fa814a146377b99500ed0d3f860322c.nq.gz
    ├── 4cb40452799e99f83e48e073d8bdcec2ffc0b075.nq.gz
    ├── 4dcf3b4ec0b65e427695508a402af0affa87e8d8.nq.gz
    ├── 4e1b597fb3378f6d8674a45f2c2a354d2a902cc7.nq.gz
    ├── 4f2c095da0dd1659c99ca6e5858bd1bb36901f16.nq.gz
    ├── 4f91466de79c01fb143a17e267b1acdecaec934e.nq.gz
    ├── 4fc173fa0f869e922b5317b8334b3f5c9621ffe2.nq.gz
    ├── 5081958dde34493912533352f94a6e651621d28e.nq.gz
    ├── 50d204a4bb4b93be25a484d37d31e87f22c486cf.nq.gz
    ├── 50d2f551d623cb2854900c7334bdf22fa5151c48.nq.gz
    ├── 5286e8708bf35215f85839cb8e6c80f0656a69b8.nq.gz
    ├── 535df4a4238550eb1b6ae7ac84639fe7c873474b.nq.gz
    ├── 5433d981a094c8e29688c3abf3120d1cf09edd6b.nq.gz
    ├── 543406a32238cdf043ac8515ac79771ca9b1f83d.nq.gz
    ├── 553c5371a2781b1b5fc4c2a83bae055d240ae2c4.nq.gz
    ├── 57905a7f1a8294f41b70a4ae1303192915515b7f.nq.gz
    ├── 57a0f6e3f633741bb6accd646508703c4b169fa3.nq.gz
    ├── 58caeeb5af3435f6365c5aa038dd4adea132b8c6.nq.gz
    ├── 59f5e3e16a3020f77b7785a3d31f442389714daf.nq.gz
    ├── 5ad828982601017c1ec1532a5eca8b9031b76cb2.nq.gz
    ├── 5ad9c1362ea84373a2ed06168eef79b35090ece0.nq.gz
    ├── 5b175ac868881a71878dce52ddde3768f357d3be.nq.gz
    ├── 5b461d0a0ac29345be53d0730f7c193afd59cb3d.nq.gz
    ├── 5bece32ca5425bfc40f3d141e6d8c1b7872f209a.nq.gz
    ├── 5d4dc6a857ec0f4d207144da125764dba0a0e834.nq.gz
    ├── 5e41ef92f09ae55fc578b4c2c7b772ad91195e18.nq.gz
    ├── 5e5f9f18bcbcf5671860749e68b3b9793f9818ff.nq.gz
    ├── 5e6df6f9e00bc147fa60fdbe90230fd99fd8ff78.nq.gz
    ├── 5eb231b4371b9b994f21b0672d8c23deaea9b324.nq.gz
    ├── 5ff4eecf02e0823f426f02225aa68017c2a4e087.nq.gz
    ├── 609007ccebf2b3418d7f6203cdb5d260dadcf94b.nq.gz
    ├── 61ea4ac456bc44167b3368ab58bc1ad8c12eeae8.nq.gz
    ├── 6266b475eed7391cb586ed5d588a2cc295d27a15.nq.gz
    ├── 65379c1fd22171d227d65736799c0c2b91fa64a0.nq.gz
    ├── 66ea74a3fe50397c447a5b5e26fecda6cb94639f.nq.gz
    ├── 69230f001315d322a7d11ad31670e9323da78dd1.nq.gz
    ├── 69544f9f3b34b3e6c44f4c07e5af1a6154659d0f.nq.gz
    ├── 6a3e05d4a2181b161632e052ee20dc7a6aeecf74.nq.gz
    ├── 6a48f255a9a32d63529b8fd408faa0f6bf56473f.nq.gz
    ├── 6b1055d962ff5ee82ed9589cd8a5dbfec542558e.nq.gz
    ├── 6b24dab10f3f64bce18ad6ff565f47e68896d949.nq.gz
    ├── 6e254376299ac2ac9f2750c9dd596a444179d0fe.nq.gz
    ├── 6f916b6d43dc17a365369b7f2d14dd86a1428341.nq.gz
    ├── 70dba6542f148fa2d375191556a77a7a7cf0eb2e.nq.gz
    ├── 7124572d6240a6220b3803f5ae3cb9731c6f9353.nq.gz
    ├── 71692fd9e9379be1495596c4a972f4d325606a2b.nq.gz
    ├── 71b67f851f435c0fc4e9c8fb1cb5508111c412d3.nq.gz
    ├── 724f2bfa82c0ac66c561906bca44294fa577f9c1.nq.gz
    ├── 729ebc67b4cd40c007dac4f3c398e2bdc96149ca.nq.gz
    ├── 739cbae720ddbc47cd2139d106541dfb01914be0.nq.gz
    ├── 74aa8a14c4da2b5dc1e80de65d69c21c6e7edb00.nq.gz
    ├── 757350a53976cf0795bfef9887dc123b40fac5aa.nq.gz
    ├── 7642e6552c4a825855622cd2dd701b9707d32a97.nq.gz
    ├── 76db79f3ae6b34d2c2f5f892667ee4af7bc9da09.nq.gz
    ├── 776f4269eecda89af3239818e102c7ae66ac2a01.nq.gz
    ├── 7827f5043ecb22ada333d1b3a31aa896ba65340d.nq.gz
    ├── 78a039ce174bc0049186feb09a86843624b0210b.nq.gz
    ├── 790dcc62c6955ec037d8300148a3674067e4f4da.nq.gz
    ├── 79bf64c5ef4188baaa9268ec49a91fb9d771ce53.nq.gz
    ├── 7bcb75e985e303ab39eaded37ff4f38743157ac3.nq.gz
    ├── 7c671e8469d889cd58cf74cea63afeaa85cdc812.nq.gz
    ├── 7cc7ada0ddfcd0af95ef76ec02fc56a586fffc27.nq.gz
    ├── 7e5e058a9b3cd8b8ae8969afb851cd262bbe8fe4.nq.gz
    ├── 7ec7842772f474ce077fb1138b0e203bcef68b42.nq.gz
    ├── 806f0fbda460b38bd68f1c4d1155f210a945d5c6.nq.gz
    ├── 80b0768e0cc7e790db956347a0ce44b53cc893f5.nq.gz
    ├── 817e30fef0a9f702d80c23f79edfda87f7e20264.nq.gz
    ├── 84d5f4d7aff4675d822d01470c01e150465a72bf.nq.gz
    ├── 8560f98586ee817df249652d6a07a2f45a2dc991.nq.gz
    ├── 862d877428a00ad21332f740364e2e03e74fe2d3.nq.gz
    ├── 867fdd07179774f364dc28e5f7026cc145928e49.nq.gz
    ├── 869c842fac20676b6dcf0b6a71580d2fb3ec3587.nq.gz
    ├── 88fc411f7e81446a483d58d167cc9e4885699f86.nq.gz
    ├── 897c9f2df563d24d37b5b526719f654a0da56fb2.nq.gz
    ├── 899df3f83fe030544c90bac98ccb47a8a378f3a9.nq.gz
    ├── 8a1ff6e0414102f321535099c96e01bac1205c56.nq.gz
    ├── 8a4b50f94610de5fecf29c3a8d5b8f74bb161f51.nq.gz
    ├── 8b48cc203b4b69aa6d6eacf72358884f43dd67b0.nq.gz
    ├── 8b78bd28041df108097b4e0c00555fcbdd700c3f.nq.gz
    ├── 8c13cc305dd7dc8690aa9d903652f5eeca387d8d.nq.gz
    ├── 8d5fc03f83f2dac487285a8197b2904531a10cfe.nq.gz
    ├── 8f67cfcbaf9b42f781063ff7572c61e0f8daa609.nq.gz
    ├── 8fb38dc0e26a08eb3c9d5412a14dfb7bfd58c8ea.nq.gz
    ├── 90192f2f027eb4e6ccdef6bb725dc8ceaf6ec118.nq.gz
    ├── 90e2f0eedfeb063edefe48f8fcec9e36d43e41ff.nq.gz
    ├── 91ab9c91d2b85152c206a3216a7e5d0dc081d3a6.nq.gz
    ├── 91ee9bdf8dea29fe59c1cd8e1c696fb20b954007.nq.gz
    ├── 92abf0bff9217a933a9004ceec6c4a6edf97dd70.nq.gz
    ├── 9306390794efba079bbb0d16003acb5772fa6415.nq.gz
    ├── 939f3a32ed0fdb571075abd059e1f34cdadd0073.nq.gz
    └── 93c14f422c2efbf79cb97e22f8f5904fb2ae7038.nq.gz

8 directories, 200 files
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

[tokio-rs/tracing](https://github.com/tokio-rs/tracing)

---
*Parsed on 2026-04-23 by [repolex](https://repolex.ai)*
