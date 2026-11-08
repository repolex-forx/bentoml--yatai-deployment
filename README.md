# Repolex Knowledge Graph of bentoml/yatai-deployment

RDF knowledge graph data for [bentoml/yatai-deployment](https://github.com/bentoml/yatai-deployment), parsed by [repolex](https://repolex.ai).

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
rlex download bentoml/yatai-deployment
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 60877e2dffcec073e6e3c6e088a3163fb7618663
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 60877e2dffcec073e6e3c6e088a3163fb7618663
│           └── chunk-001.nq.gz
└── blob
    ├── 014df30f3fed8f91fb492121e99ec92858987029.nq.gz
    ├── 02438eab918916211ead1ca5048a9d74118998d2.nq.gz
    ├── 02ab515d42816d059ca166daef7155ca5378a191.nq.gz
    ├── 06734e0ea3efd07f97f6a2bc17e642b33465a530.nq.gz
    ├── 06abb8a435a8c74bd99cdb91cf64dbe692fbdc3d.nq.gz
    ├── 09492878a0785f0828900d955f334015dee0b12f.nq.gz
    ├── 0e4888c96502995ad2a01babe84f6a287c009cc2.nq.gz
    ├── 0e8a0eb36f4ca2c939201c0d54b5d82a1ea34778.nq.gz
    ├── 0f046820f185fbaa0174e27ef29b082c80e6c89e.nq.gz
    ├── 0ffd40d19de4ffc3a52e4330753260a2f2f0ea61.nq.gz
    ├── 1004c676adae20f1b948cd8ffae187a8398350a1.nq.gz
    ├── 105f461a2e34619da293d94d7ee3164795a63144.nq.gz
    ├── 110edd17b1c657526d978ba164c93cbd1a55293c.nq.gz
    ├── 1318339eae62ddce763685f85355c967351ae54c.nq.gz
    ├── 13ea78e8d0ec7bf92f21edbb107a3881a0a970ca.nq.gz
    ├── 148765779f199e1bab25d84bd4d9cb79308fce2e.nq.gz
    ├── 157407c51921702f913f0e56aee7cfd6c610dd8b.nq.gz
    ├── 15bf993cfd37de09c120979b8669e6ca177c111c.nq.gz
    ├── 15ed917436f72815dc7fed6b57cf052721e4f9d0.nq.gz
    ├── 18a50cfc9ab63e1ddd0fae08fab3fb673edd02c4.nq.gz
    ├── 1d1321ed4f0201e7469cb18a613d75a148e2c987.nq.gz
    ├── 1da8666ed138e8800869b797f779e80ea8b54f24.nq.gz
    ├── 202624427c27d9edb2b0f153f8055299c56c858e.nq.gz
    ├── 2070ede4462f1b15d9d6130318d61f9d64889544.nq.gz
    ├── 21009f126242b20e4317e82916f36590cf4db447.nq.gz
    ├── 21137febeb8b0afdaa9dc3f88afb3c73f6071187.nq.gz
    ├── 2371dec898db3014301c1245c5c11a3be95af289.nq.gz
    ├── 243460dc4ed4b0b4f91818ea732b81f5b751f4a8.nq.gz
    ├── 24568169dde8aadd28d18625da1c249d144bc7e7.nq.gz
    ├── 25c100c70338fe65f6c21f9c7e8feea285d02595.nq.gz
    ├── 25e21e3c963f0023f8ca76d726a1526e660371f3.nq.gz
    ├── 2955d05ae1227a9e5dcc6bf6e26fe894f4991dd3.nq.gz
    ├── 29c55ecda3b47c931a8e6d0bc6c2dcc366de3d23.nq.gz
    ├── 2a8ea30f36ef637c1ec8900cd97f0518dcc6541b.nq.gz
    ├── 2b02d4792fbd5231cdbd35954eebeb781f1d41c0.nq.gz
    ├── 2b32a8972cf6cb2508c68ed6fb9deb4a9ce01987.nq.gz
    ├── 2c14b60de73201b2076fa240ef19c84472e22661.nq.gz
    ├── 2d2ecdd4180238adcc40571d19940c28dfe3ae0d.nq.gz
    ├── 311c3586585d89281546eef62133cbcc0646a7d5.nq.gz
    ├── 3266b0107e5e1187c1dc3f896f4c1991cc72048e.nq.gz
    ├── 334113505a4482c5cd83120e9873786586731e56.nq.gz
    ├── 368c6e4d64214fcf0b61857ccf141f51d43ae6d2.nq.gz
    ├── 389fd15883c153f1e28b02eeadf671b5ab74abae.nq.gz
    ├── 39774e5d71a40eab3ad040811ae0b5a3df0f4bd4.nq.gz
    ├── 3da56feb45e738ed17a3afab8b73734f83297e2c.nq.gz
    ├── 3de1b3b24835ba05cb33ba474512f24b152afae4.nq.gz
    ├── 3f638bd9c68b78e759b75e0e84a319febd36d703.nq.gz
    ├── 40d726d86264904ba15c38df6d961ccd06ec4dd1.nq.gz
    ├── 415b337a6886afe9089f1a318797c55c02a5e696.nq.gz
    ├── 418d991e13a1aad3ac8d7a723507bd59683d668b.nq.gz
    ├── 4190ec8059e2c142165c3d6d345f1867fbffa336.nq.gz
    ├── 4367f4eb726ea311a79760dc4fecbe43d937a20d.nq.gz
    ├── 4754d6e8bf2f4d65835e298ba13b8a1aa92070ea.nq.gz
    ├── 4a7236df1cfac088193bd91fbcbd182191ba28c7.nq.gz
    ├── 4a89537751395c0ba00f25a9a3bd31dbf5b1d7ab.nq.gz
    ├── 4b5853c94f580ef6b62eaa2f50ccc046a92b6e31.nq.gz
    ├── 4c36dd6e07a0abd4a2edfd1994ba655cf8ec44c1.nq.gz
    ├── 4de9be7bc9728fab4599ac7888d227e7cfe378d6.nq.gz
    ├── 4e2232fa1a9355bb899a11bf5fe1d1339e8a1f5d.nq.gz
    ├── 4f00d229d0030d57a3d7d936684c940970fdadf9.nq.gz
    ├── 50a12f6b823db0551fb4f379f69b651f87e1c93a.nq.gz
    ├── 50cd2d084eb9a897e20efb26ed6edf47518b1165.nq.gz
    ├── 51a75db47a5b3f7f585a985ae15f64c5dd912394.nq.gz
    ├── 525119555c9d3962d639dee3171a8314d2925a71.nq.gz
    ├── 52d866183c76d4c5ef9b15d68b00940e02951d08.nq.gz
    ├── 54aebb24e182d381e75bc5d96d527f8333b6ce2c.nq.gz
    ├── 54b9983d337b5bc8fbc9d2ee33e8d1dd75017b52.nq.gz
    ├── 571e50e7bf5551766105444aa5989f901e9408a5.nq.gz
    ├── 577389e22bcd41631884b2fddfa004f7f9fb2f2c.nq.gz
    ├── 5ae7faf47dc3513a4d0c171f9d556709356a4a87.nq.gz
    ├── 5afd87eb1796e3eec0c107eb45c563560d4d1992.nq.gz
    ├── 5b159d64db52a21f389159df78581924a79131bf.nq.gz
    ├── 5e04218ed56fac1c3d618bc2c62fb919b4784c1b.nq.gz
    ├── 635d46286ac312a337b9b7e6d05e9c0fe1cfe573.nq.gz
    ├── 6403332e52c838587743d032366d76c1b5995e99.nq.gz
    ├── 677d1116996517e68739eb96abea178ef8cb526f.nq.gz
    ├── 6a6055b2c32bf53ba4ac0757b2667347b7c2a3cd.nq.gz
    ├── 6c400155cfbc874a9a45ee5e8869125edeb1bb30.nq.gz
    ├── 6da200f4a4b413c24413834e0836987f2342c2cc.nq.gz
    ├── 6e33d3c3b49a9d6d405b6e74d45b72a54cfe882b.nq.gz
    ├── 6e82d533636abe514e23919bb89d5625b643b744.nq.gz
    ├── 6f3199a181697d6b2afb34db1b3f93cea2ecdd6c.nq.gz
    ├── 6f4403b84d424279539c1a106e2560fed4ac30e8.nq.gz
    ├── 71f1797279e5660e9c03a8366b97db9d82e9699b.nq.gz
    ├── 723a9bcf5ff05628be6c88d9f936d0e9578b8738.nq.gz
    ├── 731832a6ac3b6a55814601f2e86edcdec995f520.nq.gz
    ├── 738de350b71e1c37a8f91eef98ce30bd3fdc1f60.nq.gz
    ├── 792186542d05156e2c9b74236bd11db8b3485ac3.nq.gz
    ├── 79ce5e2cedf306b133231267879565c8a78d9c72.nq.gz
    ├── 7cd6025bfc4af5ff011cfa6b420e9f11aba5e84e.nq.gz
    ├── 7d660496469029fddf9ad691171ff7acaafd731f.nq.gz
    ├── 7da2f854ae0e4f8a9d47a649301760087c190a27.nq.gz
    ├── 7f03ff9fa23c0f6b1bf844e4acb8b6251fa3a61a.nq.gz
    ├── 80e1857c594f8ad0689f3a476f705f7ddfced021.nq.gz
    ├── 8498e28057c680df77a461a0a5aad5f9354744cc.nq.gz
    ├── 84f1eade6eccbbfe1c3f78983f0f85dfccaf0244.nq.gz
    ├── 84fa5ddfb5c27c2021659839f9067e4eff9f46b1.nq.gz
    ├── 8888dbdd5c1d88a36d620f2af3db1b98989e962f.nq.gz
    ├── 8b536aeee7e66e08582cc76cce722b9e3b0f1642.nq.gz
    ├── 8b8f602e4445eaa51682eadd18b5ddb1b7af01d1.nq.gz
    ├── 8bac4b453c2940cfc92d90acd518d6f6bd1b94a3.nq.gz
    ├── 8e53ae4651aee09068dd14fe3462eb618f102b6a.nq.gz
    ├── 8f8a6aef03d82ae1145fae5b5d252b96a1cd45e0.nq.gz
    ├── 8fd962b997104801ed8facc0656e11df0a13c0a9.nq.gz
    ├── 90d7c313ca10ae5581252f3d39d2f7098b5cffe9.nq.gz
    ├── 92f8979b55f4e191ecad577598222368d3114fb5.nq.gz
    ├── 931c2bb6deb24600779e5ed41763d03b85273b97.nq.gz
    ├── 93565f86efb4ceb7542f180452773a86805d12dd.nq.gz
    ├── 93d21c5c4f4060157b201b2204c61b0ae0089308.nq.gz
    ├── 95fee21c2fa05634c1e668971adf2e227f4d1b2f.nq.gz
    ├── 960ec1bbc46c0621a248c329d7e799a6bc85a82e.nq.gz
    ├── 9623b1401c52a0526043d4845e9fa97094472443.nq.gz
    ├── 97a5eed8bfaf0c01422e5bf9e15dd837a88dca69.nq.gz
    ├── 97dfaa86e2a4b9bcd50a161f6e13102f5773572f.nq.gz
    ├── 9ac9e700b4e9318057af82c0a4976ac91244e410.nq.gz
    ├── 9acaf204cd0a2c3abdb4fcc8cb786c3899545205.nq.gz
    ├── 9b6b0b7fc3eaba887bafff6eb59f6a3a72a0ffa4.nq.gz
    ├── 9b89efed8afc6a4c395ea314113d3c0ca163ee90.nq.gz
    ├── a0219e4668d859f3dda4be002615faeb8293bd15.nq.gz
    ├── a226b74ce597130005dc852d3d54b3d64c18cef8.nq.gz
    ├── a538a3145176bb657b8227e64575a0ed2f1d2d24.nq.gz
    ├── a6330724eb6bf1fef89e3edd9cfda7fbc213a74e.nq.gz
    ├── a97f63874ca4f47254496296192370f798a5cb2f.nq.gz
    ├── ab4a7429917bfce89d1f931dc98386e1666d93f8.nq.gz
    ├── ab504284a2599a5858b910264dbddbf9cbf91922.nq.gz
    ├── ac625d55cad1b10e29219725720c4e6fb5ac65a8.nq.gz
    ├── aeea302536a94db32702576ab4925377f169719c.nq.gz
    ├── affbd8b541229c64e6b445ecce7d4c48df3f0bd7.nq.gz
    ├── b081135bc7acf23e572cda7d5ec98f50ef6e4354.nq.gz
    ├── b0f97ddeaeb735306c9c7577d130b46310261518.nq.gz
    ├── b5bea5f2529f342e46590e6cb792a535aaec4cf6.nq.gz
    ├── b6e0851b6ac1364c2993054805ec975356863559.nq.gz
    ├── b70dd5937ec2a9e754111f52aba0b2fc96889f83.nq.gz
    ├── b7412efca0eca88b5ed0e1eb4074a7133a2db820.nq.gz
    ├── b84580412d205b538e7b5487f88b8488e4954b02.nq.gz
    ├── b8d9d279b0b75c6531776c539d82cc4c98b72b6f.nq.gz
    ├── b9258c2fb27aca734e958b710d5e953fc5256663.nq.gz
    ├── b9428a087f5f440dc13c34ed92eaf3344adb374e.nq.gz
    ├── bc410d47cff64e6c33400fbf74cfa451b3bef1eb.nq.gz
    ├── bd48a5923c732d86705d5a1d16e371c3c5af8ae4.nq.gz
    ├── be418d0e195dd9e11563c3ceb80b3ad9067b5e62.nq.gz
    ├── be4b7800be0a8d0770e81e618e95b10d618230a9.nq.gz
    ├── be6731b841a96eeefba7bd605e99adacdf50edc3.nq.gz
    ├── bebea5a595ee6ca488a3c3a5c820edbbb02bff8a.nq.gz
    ├── bf7a0e0aecca1415afeb5b06f0e08a773008e3ac.nq.gz
    ├── bfe109f604b25b70d26dcafff965c7d882cbe06b.nq.gz
    ├── c067916918c79b718d2b495f6c599ccf49543a67.nq.gz
    ├── c19af06f96d92bcf6e4c5a704d825a130a80d988.nq.gz
    ├── c3fac980a17de7275dcb820c97cd7a9f5cefba4a.nq.gz
    ├── c4a5b7ec77c085a34ed8a68c1509027fa8cfaab1.nq.gz
    ├── c4ec26890b80cfff6c25cbc694af263c46b70cc1.nq.gz
    ├── c77047841ed8c7e2e0604e5cef596b187cfd74df.nq.gz
    ├── c9b54a69acaf503ad9dcbf08bb354da341073198.nq.gz
    ├── c9b70b549a1582eba0341ab28253c6c775bcdf22.nq.gz
    ├── c9b88d6d368262ef5ee3de94803e0ab3373d30e9.nq.gz
    ├── cba99d53cce78663959b4b8098cebe9687969bb0.nq.gz
    ├── cc806468c29911ad6288a2c807fd2bbd31074470.nq.gz
    ├── ccc6ee188bea78d004ea069aa79c4ed0afbf0acc.nq.gz
    ├── cd8933ccca947b5f2464ac42db936739a6fb63ef.nq.gz
    ├── cfe4927d5359a219e3d9ca724964b0b5ddc77d32.nq.gz
    ├── d0b51a5ab951ef58958eeac4ef888ce2d58052b5.nq.gz
    ├── d1748a9d95b635bff0722834a7b92a2550a4a063.nq.gz
    ├── d19136ae7101958bc882c833633a0b852be5178d.nq.gz
    ├── d508f85cf32267adfce8407eb59448106fa51930.nq.gz
    ├── d578a2d54989fea9c6808e7e7ab755414a735cc4.nq.gz
    ├── d812943ad0b0463a77d5f7b3e1a6f3c3f5697080.nq.gz
    ├── d9d02f6818a08971388ebf0d7cc9214c5da53333.nq.gz
    ├── da5797aae0474c4ca161607e541149a1431c5232.nq.gz
    ├── dbc7ada8c0e194fbcbdf43c7420f373b3293bb53.nq.gz
    ├── dbf1bd579c4856bb4355a60f51baf9694b647737.nq.gz
    ├── dc05508115aba5b9910ca2472958ad55b25c3f89.nq.gz
    ├── dc315b7279224b6ab77c094bd4646472482a8248.nq.gz
    ├── dc79e1451517cfb0bd7bfd385c8abe81151e3cc2.nq.gz
    ├── df630baf9f996da690f4d5cf329fe3cffa2e7579.nq.gz
    ├── e13c9ca0baf4285d92c207cec1bfff52368d98f5.nq.gz
    ├── e1ef2b3738140af8c121951a3dc9802b64b03f3e.nq.gz
    ├── e23be5262df41bf647ef6ae051a738b5fd776a80.nq.gz
    ├── e4ad3f22dea7bced35776e13aa64d899625eec56.nq.gz
    ├── e4ffe7c9c148e354f0eecadb66975bd5b297c96e.nq.gz
    ├── eb9a21840de9ad1d65907a524f83a9a8d1111ecb.nq.gz
    ├── ec5c150a9df257f152db0dbe2fbab375c1c1156b.nq.gz
    ├── ec6cfbb993c1edd737a9b53bcd1ec05492561aee.nq.gz
    ├── ec7acc0a1b79c38a0d29df0a9ef2470b2b9d4b55.nq.gz
    ├── ecacf55d1f2d696b78280c56bf755eaa4436deba.nq.gz
    ├── eccbcb19955dbb6f5ad330262113e0c67ca2e1dc.nq.gz
    ├── ed137168a1dbc962c3e057efce714960f8c5624c.nq.gz
    ├── ed8fa67252e25ff6bbc100035ea0e336ae172cc8.nq.gz
    ├── ee23c58905f0633c5b991a6e73deb6133e4f42c9.nq.gz
    ├── ee66ed4c997ca4d38f0c380ce0df986963d596ed.nq.gz
    ├── f2665e08e332440c24087184a10bbd70585d8e85.nq.gz
    ├── f3767c7fe24c970f581b3b335eec8965d0ce75bd.nq.gz
    ├── f5a3d77552ee7f92dc3721b319f633dfc22b27c6.nq.gz
    ├── f6a4b889c8da354df96cd9e7274069ff050b8d44.nq.gz
    ├── f862e5a2091962c39b1787aa4bd0759c3e0e45c2.nq.gz
    ├── f95e7f88e32c84a34a3f8849e5562b62b5db5f24.nq.gz
    ├── f99628dc183ac9ddead6d0f25a29198faafbb5d4.nq.gz
    ├── fb4fce3f263d140fba5baecde5c0d7653d4082bd.nq.gz
    └── fe5ddc2081355532110587b96ad9244d409555c0.nq.gz

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

[bentoml/yatai-deployment](https://github.com/bentoml/yatai-deployment)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
