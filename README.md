# Repolex Knowledge Graph of holoviz/lumen

RDF knowledge graph data for [holoviz/lumen](https://github.com/holoviz/lumen), parsed by [repolex](https://repolex.ai).

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
rlex download holoviz/lumen
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 296c796a1438cb149fc8741b7f0d2aaf47a766ae
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 296c796a1438cb149fc8741b7f0d2aaf47a766ae
│           └── chunk-001.nq.gz
└── blob
    ├── 004f44517e5e19ef7d80fd1ae54e3c25657825a3.nq.gz
    ├── 00e5f8969bf82597bf6e96c2b00bd1015d1ee67d.nq.gz
    ├── 015c0a3ff76fda254de7ea202739e5f292d8da9c.nq.gz
    ├── 017e8596757234e3064b0c063936a2ecfb0ff2dc.nq.gz
    ├── 01cbda534d7c6b5bb067f17cdab603eebaf23e83.nq.gz
    ├── 01ec22713e45648f3eae9dc3fffffe844d52a562.nq.gz
    ├── 024d1bf3c1844ab19f4edc29d0da54d245dc2ddc.nq.gz
    ├── 0276c581a9fbf937e964bb9f8300aa5fb507fd1b.nq.gz
    ├── 05b4f522e97333428e928bcd2316164d1a348099.nq.gz
    ├── 0663e9a43e763bc8a9e98ac260d004aa7dda96f2.nq.gz
    ├── 06cbe39af980d10d27d2ab88378e6d87b41edad8.nq.gz
    ├── 06fa5ef033130c9d7d8d940eff9657e28f9e9e20.nq.gz
    ├── 0790fcc8e442cc360c0e15c5016d2642766aa10b.nq.gz
    ├── 08e70f1cdb964a3561a46e9e8addf2c87211bb50.nq.gz
    ├── 093818f16aaf211d4a7d2c0ebc6ed2eb10bc6e37.nq.gz
    ├── 09ef493f088f53014c57b0f9b1cd36003c5669de.nq.gz
    ├── 0ac97a017b5c0e4399a6b317b4ffc3c7044176cd.nq.gz
    ├── 0b95810352b4889109f0b8a639f81667ccb1652b.nq.gz
    ├── 0c3cec633d30f623ff597eb45b3d394cf6ce1269.nq.gz
    ├── 0d257a6d4adaa8981d8cc58d7dd5c55a212d1f80.nq.gz
    ├── 0d387a6041f29e554dda36d596fce4edbe722438.nq.gz
    ├── 0d9c3bb0e37303cc6f6e1f3b50db822ec895abeb.nq.gz
    ├── 0dcd8e76a868930751978f52cde67bc259956e67.nq.gz
    ├── 100bf1fb28df0753560003fc94e28f33ae2db1c6.nq.gz
    ├── 104d802477662935aa000d876d298e53be911219.nq.gz
    ├── 10564add90aba5ad79ec4393b519e9adb3302533.nq.gz
    ├── 10bfa01cbba08488a75463afe17e07fbe62d6f60.nq.gz
    ├── 10d82dbf84f60ebf9409088a0f31f76b7e043b3b.nq.gz
    ├── 11c3d822d9a69eec9f6e53599dd54c7ea1f79441.nq.gz
    ├── 12e627df0bd7219ab3bc44d38f9ce0d51c66df8c.nq.gz
    ├── 1367b08a203729f6704cb0b06e68d693e9fdf9bf.nq.gz
    ├── 137b055cb30100db6bc914c6aa4e472929d00915.nq.gz
    ├── 1473ad07a52e462221f3e4b762f0f2b1abca0b81.nq.gz
    ├── 15667a5a551d74306887c8192c203728a181c42f.nq.gz
    ├── 164cb84fdb7f5636457c0bb642ea2d8bc5a72642.nq.gz
    ├── 16c21dd9a195406d0466126ec2fb69957029e55d.nq.gz
    ├── 17bf42c480f40056813ea2ef214a5be46745cc35.nq.gz
    ├── 17f45c04b093153cec8dec7216fa6151f44a626f.nq.gz
    ├── 18a4ebe01cd7c78628c30de5b66d3d180a11e970.nq.gz
    ├── 190d8c2972cbf5cd85fe6eadd67b4698e567b18b.nq.gz
    ├── 19950ba9a942bebcb463b0b6e00aea8b577a2a21.nq.gz
    ├── 19f4b2c8c610b64fca5454d8ac06d9bcc301cc76.nq.gz
    ├── 1ae909539b3824eb830fc36b331ea5dd9fe56f83.nq.gz
    ├── 1b11a8762991b0f6ebea4fe340d62b4421d48a49.nq.gz
    ├── 1c763d7c50ff7293702542e3e74860e3f4ed8244.nq.gz
    ├── 1d2ae008337605ecd408e74b16760d59c0b6ffb2.nq.gz
    ├── 1d34c9cc43ed1e9d15a3d63c08b605f26f5d3073.nq.gz
    ├── 1f1099c3acec7b1b506e947d7ce62ed8bdce37a7.nq.gz
    ├── 1f2b55d0697fcaf9de24aa74ba53a1da36bf67fc.nq.gz
    ├── 20354e0d71ea8757168d6abcbf97bb13863b800d.nq.gz
    ├── 2085466405d8a8258a0f72376c0ed375447781e7.nq.gz
    ├── 214a96cc1bf226de2608caeafb17c2d1aa85161a.nq.gz
    ├── 216c522c630495089c40dad8beb5e6eef2a7ccab.nq.gz
    ├── 21e8e0c8634820163558fce9acebc5486d032110.nq.gz
    ├── 22e676aedab017d2463db5d51ed21e767e20f210.nq.gz
    ├── 23125349c61d99a77ccce1593eefcb4fcacd18ff.nq.gz
    ├── 23c8ea5b1fc1c31c3b4a020d49eb937f4f5ea1fa.nq.gz
    ├── 246744c6da505438123883babd8a3ec870606ffc.nq.gz
    ├── 24a43a92b4f9b7dcba57b1247200fe7c1073b8ff.nq.gz
    ├── 24a6d6daa140387c109847d5778588e4f14eb94b.nq.gz
    ├── 259d8212d06a2cbaec167a2dee6f3be64bae0176.nq.gz
    ├── 25b18f344a57050aa083c3606d7f7ede8a511105.nq.gz
    ├── 26f51d3ec456fb92999645ffef035c79805eda0b.nq.gz
    ├── 271dd1abb905d1188602374add86bf2f8b020614.nq.gz
    ├── 2886fc9df944cc5e03bbe31b37b044e904256783.nq.gz
    ├── 28d276a69219c05bd14f4ff3e4a96bb6f2a8ccee.nq.gz
    ├── 29119e4c4c6fd77dbc7e119d0095b56c8ba33812.nq.gz
    ├── 2a06461b5ba2e222f15fffd7dff92c8a3d5be1c7.nq.gz
    ├── 2a6893ce09888275853d5bc17253721bb573fd98.nq.gz
    ├── 2b11b5c6f0d328c1e1dce2cf2ec3979629cfbe96.nq.gz
    ├── 2bd13246c24e5175004b3c022d52fc8b05e347d4.nq.gz
    ├── 2c0ed0c9bde9cc38030c5395fddabcb4cddb4cae.nq.gz
    ├── 2c54ccf8e4af98df68177feb6c1f90ca95fc7e85.nq.gz
    ├── 2d57a6a27dcea942517afd2de341bae71207e3d5.nq.gz
    ├── 2db75efb617f820a0e6f335d2d922b824b2bbde0.nq.gz
    ├── 2de5891bcd1151e7a45dcad3aad07856bc0cb8c3.nq.gz
    ├── 2e5afbf9431c4712502a9a549c641e3b5e4bd1b4.nq.gz
    ├── 2eafc11501f335193c7362c593996d8d6b0710ae.nq.gz
    ├── 2f79c13c61d8dd307949dfe6d662877f3c70acdf.nq.gz
    ├── 308005ab759f89810be11215309a8858f977ce93.nq.gz
    ├── 30da55893263d60affbdaa9f5d16c77c261c2bf5.nq.gz
    ├── 332881a7f1e0a958068ad370a106dffcf0245818.nq.gz
    ├── 33aa750aa0ecb8f125c56c3897c4cbbb845369d9.nq.gz
    ├── 343b80806e5f3115df970f123312470b7b2e0d9e.nq.gz
    ├── 3445ab385e29013768d34f188f9706bc466fca79.nq.gz
    ├── 34d2087fe92c92ef912a2271fd1becfef9e678eb.nq.gz
    ├── 35695558dfd9030cf410eb28af64d734c2c411b9.nq.gz
    ├── 35dc0465685942a3b96c22a6da080f0765615760.nq.gz
    ├── 35fc2d288de37498df91bd561efc300e50f617c6.nq.gz
    ├── 3777aa7e8db83ca39316d9732042bc26d61b133f.nq.gz
    ├── 378cc580db1a45e469546e6213236efbe80b86f4.nq.gz
    ├── 37e1f2bfade8f975b810971e83be0cec3f776ca5.nq.gz
    ├── 37f4478e76b8507e3c885e349ba3635a4327c9d5.nq.gz
    ├── 384bb1e66fab5408351f5866015e55a138814219.nq.gz
    ├── 387da1e5f52c6058eae84e12d133a64425acf773.nq.gz
    ├── 39b2d5702567ddca1bec91008af3f189112a3370.nq.gz
    ├── 3a050bbf58bab3e654a88549586eb8effbe17463.nq.gz
    ├── 3a1640f8ec8baa31997a70467650b3e06bd4275c.nq.gz
    ├── 3af3ef472a2a2e66d8da1512f40f8537ae69c2b8.nq.gz
    ├── 3bda73635e62e19e7194f5e4cb4e03636d4e7a5a.nq.gz
    ├── 3c21b8064c91bcbea21313d729951b8d210a553f.nq.gz
    ├── 3c792af85d9f3f65fa10fd7be9377430cf658acb.nq.gz
    ├── 3d0d2f2127f24fc9fa16973435c56117476e30e6.nq.gz
    ├── 3f0f29f61a686be7b68dd26ad4777768e2f66ed3.nq.gz
    ├── 3f6bac2d9579b5f6700e9f6251b20fa34d863f58.nq.gz
    ├── 3fc30cbcf8d0b5eb7d17a10c909d2f01362d2f8a.nq.gz
    ├── 41429e81e364d9f45d80341d231227befb6d2430.nq.gz
    ├── 41ae0f01f80dd1e1605ef1f1a062400a1723d6cd.nq.gz
    ├── 4377a2ca0377d32eb61ded79db7cf19ce00cd6af.nq.gz
    ├── 44e070262f8bff4870be73993a4749b674885bd1.nq.gz
    ├── 451e194fd2f82baf24b81fcd35b54fb5572b433d.nq.gz
    ├── 46b56491f629d8d4f5baae3b2579b7b72db672cb.nq.gz
    ├── 46cb229616158aceb6c42b2fc8fafe34197a732b.nq.gz
    ├── 48ea1c5cbcd5de7fb35a37ea9a23acd05a8ba24a.nq.gz
    ├── 4bc4c2b27e977185a4360bacc7dc596fd7d89fac.nq.gz
    ├── 4c007930dd365d641dd1fa2d2075d15bf501725b.nq.gz
    ├── 4c5ba32265b3f383c9887322eb0b9bbff7d279f0.nq.gz
    ├── 4ca205aca7cad42d79f82ede815009cd8253cb93.nq.gz
    ├── 4cdeeedc4499b1f40ceb35523ab1ea783a292bfc.nq.gz
    ├── 4db0247aa99df0157fffe76aa1c7ee4e9cce3e23.nq.gz
    ├── 4dba2204c52d7bb0c5ef109d18f2eb80e7b74bdd.nq.gz
    ├── 4e6948251cf5273336e98365adfa44295e6cd141.nq.gz
    ├── 4f88b341996962bcc96e2132619d114df4a98873.nq.gz
    ├── 4f93dd3e4ebfb8a08b0982e77c098e8bc6068132.nq.gz
    ├── 4febbbe01ef363ffe751875ca20ec1dba516e815.nq.gz
    ├── 5007c01b5632229c29d7d794e9638bedd7ad2e6f.nq.gz
    ├── 500b2258667c7704e1bd97d879491e35e07f8e73.nq.gz
    ├── 509c06d0e2436feab96bc3f4c4853a4c4f42996f.nq.gz
    ├── 50dd7e673685c6316279fe8c46e7b2d8467292ca.nq.gz
    ├── 51eb620c2dbccd764e3d2f17534629585318702b.nq.gz
    ├── 521918682e329788a97af7f06be7d7cb711613fc.nq.gz
    ├── 5294e35227e48f265fe5d37fba829a9307261b0a.nq.gz
    ├── 531edfcf72b6b88e64542100186ea588d551a258.nq.gz
    ├── 53349565230cda7ffc53600de020f50e2bd205ef.nq.gz
    ├── 53599002ca510ce41676aba142967a7c88d5c085.nq.gz
    ├── 537dc9da3c7eb2b9dbdcd2a967430f5633871706.nq.gz
    ├── 54424480369be8db7cacba19f64926a5385f23bf.nq.gz
    ├── 54e373d0dd5969964a4195c4385b6180204b1956.nq.gz
    ├── 554403eaa71264f7a6370f7eeff5bb8c07b51fd3.nq.gz
    ├── 55756a0cb393336eb21c2ad0666f82c5effcc25e.nq.gz
    ├── 55c9dbb8120b343c313bcec358f0e6ac42567a8f.nq.gz
    ├── 560aebdfbc84812e068a7de39dae3f77bc10b12f.nq.gz
    ├── 56877f5e479a89434b1f916589a831cdbb65caa1.nq.gz
    ├── 57022213686080ffd6effeca18037e40458f1fa0.nq.gz
    ├── 57be490d32c3b6e8136c4abd939d5120f73c192f.nq.gz
    ├── 590b62d9dd32130ab188886368d5d69089b4ac69.nq.gz
    ├── 5920e898d65f755ff6b0dd1acd6a9dd8513aeaae.nq.gz
    ├── 5a4440a9d70be78566c744566ea885ad4b5129ac.nq.gz
    ├── 5b926d071855f911dca322beed4cda2ef1a801e4.nq.gz
    ├── 5ba618ee7f34b0a251388d5f226a3952fdcb35e7.nq.gz
    ├── 5d436bd1aee808e26560f342570652901e7f24e3.nq.gz
    ├── 5d9086691ba59ce796956422823516cf43a0e6b5.nq.gz
    ├── 5f4f062612c7322d41ec30077bd7939f37723bc4.nq.gz
    ├── 5ffeb2b0ed6878bd155d47f23c97b2e97e229f5a.nq.gz
    ├── 60bb56f7bd1b50f2b613b03eff2ef34711a7652a.nq.gz
    ├── 60cade9e9e8239a12da8c52c55fc9a19b451e665.nq.gz
    ├── 61e58a1d9c021e75a83a2f6282d2000ca7fee45e.nq.gz
    ├── 62eaf39dba98f531ba4891a27b80f13d4c2cbc3f.nq.gz
    ├── 632d26aca9c632af2652f1e42506a753184d6a6b.nq.gz
    ├── 635adb4f96707827ab03e1f0c9c6c1e40f42c406.nq.gz
    ├── 6480eb57b9303e633535d697b43c2c8d1a4046d0.nq.gz
    ├── 648aa4700576af09897329e66cc089067184dec6.nq.gz
    ├── 649ffeddfe81a7cbb94910a7ce10e2a41ac6aa1c.nq.gz
    ├── 6506e4569daee4939e163e02a6c7a879304f957e.nq.gz
    ├── 656918069e2554fa9048d8c3aee1d44cb5683f83.nq.gz
    ├── 65822ad8d9c0a80970026427667ad80b8f0f0d1f.nq.gz
    ├── 6717b04238b158587f50739ca38e00f0e4efcda2.nq.gz
    ├── 687522f6d123aef18f20bdb1ea7a69407b4a4150.nq.gz
    ├── 6890b4b33f25e006e42c54de8cef161121309353.nq.gz
    ├── 691baa0d02c6cebe1870259117f4862fe6424c61.nq.gz
    ├── 6a4bcd06d499251f47b76da0a6c5aa934b655b26.nq.gz
    ├── 6a5fa2dc9db73dab54fb2784cca2d2875c0c4b9d.nq.gz
    ├── 6a6462a770c8838963afac83c3b74b1e8bafedef.nq.gz
    ├── 6b358787ad43224d2e50dad5aa41de5aec66bb96.nq.gz
    ├── 6be3629e455c353db383a7e1f6c5467244ac166e.nq.gz
    ├── 6cb0979598ad0808d47bf8ea73994579cdc3acba.nq.gz
    ├── 6e09aa4dcc67bf80368993c280e43625f62f5801.nq.gz
    ├── 6e47b95b219a27d5c25358a1c659138e9f9cf637.nq.gz
    ├── 6f1e7d49ac45d75c8aeabfd0c3f0ea00d2418807.nq.gz
    ├── 6f5a37647ce09ca1d1117185c571c1e06fa4dedb.nq.gz
    ├── 6f69ff366a72aeacb414633cd4e5bdf65190317f.nq.gz
    ├── 6fa58aef81af4783d624dd861272dc77cff02494.nq.gz
    ├── 6fb20ff84e450a512d9b66dec6219696b0c81f28.nq.gz
    ├── 701f52387fc75e93224b60e7494db671f4911d70.nq.gz
    ├── 712c69ead5840890886f2be05fed1088c9658dfa.nq.gz
    ├── 71528817e26e3cfbbe66b3e1a2e82b952698fce3.nq.gz
    ├── 72912bae3c6a5771dd00102ee5c7a735fc3053b1.nq.gz
    ├── 752371c7ac2d1cb11baddd1d1261d703fb6e336b.nq.gz
    ├── 75eff9ad95aa8d00f5e5ec5f4ac7d99bfe71e3f3.nq.gz
    ├── 76515a75c5a7820d51feebd55d6729e603fd448c.nq.gz
    ├── 778eecb4981de7272bf535860c5989159c86fa13.nq.gz
    ├── 7810861248d5d8ae2317c8e84bf5386f442ead2e.nq.gz
    ├── 799316cc2f16cae565294f3b4a312f2a067db128.nq.gz
    ├── 7c17063e752041110a159c659b757941d0a59569.nq.gz
    ├── 7e815dc36a477c979a09a5cfd56f2b1bf3fe16e1.nq.gz
    ├── 7ffd943751c0b3c96c1e10b7151474c67502463b.nq.gz
    ├── 8028414d4f74329f5ac04c17742f4cf113dc82f9.nq.gz
    └── 805dd8c2e85fe039c14f439f59d5339b3a9b4c04.nq.gz

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

[holoviz/lumen](https://github.com/holoviz/lumen)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
