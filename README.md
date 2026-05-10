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
│   │   ├── 311c31321657ba657ccf63e10bc92a45a079fa2b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 54ede4d5d85a536aed5485c5213011d9ec961935
│   │   │   └── chunk-001.nq.gz
│   │   └── 9638587480b3f3c59a858ec78a9ea94103b746b8
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 311c31321657ba657ccf63e10bc92a45a079fa2b.nq.gz
│   │   ├── 54ede4d5d85a536aed5485c5213011d9ec961935.nq.gz
│   │   └── 9638587480b3f3c59a858ec78a9ea94103b746b8.nq.gz
│   └── repolex
│       ├── 54ede4d5d85a536aed5485c5213011d9ec961935
│       │   └── chunk-001.nq.gz
│       └── 9638587480b3f3c59a858ec78a9ea94103b746b8
│           └── chunk-001.nq.gz
└── blob
    ├── 000a2719516f569fe0f119501bec986778ba25d8.nq.gz
    ├── 002c5ffd807d51132f2ba68fe1c71b6140677d88.nq.gz
    ├── 00837b04b39c80d1d21e174c10bbb01cd33710a4.nq.gz
    ├── 008bff4dd0259287e80f2c1c45af58ddda0e121b.nq.gz
    ├── 00a7d38d3dbd52768d25167b8b49f03c9ecbacf7.nq.gz
    ├── 00e98a994c0a7290cf44ddeb171159c2eae01068.nq.gz
    ├── 011c16119522ad56b221a161174a444f19d4d48e.nq.gz
    ├── 017d42ff1053da5612fae1343188ec3350c1afc0.nq.gz
    ├── 0213631ea25bc1cff82839c487d954ae20da95b5.nq.gz
    ├── 0233f063b9f19a515563b57449d1cd7dff354191.nq.gz
    ├── 02830122cae3c67082aa703252bfd796f64be9a8.nq.gz
    ├── 02d000748fadd4c8fa7314e72a76fe8fbc1a9481.nq.gz
    ├── 02e16bd0318a20aece70528a7143ef1e4f0e7580.nq.gz
    ├── 030129da2b66124146ef5a4a81bd34ecd1521329.nq.gz
    ├── 031b7a354099882d0f52139f60be62112982dd43.nq.gz
    ├── 0328754fc8aaa851013253502030977171c7714e.nq.gz
    ├── 033efdc3f7e443780dd0ba5e948cf64a065d9960.nq.gz
    ├── 03663ae1b63675640daade062c7dde67284eab02.nq.gz
    ├── 03b3e18afb00b3a6c1c7509da5c51c70ef345bc8.nq.gz
    ├── 03b9146ba694ed73134bdbed3b3296051de7daed.nq.gz
    ├── 03e3dbfa4516170c80779b5eace2a6fc548e8373.nq.gz
    ├── 041722c366a5365da4169d35a4593daba73868d4.nq.gz
    ├── 044f134580b21f4f8bf69d30d8cce01cc2c143dd.nq.gz
    ├── 045216721ce2041d69a71310c095f72673604704.nq.gz
    ├── 048d5f23925383d026819b4bb28dfebc17af5bb9.nq.gz
    ├── 04abd59175a3678e0eb54523dcdd59da85882516.nq.gz
    ├── 04b8e1b29786d175cdb711858b9a2fc0545c60ff.nq.gz
    ├── 05e15dc090f35e541a10c76458f5b2b5b6fa4ccd.nq.gz
    ├── 05fa1042563842bfc464cb29e7bdb7a5531f0720.nq.gz
    ├── 06455c39b5ef8ff789f14374d44a26df00b0668c.nq.gz
    ├── 06bb78c5cecbb575886d4c2e50a46f5af94d1ea3.nq.gz
    ├── 06dd34ba9ef067f4d39d26943f53b05d22ff9af3.nq.gz
    ├── 0701cf1fd1374cba35d382345d91c130747c1901.nq.gz
    ├── 0739dd312e93c36b6af59e82a8b1f41b7f8c2bf4.nq.gz
    ├── 078051c783d6182b0d785819ab3d1a4783e89805.nq.gz
    ├── 096f83d38a69fe246064da4cb67ba195b8e68534.nq.gz
    ├── 09cf1ad534429930900c33954ea090868e19fc93.nq.gz
    ├── 09f1be8954ca0eb43c3b3287e380735b5805cf71.nq.gz
    ├── 0a0a02005dc113bb86e4585afc909b0e68be2c9d.nq.gz
    ├── 0ab6648d813dcda0ec04d2c781b12012c11df958.nq.gz
    ├── 0acc30563265197d2fd593f3bae360bb17a1e319.nq.gz
    ├── 0ba2e10c8b0dacfa7044037599ebbd30ca64be6c.nq.gz
    ├── 0bd420863ee0fbecfdf298df5845e4ac3d45e084.nq.gz
    ├── 0be7c0bc565777f40592c6a526b5c30d68cad6f7.nq.gz
    ├── 0c2ff87641425dbfcb9c1d88a3c1f2c676e3f162.nq.gz
    ├── 0c8e74f7ada5343420b538128687aa3d89ccdf42.nq.gz
    ├── 0c9f5f42d3f1b2e8f91e0e8d1393c26c4fc28b32.nq.gz
    ├── 0cd6e7fdc52ed56b2a63776f33a2cd36ef7277ed.nq.gz
    ├── 0dac3d4c782f073e32160e3b41b57ac7100289aa.nq.gz
    ├── 0e70287d3e8b661b5ca62986ae1fe0cf6177a2d3.nq.gz
    ├── 0ea4e165accb7c1b31e52d18d63069f356881b7e.nq.gz
    ├── 0f510d537976b5f9c0be155a1625315eb2147628.nq.gz
    ├── 0f92bc47aa12aa507e32cdc063fd262a7a76f3c0.nq.gz
    ├── 0fa601260ad5a3ef48d5cb7e965a8f1a6e1b5c03.nq.gz
    ├── 0fb03ad8920029fee14ea1a00ebd0cc024c4a32d.nq.gz
    ├── 0fc9bc0797b04ee094f26f1d6049735be987b982.nq.gz
    ├── 0fe37188e13e0318a2f0aed75b35c82a3d833f39.nq.gz
    ├── 103d663605ad7ffc6f7e91b69bcd83dd9a30ec59.nq.gz
    ├── 10467cb7d6b72a9bce916e4ae4693ff8b18ffb68.nq.gz
    ├── 11427aca6a8d78df57ccb8b3410d177be9209b32.nq.gz
    ├── 11c96821194037ddb105c6100915364b4c455464.nq.gz
    ├── 12071de92227989937840dd6df9f4dbad3c0cdf5.nq.gz
    ├── 120a44b58885de8c1c3a784679f28aa532fcbd6a.nq.gz
    ├── 12525ec9e65274a267da94eed8f4f632e61290b9.nq.gz
    ├── 12b54084d4320c459869fdf126c2ada42f824282.nq.gz
    ├── 12fab82c9999a79f08e7f5ef6618cea285aa653b.nq.gz
    ├── 133c2095e43452b001ea60191a9ae4525fecbb02.nq.gz
    ├── 138aa92adf5519cb21a5c4481aec9d3a953d0447.nq.gz
    ├── 1394fd04a6229003fda7777e837f1bc11d4b3860.nq.gz
    ├── 13e1a94a3e9b82d00612838c3d07a897d5dfb2a2.nq.gz
    ├── 14436445037e53f9c2e50fdad438ff06fe4190e1.nq.gz
    ├── 144459a4290baf7c0ffcc36399ec816fc5253950.nq.gz
    ├── 14481c0a1ed490459a035b61d1b3091ef2edd6da.nq.gz
    ├── 148b192b34d6db857e86730cf6b6c366cbd5499a.nq.gz
    ├── 14ae02caaeb08b1f8a4346ea7adf11292a55ccf8.nq.gz
    ├── 14cdd8a45fde120ef24551459b582e844926aa0c.nq.gz
    ├── 1532082d57cd4ec0cf3a389b2e63499a323946af.nq.gz
    ├── 15351767e08bbcaf75b44f38488133cfd457ca5c.nq.gz
    ├── 153ce16b4876f0f4458ff57165bf9704f7773f93.nq.gz
    ├── 1540941f2f13b53f1cacff0b1b1beae4ab14fede.nq.gz
    ├── 15557c107f99823c622d1fc31b5c72f254cd144e.nq.gz
    ├── 15577c6969147b424685c54531d2fc777c9f8850.nq.gz
    ├── 156334a356e3a7416a7fed1a85e302e9834ba33b.nq.gz
    ├── 15ae35ba069597f9a3d6e1dbba5386a1acc998a3.nq.gz
    ├── 15cd2f75117102a4b0e0aa72868b56eadec006be.nq.gz
    ├── 16034a50967b7541a3536ab17458a4885acf8913.nq.gz
    ├── 1617f5ce4fe6a5d27f9651413793a7a16adbe491.nq.gz
    ├── 1624740e6c33453e0de5865d7a303e518ae74a6a.nq.gz
    ├── 1649325482192c710763725c3f46852c047d6b73.nq.gz
    ├── 164e24ec360b14993f2942fed286f6a74930cd2f.nq.gz
    ├── 16921814c1df725203ae265ba23e8136476c6f8f.nq.gz
    ├── 170d8276892a639cfd04a0cdb30cbdd4986b7fd2.nq.gz
    ├── 17b6316971856945c7da9868f5ecc952630a23dc.nq.gz
    ├── 185b2363b34c32688ca7f706246a77e7ad150b6c.nq.gz
    ├── 18cdd8ccc801429966d49d391520ecf576e96862.nq.gz
    ├── 19283fdc3168465bd70d83f74647c97e93fd1310.nq.gz
    ├── 193044d7806e72c50d7e4cba35da3ad993b6def7.nq.gz
    ├── 19bcff148931a76d8312e7f4b587a034fb7d4f68.nq.gz
    ├── 19f2d99086986e3d851fa3fa96de9c242f2c521d.nq.gz
    ├── 19ff5e153823f9362451266ba66eff6c117327b6.nq.gz
    ├── 1a0f15139e989f0c6a68acad7026998ad1773550.nq.gz
    ├── 1a49b958ef2690a9ad71136daa30912a607930fc.nq.gz
    ├── 1a831efa1b5ca209cfd8836f3d2299584a4df30e.nq.gz
    ├── 1a8d7aff79903703c24874a167550216837dca56.nq.gz
    ├── 1ac2ba54a1ac6a65c974061553304f7ce8012e90.nq.gz
    ├── 1b9862879f98bf87cc6a78e4250b0daad9c228f4.nq.gz
    ├── 1bfb4a0adf386ae277418413d85f2949025c4b26.nq.gz
    ├── 1bfe26ce09c40224d8a510988339233fc7f70275.nq.gz
    ├── 1c2625d7147f78be3f2f4fc2455ec2341dcb22a4.nq.gz
    ├── 1c37fa40ff763b51d1cc58e02fdee1de399c6450.nq.gz
    ├── 1c527f2de4f9bea9c00a4eacbb4e16eddaddbdd9.nq.gz
    ├── 1c7261c6ff45d6bdd572e53542bf07e91cf4ad95.nq.gz
    ├── 1c98aa4d26058e89f1be3d7f136842e83dcc6984.nq.gz
    ├── 1cfee3681d2d420d42fd6b8307ceeeefb889eb59.nq.gz
    ├── 1d1bba2406eb0e1977513d9d813c7e4922d77f77.nq.gz
    ├── 1d463e6f02ccde7cb80698ae98cdf3ac79e28c2c.nq.gz
    ├── 1d92734007b1b2cb0ea1259ee1423d98c75dae26.nq.gz
    ├── 1de6560a66633c31cda64af63e405bdb4f04745f.nq.gz
    ├── 1e0923a5473171e9ca3234ae346481ae8336feeb.nq.gz
    ├── 1e646cafc1e07e5e6b65f2f4870b5a62281e6c58.nq.gz
    ├── 1e95f7243b26921d90c3ca3f8c024ffa2de78b2c.nq.gz
    ├── 1ef78506feece558e3bd3c8b6fb89b5583106ea0.nq.gz
    ├── 1ef96b54f8d228db6ac4818e446dfc4477f931fe.nq.gz
    ├── 1f2a062f3ae2c7ceae2bc8d71adfe52e9b923890.nq.gz
    ├── 1f829940a0655e333e4d108d619cb6f94db3d12b.nq.gz
    ├── 1fc37f66ac2182725ed37a7ad60745b059307c81.nq.gz
    ├── 2039358e907f17c9dc464cdbd8ed1f06f90e62bb.nq.gz
    ├── 2069a19adbbe9c1ee47dea05c71eb08fc83d20f2.nq.gz
    ├── 2076b45f08f1e131b028c78939d761b9bf526bdc.nq.gz
    ├── 2086f97a7eccabd8040061bc8a432c9d27cc45b2.nq.gz
    ├── 20969a093e0d70fd6cdf56578e6c46dcd21f9064.nq.gz
    ├── 20addd20b97f1d12ada12eb16aa1afc1081af740.nq.gz
    ├── 211feb80f671b12f84d3781a4191f44219797228.nq.gz
    ├── 21358eb276380a64e5a31b67aade666cab8ccf7a.nq.gz
    ├── 2153a0b7879f219daef7376b0c9124da98de037f.nq.gz
    ├── 21992e78094f7a44174395ee701fa5c63bc815c3.nq.gz
    ├── 21cfe70dee789c2b2529bc73055430a07d4d31c6.nq.gz
    ├── 220358d1c067529bf9011d2f3e67e01e8814ed94.nq.gz
    ├── 2207b71f13302aaf10f097f9d7a30de71cd28465.nq.gz
    ├── 229b9ff7768aed36631bc96a17ae1c63b84e4f11.nq.gz
    ├── 234c4ce0d5b2a26ec6a0730f0d1580ce56f3dbe3.nq.gz
    ├── 241509d9791a260292a7515749bd5c2c8e7daa1e.nq.gz
    ├── 2437d8c3b965c814d12ca2f0b6335ec5f75e9ead.nq.gz
    ├── 24b853323442d8a73eb426771915d85c12b0bcae.nq.gz
    ├── 24fdfff2fd1e0f731f7161d927abd9c3b83718dc.nq.gz
    ├── 25279fb0ecfd50139f34c37fc7e92b2d696a2752.nq.gz
    ├── 2529218a146445b5a318e89fe9b3bf632c4f4ff9.nq.gz
    ├── 2561b4fc0e90322eb61d1ba569d0a2e6117ba1eb.nq.gz
    ├── 25b5bbe0c094d8d37882f009a4a9021a0312cf84.nq.gz
    ├── 25c44f862b94b24082f9b6be7841cf489a7981a8.nq.gz
    ├── 25e56247bb33b7e73502165f27149e5c5501af7b.nq.gz
    ├── 25e9e7e229dd33d60bc52d714f86a948883a6caa.nq.gz
    ├── 25edc5e61cf78ef05f54253332eb22fdc15e9bfd.nq.gz
    ├── 265d4a88656ab8d142d79cd6eef161e6176870dd.nq.gz
    ├── 26faecfda901c02726d1401fd2c6d3cf9a24c33f.nq.gz
    ├── 2712c160ac7b0076d51a0405bd4bb4b810da14ab.nq.gz
    ├── 271c5d4b3a86ffef14a5e75cc5c56b2a4fd92b37.nq.gz
    ├── 2769dce4b7decdd548f7c200cba4fc8d4c93ffef.nq.gz
    ├── 27c99e56eeb4bc1c885fbe06c3d6592b58ffd52f.nq.gz
    ├── 27ff409e18c3f20da54c48f5d09599cdba56c405.nq.gz
    ├── 281b62582e56a15597cdc4bd6b7c12a75fb8ceea.nq.gz
    ├── 282f93bb7503063dba122d3ec81a62ca40699ea3.nq.gz
    ├── 28662e2e6f4af0c65aa8f5a022d72b3cc49b3837.nq.gz
    ├── 290b85ae1b56e3b5ff6d01fd8131a0355dd50b3d.nq.gz
    ├── 291eb812be89f738e01ccf197567be22f48bea91.nq.gz
    ├── 296de5ef4895e177579b12e83720116afd3524e6.nq.gz
    ├── 299a7375348111f44431d4f136941cffdd1b02d5.nq.gz
    ├── 2a30d2db602e584cc07b202d3fba2b390152036c.nq.gz
    ├── 2aa9e1ad698f3a11d2a02468d963f4808c61196b.nq.gz
    ├── 2ae3f0f24af046ff9845aaa25c9bd6cef4c59430.nq.gz
    ├── 2ae9f0e6d81d933bafb6b24d02957b2f58ecd97e.nq.gz
    ├── 2b20bc540191be3076fa5ea576a8bd2648c2dba1.nq.gz
    ├── 2b2fee71e7f010dc8439c256db54f8543f1965ee.nq.gz
    ├── 2b68577b22c72dbae00b31e9ebae52d6d87a7810.nq.gz
    ├── 2b9f9e973eb5ded24a8b83f2fc6566a10c4cfb38.nq.gz
    ├── 2c11edff2c5b1d05b2190cb9b087e5a1bc2a454b.nq.gz
    ├── 2c64b0c15ea115bd5b47d38026a5a958206b0d1e.nq.gz
    ├── 2ccbb1d39d58bbc1952e3c42a689de73354b4bfb.nq.gz
    ├── 2d02b38e9544f185f59b7579d36b91d5ef945606.nq.gz
    ├── 2d0a9d6528f4b6e0979346cc8bc5cabb0a9fad3c.nq.gz
    ├── 2df77cd03dd11ce0ec27e7d5658da22639925ec4.nq.gz
    ├── 2e009b4e0018a45fda5317a66ad35f4549790f3d.nq.gz
    ├── 2e04bc3f1df63035e7e860fc7b9f5b36667e05bd.nq.gz
    ├── 2e060df78c271f9b10159681a765ab69817b0922.nq.gz
    ├── 2e92f74fb45f5073dcc46b927313d1e2de56a647.nq.gz
    ├── 2ee77e5cb2a164897adcc190e2bb082859b67790.nq.gz
    ├── 2ef1c9c701d5b8437635860051a7f18d82319d1e.nq.gz
    ├── 2f04a1652d1d8d7dece740bb3e146b6a80ca7ca5.nq.gz
    ├── 2f166cec4a5bc64abf06ce0b7e39be28fa90022b.nq.gz
    ├── 2fb5021fa864da5732322559f0fd489a35e66950.nq.gz
    ├── 3004c9c52b50c3fdfe72b4aa5df4ca3465837e6f.nq.gz
    └── 308b8529e623adf03ca9c11cb6f818c30b437062.nq.gz

11 directories, 200 files
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
*Parsed on 2026-05-10 by [repolex](https://repolex.ai)*
