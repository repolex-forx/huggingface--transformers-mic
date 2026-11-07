# Repolex Knowledge Graph of huggingface/transformers-mic

RDF knowledge graph data for [huggingface/transformers-mic](https://github.com/huggingface/transformers-mic), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/transformers-mic
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fa648220c4d566c5a23bbecbde2465c685a15754
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fa648220c4d566c5a23bbecbde2465c685a15754
│           └── chunk-001.nq.gz
└── blob
    ├── 013be732dad22e9386438610fb60403e9f110582.nq.gz
    ├── 01de8e234f0f905e73a88f7fc232c329fe2898fd.nq.gz
    ├── 01ee2961cbb1b8696f1d6d96d5ba762a5cc75c21.nq.gz
    ├── 0285f24ccd5101c3fdd4a5f1837bfd6b242d804a.nq.gz
    ├── 02e60b2b10c6e7e956236958acd1de722910fbe1.nq.gz
    ├── 03501340276cd05b3c34a1735ef03bc143257061.nq.gz
    ├── 0385c363ac6ed309d151022576b06229503db4ad.nq.gz
    ├── 04d6cd094d9bbe1ab394331f79d5644478538df4.nq.gz
    ├── 051b048b34a7f6023bf6b8577a088ef7b633ed31.nq.gz
    ├── 057c5c0a13568b6f38caa33936b6463c8aa1f7af.nq.gz
    ├── 05d28d0d1b7c98cc65de4f3607b974508dc736c4.nq.gz
    ├── 06285b845698e30eb76f9eae17628d4322577b28.nq.gz
    ├── 065a87aed52c6bb9992ba366053c5898702e6454.nq.gz
    ├── 09252520f89386c7652853232755bed33fcb85a0.nq.gz
    ├── 096ee1e332aeb9894452519321f3dd391e4fe7d9.nq.gz
    ├── 0a343c4371dc45f0d3052a53229ec332e30f11c5.nq.gz
    ├── 0bb5b8d1095eb8b998cd8965fe82619af47d7914.nq.gz
    ├── 0c31e97e2c4e5695281ea29a5c001e3bb80b68d8.nq.gz
    ├── 0d42b50c122e9f50c638d2c290e1e3c8d3053dce.nq.gz
    ├── 0e28cb820a8539b07e22b0443a8c942bda2d4108.nq.gz
    ├── 0e6de5a8cff0cb6d0a20ef3c3a9f1c8a28dae675.nq.gz
    ├── 0eb6a284436b6df0aa5855559f9bb8513938bf91.nq.gz
    ├── 0f332cb28f9af435bf649a9b853619cb7e09f775.nq.gz
    ├── 103428e2c4343044cdab253337f9cd74c97bae07.nq.gz
    ├── 1123f3656ef7a73f29f03d5a9b1d124c802084e3.nq.gz
    ├── 112e9f52289e3dec85239e446feedd0fdc4a5144.nq.gz
    ├── 11dacfe68d1a95ab52c06300b73c0c7db4ff83ce.nq.gz
    ├── 1256becfd16dbc63e3905c99a8566100ef1e594c.nq.gz
    ├── 128da32e443311d418c90dad554fd3af8994946c.nq.gz
    ├── 13004579de89d4f01c4cdbbd084c62546b4f62c3.nq.gz
    ├── 14050197a3b73dfeb070fade18533c68e1567e5e.nq.gz
    ├── 1478a0684ba2ccab7900a60b97d4a7e30a50d358.nq.gz
    ├── 151d2e882322dafff7544801f49d3db51fddb9c2.nq.gz
    ├── 1565a905fa4538a4649a845e0e207af86cf321de.nq.gz
    ├── 15ce4c9f74c6ffcad96c5573337de26bcca5a989.nq.gz
    ├── 1627e7beae1eee8148c4df23a3c4798114c625c0.nq.gz
    ├── 170b7712ee725f8c559562212b519af286241905.nq.gz
    ├── 17123c851557fe44ebe101d24b4570a142c558b7.nq.gz
    ├── 17b24dd09421025d0204b6765e95487aaff213e7.nq.gz
    ├── 185dfa283d3ec59846bf7d5ba9d029862ea9c011.nq.gz
    ├── 185f27488dff0bb0415a34bc58f01f91ca6179a9.nq.gz
    ├── 1a2a07a33ad16b9a91bf669a272abaa57292b259.nq.gz
    ├── 1a6b4188b66f2f848e40b02cd29fb1a590cdd384.nq.gz
    ├── 1cb38eb8855a164b50edbf82f31f556dd0270707.nq.gz
    ├── 1d5841e29cb8f3638cbf73fd8bd54c1bee5113d0.nq.gz
    ├── 1dab44bc49ab57857e4a386a7468bd300164daaa.nq.gz
    ├── 1ee57f537203b622f30746a3360d85c35b4f2460.nq.gz
    ├── 1efca676538a5393863c31864158461d06bd2058.nq.gz
    ├── 20a460b00acc453dd68db51f04319053c7e0fc0a.nq.gz
    ├── 21a54e7693c17eb57c8008b163fb61dcbff32f94.nq.gz
    ├── 223179b6250d6e0a5a63dedd04cb4cc7c8cc11d0.nq.gz
    ├── 2257b1754defd7b1a742af4fd801052166226bfc.nq.gz
    ├── 22dce22e4f513706753a14758965127b93eb954e.nq.gz
    ├── 24a46697bc03d15fc3f1021105dc60f38d257079.nq.gz
    ├── 258cc3c37dd8f7bfb410312e6998a440bb3180f2.nq.gz
    ├── 25de311ef188e11b998fb95481450b8b13b66305.nq.gz
    ├── 2771d27c53687710a289904069786a9429478df9.nq.gz
    ├── 2964a93a9d5c2e1a8c6657417215b691eb0d8071.nq.gz
    ├── 2ac78d5597ce445443e8458a8f330d1215e40ca8.nq.gz
    ├── 2d073322155ba1a896d79cf6821ddafed932f783.nq.gz
    ├── 2ec2732da4139e7c9e6b35d0e52328da443a83c9.nq.gz
    ├── 2f798b3f351f8f71ef7cd54e58346f9cee84a66d.nq.gz
    ├── 2f79af3c1f2345ef57e93e2490df0159241e1811.nq.gz
    ├── 2feb7b70a9480824ad57c590cf8008fff099a66d.nq.gz
    ├── 3062eda378e524b11cac8b2e830e83bde9971c68.nq.gz
    ├── 30a3e4a1761029b6e1f549e64ce724090f6814cb.nq.gz
    ├── 3189f944fd4e3dc24df72ac9f363bb7228134e3c.nq.gz
    ├── 3236ca91f11d1a69bc03d106080fad593deefc78.nq.gz
    ├── 33b30315723ab3d2f9ae3454cbb46c1336184376.nq.gz
    ├── 345fc02a119f1d533869b079b309debbc0dc1922.nq.gz
    ├── 35d90e1807464d5af02396898e5623dfc67bb638.nq.gz
    ├── 3603901b4a3c6a5e42552c7cc7a7711ffbd06224.nq.gz
    ├── 366ff52f122751f39dd35c20ce241d5c228950d6.nq.gz
    ├── 3b0c844f12abe55b7988eeb62f8553384b0d764f.nq.gz
    ├── 3bfa67e79bf85f1b77fb7dca5201b4448d796c2c.nq.gz
    ├── 3d10bc66d0815b611292e2176c36d6f6e57bfdd8.nq.gz
    ├── 3e95b719050df0be96da5d3a8bc40c769328777b.nq.gz
    ├── 3ee8dfe6b6b5f045f988a2dec84a976bed9453a0.nq.gz
    ├── 40450b8817d3bcaabc195476fd666d1deb479bf6.nq.gz
    ├── 40f8fffca56aed1b1002b341e714c3d2f9e05951.nq.gz
    ├── 417035cc148d775be16d59fe22f5d259480ded34.nq.gz
    ├── 42738204d5663235ba92faa33cb3d716b30d5334.nq.gz
    ├── 452c071e700f8a0b445a4a782906fb7977d4d6d8.nq.gz
    ├── 455a88acaf203a64241b6429d002aefe6f443245.nq.gz
    ├── 45c25b262529343e5a82ead197fc2a2f4cf09996.nq.gz
    ├── 45e9d559d289d70645f0d5408707d3a54eb61785.nq.gz
    ├── 4755fbfd96930c045b5b569603d984d401188e1a.nq.gz
    ├── 475d32346a017c4b542f03e1f5e2f4b0d4574d9e.nq.gz
    ├── 4926f9e3ce58b114762e3e6efcac9009ac286aa8.nq.gz
    ├── 4aa6294d9a68720345869f1db7bcb3a0e0e3b67c.nq.gz
    ├── 4b7faa30b0aec2ed1c9674d5ef97335358d92bcb.nq.gz
    ├── 4b823d7933c0a2e434658389e0e568d33e578598.nq.gz
    ├── 4cb49e8fe5c1813947c59d9fd9515595e0f9a0bb.nq.gz
    ├── 4ce480951f573842f15ad3245d6461a84f25e69a.nq.gz
    ├── 4d33a98c5dba4013de93ec389e9dc46f53525166.nq.gz
    ├── 4d6c6812a775d7fe3fae49ec538e9c7f3b6585d6.nq.gz
    ├── 4dcbd24ad35ec1e9581233e84e52b8923299b26f.nq.gz
    ├── 500ed69d887e1ec85015c8c964c9044c7c8c480c.nq.gz
    ├── 5050f5dfff267dc510b3abfbb2c0a670a7d5f3a6.nq.gz
    ├── 524f32d391b6b6ec0256c53c5087d756c67eed49.nq.gz
    ├── 52c85e037f0b857ca8b5e82ece16a79d3c8ddba2.nq.gz
    ├── 52e0c3ff271b5372e9127a295dd01c75efb6bbbb.nq.gz
    ├── 531591549f248e871a543a989c6bfd25e4509d13.nq.gz
    ├── 547fcb0e9fb1211539712c4434c321cb3569aa00.nq.gz
    ├── 5504d4115577f1293df1c52138409a0384415f2c.nq.gz
    ├── 56cd4ccdc999d4090d0485a0205370e42cae5aa1.nq.gz
    ├── 584716ce145043f55a5f9320f5b03ff5b91b4596.nq.gz
    ├── 584b0d5871e599f1f2a45a6b07d0e9063a5718be.nq.gz
    ├── 58597be715d73d1f5ee7bd9a8933ce49aa5710f1.nq.gz
    ├── 5a1ab94114bb6344b8aa4810bd00dbbd96448caa.nq.gz
    ├── 5d6bbb9bdebba2090c50681fc45e776d52d46f2d.nq.gz
    ├── 5da81b59d5886624d840fb269f3594a963c680ee.nq.gz
    ├── 5df6128fde0fa2b369ffac08c351fee68cea028c.nq.gz
    ├── 5f9f8d31518b2b0c6f2cdb63fbd8055a68945021.nq.gz
    ├── 60543f678fef52a59f8e53b4ee100abcb4041acd.nq.gz
    ├── 611b18d5592b7482eb24d2286513792401308c0c.nq.gz
    ├── 61b7a901e48a964912d551a7087321c1955f014a.nq.gz
    ├── 61d40b114bcb8a3c08a78ca1c0d2844da3d370f1.nq.gz
    ├── 6233065b7611c02c71e7607ee9f4bd5ceabf9c3f.nq.gz
    ├── 63925a4e6f2943d4b1e72f61e7e5720dd46a7378.nq.gz
    ├── 641bfb6d3d34aee7e13495526b7b87938f3fcaa0.nq.gz
    ├── 64334a02cf462546241b16f8bc7e8720971494fd.nq.gz
    ├── 64b61380fe848ab67d3ec415d27f8bf12564ab24.nq.gz
    ├── 679b12aab730ac7846d0bd214984c1c2492f9d51.nq.gz
    ├── 67b4ed0e592218199f49cde1bb214afbeb9baf37.nq.gz
    ├── 6838a116065db23b80a5170eb8251080ebed0e70.nq.gz
    ├── 6895b701f4d6e2ea54ed7017df8669be5b5282db.nq.gz
    ├── 68b7d66c97d66c58de883ed0c451af2b3183e6f3.nq.gz
    ├── 69479c32d22dc38dfebe97a487f2f6571bd8893c.nq.gz
    ├── 69503b13f727ba3812b6803e97442a6de05ef5eb.nq.gz
    ├── 6a34baf5d2396d8369a7ebe1171a1135492000c3.nq.gz
    ├── 6a44e3592a055fd227c316183c4d93889cd4e7ae.nq.gz
    ├── 6bcc87c1c86b86153e741ab6c80414c130db5c7b.nq.gz
    ├── 6c3527b91683e97e7d94434208886de612bf72a6.nq.gz
    ├── 6d1a9b2b3b347e3e69e376bc4a023962393c045e.nq.gz
    ├── 6d7f291b08937055942639a55965af0cef7c8f5a.nq.gz
    ├── 6db6a80b276ffddc73f86cf4ce3bc35e4edac7e4.nq.gz
    ├── 6ebaa75f5aaac760b2a6f429b2eede44cdfefd51.nq.gz
    ├── 6f7dc6303d5ba0e47153c407d974c04ee6da2262.nq.gz
    ├── 704c62e5c4399b20db268536348b20619b39ea11.nq.gz
    ├── 7156829bbac2511e00e45f51a600acd95db82379.nq.gz
    ├── 72a4de7f8566f40a7cf15fcd9185f90285d2bd0f.nq.gz
    ├── 732cf66af9419fefce36ce6571a26be39116e4f1.nq.gz
    ├── 73ba9e201efdbb330455cdbf8f939750dc5c7e2d.nq.gz
    ├── 750722688b2c5fef35f411e161b0573ebce06903.nq.gz
    ├── 763b1e5558403763059cd44bcdd23c6514bfc5db.nq.gz
    ├── 78cf36b37d758914a39f0d37bc31882cdc26b451.nq.gz
    ├── 7916bf466f96835775819fd09fe23396e175d4ff.nq.gz
    ├── 794a5d82753b33ee18cfb33b9dcda55a776f08fa.nq.gz
    ├── 7956d39985643c6526e814224ee24e2d31cb5936.nq.gz
    ├── 795b6e3a10fcd17852a2085ddae3f502b05db744.nq.gz
    ├── 7965d3f9cdf2af8b2021f11ea4c63d8ae86b358f.nq.gz
    ├── 79d40127a42ca0a51c2a6e19d0f1a4a26875c03d.nq.gz
    ├── 7a610043da7ac95ac7a134c9be05b273da3d5e9a.nq.gz
    ├── 7bd2f8ac09e6eed3ee156898b6bc64c9b01aedde.nq.gz
    ├── 7cdfa1ee735b44fb43542f215d9897994aeeb737.nq.gz
    ├── 7e835e7dd49c9423288bf88f3d768dcddbaf856f.nq.gz
    ├── 7ea2a579016d78ec10fbbabc73755ee0c1ed0e97.nq.gz
    ├── 7f75dd875773f03ed3eacde16564d25b99d7ce6f.nq.gz
    ├── 7f89ecc4c2fd67553c039a657e8ca78b7526abcf.nq.gz
    ├── 7f952a648de0d3fc8e627e83f66100334dcd1a1a.nq.gz
    ├── 7f9afeba956d0e99d0eea3cc7e534634e76b8594.nq.gz
    ├── 808f475b1be94ef4d2b52b1ed0960f972b2776f8.nq.gz
    ├── 80f329b4c1c2a2093734ed6867134471acd09de6.nq.gz
    ├── 843cab698b3b98121666f0e656dff6b38a3fac48.nq.gz
    ├── 8476ad8fb25350a0b855141cf50bfa83e1e98d2b.nq.gz
    ├── 85991e750f14624b995a42cad4c9c96c8f358581.nq.gz
    ├── 85c2518efbc1b125fb3341a0eb73234b247d02c8.nq.gz
    ├── 861fffc188229f59e35bb588dcf0f27f44cb1210.nq.gz
    ├── 87c1255aa246295f7fa993cfb1aeff3a58de67f6.nq.gz
    ├── 87cb228ab620ca669fb65e3b196fd925f74d5b5f.nq.gz
    ├── 88ada2ba53d615a6a072f9133eb7bb1a40ca1849.nq.gz
    ├── 88dde3d6f51f38a5b5954b6b3929589836d86903.nq.gz
    ├── 8901aad98d24b13fd316b1a6d736ce91b9e1b944.nq.gz
    ├── 8929fc56008298c967431b3c3f3821a72291fac1.nq.gz
    ├── 8adc984dafb573f7e2bda8b7812db2d901b36840.nq.gz
    ├── 8b41cda763dfb42cd225cbc6709a7c0653c2d5cf.nq.gz
    ├── 8b833b35b95ff10656f4a23630bc64c22994178d.nq.gz
    ├── 8c644b354624a6ee49f4e98577fc4c1ec9839bec.nq.gz
    ├── 8d2fe372a7924e8033038fccfb716258f1c847da.nq.gz
    ├── 8ebbb990337749831a561a5ac13884c76e577b59.nq.gz
    ├── 8ecb5138e598051e8c2ccf6efc88125c203b06cb.nq.gz
    ├── 90ef500c297cb969592ad788326493b79526e2b9.nq.gz
    ├── 920b6ab5c1d0539e8b4fe572f5a4b0fa240a2be1.nq.gz
    ├── 95b61fdf71dd45b78418a555afd0de6967d05c40.nq.gz
    ├── 95e193a7e085aab6415fb53e8b8c224172125cb7.nq.gz
    ├── 9619d73f86a531fa0a9cadfca2ae6ef3c484b62f.nq.gz
    ├── 96500510999f07c80873921d93b103fde0282e86.nq.gz
    ├── 96e08c56df577b9c4c45954ce600d535b200d3cc.nq.gz
    ├── 97dd512ba03be756ce3d1c3a9562e08f2bfb5c50.nq.gz
    ├── 9c956d42d958d07bea5a8ae15998475bf71b2245.nq.gz
    ├── 9d92cb6697e754d95545a8319fcbffca38cfeb67.nq.gz
    ├── 9ddb2c2f31cb28650b6ce5655645052fd7f8d1ae.nq.gz
    ├── 9e18c400e2a2f6ac8fe6db9173160f292eeebe34.nq.gz
    ├── 9ec5249dd7e8bb5111f19728cc9f34a98503f7b6.nq.gz
    ├── 9f4f5e730e2968c668d042368148a3ece30f7dc7.nq.gz
    ├── 9f7566d740ab27ca012abb4d38b3db36e3dca8b4.nq.gz
    └── a064e0253f0b4b875f408863d8bed2d54c647af1.nq.gz

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

[huggingface/transformers-mic](https://github.com/huggingface/transformers-mic)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
