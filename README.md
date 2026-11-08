# Repolex Knowledge Graph of deepset-ai/haystack-core-integrations

RDF knowledge graph data for [deepset-ai/haystack-core-integrations](https://github.com/deepset-ai/haystack-core-integrations), parsed by [repolex](https://repolex.ai).

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
rlex download deepset-ai/haystack-core-integrations
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d88734f71069612b119c589372cbc6f767a7f76a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d88734f71069612b119c589372cbc6f767a7f76a
│           └── chunk-001.nq.gz
└── blob
    ├── 0005f411eb0b98285e0c9bc6b7ccf902ccb53e2c.nq.gz
    ├── 006f06c0845522fee0c0045802d937f376cdd4a1.nq.gz
    ├── 0144b29699b790e5be18b770f071e2361a615bd3.nq.gz
    ├── 0194793013160fd90fc9a1b4d79ec3a72d2baf0e.nq.gz
    ├── 0253e6df92357ccfe0ad9e502774a236df358fb5.nq.gz
    ├── 03508438d1392ba84a0b5b2575f1cdafbe7a0b1d.nq.gz
    ├── 03f69a4e758586a445b4acc49831b2f0281f1da0.nq.gz
    ├── 0416d7ac0f657f4a08c2c26c8fac4bbbfd4b351c.nq.gz
    ├── 04d67e5ba0d10465021790e28a4bce6cfde688e9.nq.gz
    ├── 060e0d58dacabd11f4088cbbe953a484d72f2d8d.nq.gz
    ├── 063646569f5a283524ecab1229834962e3875393.nq.gz
    ├── 0692c3fe714061d76b47341807ea2c0ed169c9e2.nq.gz
    ├── 075c9907ed9d3bcf5cde5d55962d004ffda796c4.nq.gz
    ├── 076b9f9cbf20a0d3bb7d8868d4321f60374b6bfc.nq.gz
    ├── 0845dea04ce32eb7e10fec540a87e3d06b826b07.nq.gz
    ├── 08545294d5d9e2515353f1466967b51276312e25.nq.gz
    ├── 09511e9f95bc0db82ca6dfa0804491583a53a245.nq.gz
    ├── 09b6ef56b6ecd6619ab618dc322f9eed3c020542.nq.gz
    ├── 09c0a045240ac3c41bc8d810ca94dcab10ffe359.nq.gz
    ├── 0afbfa15f92eaea3c707ed67b98e06e3a099d2e0.nq.gz
    ├── 0bd590a4b568ec2138dec8d4b54ba830c3f8934a.nq.gz
    ├── 0bf5b386732ffb5c37d4bc8591ce4c28363d3369.nq.gz
    ├── 0dc3dbf74add67bddfbb481c3172d1c2be0b0d38.nq.gz
    ├── 0f05c3dd0f6938afa12ad94e376b7b8998f9b6ed.nq.gz
    ├── 0f2c495e33874e19d729a29cf3ccda993e5db53b.nq.gz
    ├── 0f40e84b7accad213492cf73bfab499fbf3517ec.nq.gz
    ├── 0fe45a8a1811d75f4451fdc5809beae99331dc1c.nq.gz
    ├── 106d1805c663aea0642861d558bacf18a3d85f97.nq.gz
    ├── 10b1f8cbc4197909658fd0d234f147a8cdf24430.nq.gz
    ├── 11322c93111e0a0fb77438d92d1fd3f7345447f7.nq.gz
    ├── 114e6f0ad8365cf5320c305e98eb88414071b6ef.nq.gz
    ├── 11575b3a6dc4d2da1b56d8812f85f4383dac7b26.nq.gz
    ├── 11a02860745326de1556962248189f5242d44040.nq.gz
    ├── 11b1f7d4918e35dd392ce1875c263a3203b6e10b.nq.gz
    ├── 12390c322f3e9c8282195b50dbed7f21d836abc9.nq.gz
    ├── 127d435e1313c2b1ae67ea3a5c9ac036ac69c319.nq.gz
    ├── 128a4426448774f6819493c13e413c37cece4aeb.nq.gz
    ├── 12a40deb9ac638fe33c22bc53bfd9f776377c2f0.nq.gz
    ├── 1376afa3566ea606537e2a80886cd2c487a0de00.nq.gz
    ├── 13ac18fd21619014ecae4e14c24b3694c8a9b665.nq.gz
    ├── 13ac4e16af49d99cc997f70a8be97600de071209.nq.gz
    ├── 13cbca74bd1205794e3068dda6b5e97d53fb9e08.nq.gz
    ├── 141c98ff288c13f0a8961311b908cf6f1757ec84.nq.gz
    ├── 143bead0a68eb1b0901c048df6550672d344346a.nq.gz
    ├── 1458ad0869623c0c601073fab11112f68616635b.nq.gz
    ├── 145fdb12d77b8a3cde35cf8f1312817606b307d7.nq.gz
    ├── 1568623281ee87d2bba930a200518b6b614fca08.nq.gz
    ├── 16caaee8df3c8cfb02394a56960582fc614a1511.nq.gz
    ├── 16d0455056063feaa738967aa92b3166c57f944a.nq.gz
    ├── 1776bd20d0c5b5e1b582d2a33262719bacc0c2e6.nq.gz
    ├── 1872f673d795b4b21a477a9b2b9b8716580b17ad.nq.gz
    ├── 18e3124f5a77cdec3bd2409e1c17ba980d911afa.nq.gz
    ├── 18f251a53f1cd3d9d1e162ee400282f65de7e6c0.nq.gz
    ├── 190a282247dd8736100410b97204ee382aa6d426.nq.gz
    ├── 1a6784fb9aa655ce1bd0338acf4d49686da5468c.nq.gz
    ├── 1aa47db7cf70e9381cc4e8a875364e8e5c860932.nq.gz
    ├── 1abab65dd4d6b4f8cae4d1fc10a7d0247cb96a03.nq.gz
    ├── 1ac11756a86ac162912dadc4dc98dcb0a3f7af98.nq.gz
    ├── 1b82303195bc35332ceac7577cb7d1450d76d9c3.nq.gz
    ├── 1b909464a2bade3f1cfdbf8e5e5733eb81734c5c.nq.gz
    ├── 1bbb229d53d0c41ff86f79969626423f25d2d961.nq.gz
    ├── 1c5a2a8eb7508db27f18ee403eb90891d2bbb0d8.nq.gz
    ├── 1c79f82644cce556d4c3371bb84fe7f112788f90.nq.gz
    ├── 1c7b6cabe38182b572268b101b09db356d665aa6.nq.gz
    ├── 1c7eceb9f81f4d8b9f0a289a112f4e7691be1652.nq.gz
    ├── 1ccc5bded06f33324f58a0910ab5c738c49658e4.nq.gz
    ├── 1cfd19c23b527eb1665b163b4c4a4ab847a54435.nq.gz
    ├── 1dfd9af9e91111e8e7b20767837e3d5e7ad8b523.nq.gz
    ├── 1e598cd2047eb7e92f57a72e62d4524dc986efb9.nq.gz
    ├── 205d45cd7c3e30d05e18e0b359ff09bc020ff4b4.nq.gz
    ├── 2183468c835c1b439a109a7dec360a9608fa63e8.nq.gz
    ├── 227d32be7a940f9bf070d1d22d95fad7dcdf30e3.nq.gz
    ├── 232d9f49f015ee3d96550acd81bdddfa59e6bc41.nq.gz
    ├── 240d7bddcbba84256f02b7f60d4ce3bc47f1dfea.nq.gz
    ├── 24176d3b859ad21010d6ddf5aca08d24a52ef4ee.nq.gz
    ├── 24b34a39160f0e7bba65d1c1063dcc92503d11c6.nq.gz
    ├── 24d688d1718520b0065875fcd1a9b2103c6c8d2e.nq.gz
    ├── 25362360f105a198d78cf7548f9b956cb6ece466.nq.gz
    ├── 258ac75fcad9ea378c0285010ed3295c0730fc73.nq.gz
    ├── 25fe045cc545fed408d4e1a58c1df360286681f5.nq.gz
    ├── 2822bdc86213de8000f08a3f6814ebb7ad79c554.nq.gz
    ├── 29247a634a030d3ba40ab3aa504f803b4b00f8b1.nq.gz
    ├── 2a213c5ab562a272d7bb0856177bdaedb53b4774.nq.gz
    ├── 2ab9bc734ab19468799e2f7ffd2c0393c118d45c.nq.gz
    ├── 2b6fa51336f5ef49f04742ce88d77d519765d9a4.nq.gz
    ├── 2b90ae12c577d9b69950c2684ed20783276caff3.nq.gz
    ├── 2be0aa89a4380a4c7e5edd886e4ca1bb68e9feef.nq.gz
    ├── 2be3062ac8e82dd4db5d969e9c07ecfa7b432352.nq.gz
    ├── 2c3116644809cd267be81b72db417921ddbc0f39.nq.gz
    ├── 2c6abb3529cead36861b6f81d29137668706b6c0.nq.gz
    ├── 2cb74d47c98c3add020f30d0d3f0fe1b50e88876.nq.gz
    ├── 2cf1c470cfb7c7ea73ceb17506f344291fb52269.nq.gz
    ├── 2d45880bc07efe2008a1c0d9e61df3e8498bc7ea.nq.gz
    ├── 2eea6aab84b24ee5d8a25797f9443f9a28d398a3.nq.gz
    ├── 2eff919d50028e0110f6bb6f2deebcf35d375bbd.nq.gz
    ├── 2f03ee09ac36eb06a675475fe07d762806ca3305.nq.gz
    ├── 2f159cc3e144754e0011037830d4584ce1dea8dd.nq.gz
    ├── 2f6ee9c5dec04d71a477aa3c8f334708f0496553.nq.gz
    ├── 2f74691f350dc54a9be7b68768c509c16a0c6876.nq.gz
    ├── 2f794c6d5a1a59f59ba70eeae04b5d3e6969e2ff.nq.gz
    ├── 319fe9798dc3539ddbe316e0774a5d4d1571d9f6.nq.gz
    ├── 32186d7e072b28cc297e2a9d37ed8f45c83ed57e.nq.gz
    ├── 32e4321aa6daca02f574eea95657615507dfbaeb.nq.gz
    ├── 3365694b1415c2ea6e269766ecd12b3598d731b2.nq.gz
    ├── 336c12f477ae4740d988bd4b04a1bfc253c64b1b.nq.gz
    ├── 34132f3bea14402d72902b7c060c21bd00eb43d3.nq.gz
    ├── 345fa3c43551c9d1ce60612e09fb841f2eaed25d.nq.gz
    ├── 348c22a3c1339ec0e94e79ca7508534dabc234f9.nq.gz
    ├── 34bffa900e8203018324f984519370f5b2018a26.nq.gz
    ├── 352c160834a4d5f484bcde2853cd9945ef89b146.nq.gz
    ├── 359f45ec15096e7a528a8aa8eee8adda823e97a5.nq.gz
    ├── 35ac8a29ee8f03b0fd4215cc9d8309034223d9d0.nq.gz
    ├── 35bfd0fa669f965dcae48f519903d339865bda00.nq.gz
    ├── 3629eb43494a0fc909b32664d74270d3787b38df.nq.gz
    ├── 3643f6b5e410000c5cf44b4687ab4406d7049642.nq.gz
    ├── 365a786d370e5550dfb8b5d1e9b475b7908c98be.nq.gz
    ├── 36c1845e82d10d6326c3490bea42af771dd18d28.nq.gz
    ├── 36fbb36dccdeefff1d569548d8410688b4ae017a.nq.gz
    ├── 38ff539b1f098835e635d5dd6eab7266a8068ff2.nq.gz
    ├── 3995c619fcbd518b3f8d279a2eb0fbc0c2e4e287.nq.gz
    ├── 3b38e6d70b96fcd0a28e11efacf04c44cefcb5bc.nq.gz
    ├── 3d4485bce65737783a61bc799ad9aacff181dffd.nq.gz
    ├── 3d579803eb03aef9d039ccc6ebcda2b47dcbd961.nq.gz
    ├── 3d7b19e89ae18a58f46c3fbc12af14ec5add178d.nq.gz
    ├── 3d98f26caaf7a0f21a50e750f6b764aa40fc7040.nq.gz
    ├── 3e9c31e738f74a1de22164b83507b2360033880a.nq.gz
    ├── 3f4daae61baa3a8fa9f495ca983ca52020a5f242.nq.gz
    ├── 3f848778755d5882e158b1d5dfd6e14af0847abe.nq.gz
    ├── 3fb80eef7b0619eb51857d9a35f251f2fd471272.nq.gz
    ├── 42e53d7705b6114d36b48b975617ff7aa2a49132.nq.gz
    ├── 42e5439644d025324850ce191f59000bc2be3afd.nq.gz
    ├── 4489971dc3ac114a808245c2911f2de057cf0607.nq.gz
    ├── 455274f4fc64c56071f3b42e358fbd629a1794fc.nq.gz
    ├── 4589cb650a39348eb99af1355fe3f16102b843c7.nq.gz
    ├── 4603bd39c13f49b897b7bd0efbcf55374113246a.nq.gz
    ├── 467e54b21640626384ae87c5269c83e00d45d441.nq.gz
    ├── 479f57c76bfe36173af4285b0d0a2cd9f9a566b3.nq.gz
    ├── 47a643c15c781b00049f96c92a2f8468575383e0.nq.gz
    ├── 49322234cf6a25c4f88415cbd30c7ee820962b65.nq.gz
    ├── 497d22c2a72518e9a46f63c8265b5a865d19f6af.nq.gz
    ├── 4a01369682f37db005c4d325d519d1d853c22d9d.nq.gz
    ├── 4b1563a836658c6dd77adc252f266adef61aceec.nq.gz
    ├── 4ba260995487b4267bda79d5d8e97cf466f51ef5.nq.gz
    ├── 4ba6d89c6f67e365b01d9ef29440729c9d1f173f.nq.gz
    ├── 4c8a76db36e01788ff99a7d8af6a7be2cf742b62.nq.gz
    ├── 4cbf9de1fd9b7f50ada3e40662e54407383edfd4.nq.gz
    ├── 4cec5aac7068f1ca6229ca5c85ba7b23b3ec0aac.nq.gz
    ├── 4d0519e2eb8a6fef6ae29e754b79d7c9c986893b.nq.gz
    ├── 4d09aac30cbdf9c6dd976cd649c8e64d1c952355.nq.gz
    ├── 4d16cd8b92e0f3a0de1ab9c3879da58d3f17ea0d.nq.gz
    ├── 4ea9663a2fc7bacbccc2828d4b922f5188a7ea9c.nq.gz
    ├── 4ed6a04ad36e6885e0bcb210200a3f00174b4bde.nq.gz
    ├── 4f83fe6e0293c13103ab45c1fa254a460d95dce8.nq.gz
    ├── 501e9a2937742cf635988b03c32f94163db0d05d.nq.gz
    ├── 50c5297ea894594176c7ec1e1cecf7e65ec875ba.nq.gz
    ├── 513fc41453253efe23c66e1ddc1a337c54f34c35.nq.gz
    ├── 5183d20657147fe120f28613259366ec1f3cd848.nq.gz
    ├── 52533726ddc3b17fdefed16dd5dc0d9824611cdc.nq.gz
    ├── 52f82caa4f33f47dc666ac3e4462a89831d07993.nq.gz
    ├── 53e846a08dfde4554823c01eea35bf1d3e9e3994.nq.gz
    ├── 5461000b27c390514e3cc5070e00d04f44fa5fa6.nq.gz
    ├── 546f6d69205d8ab8e30924c1ee67e13f2b25fd46.nq.gz
    ├── 548bdcacc5501811bc04ae228565ec040f80d9dc.nq.gz
    ├── 54e5c3a4bf4757eb67a3cfd76956bef534e58f2f.nq.gz
    ├── 56030d6d864c578b3020493e8acf59d09ba5d2cb.nq.gz
    ├── 56dc30db4e4d03f764a2f01ff23c8d73eebf8a4d.nq.gz
    ├── 57caf9818c0797f1b66999d2d7452615d02e69ac.nq.gz
    ├── 588114cde8b4d21823b5640c91e5a3d32d962743.nq.gz
    ├── 58898a2acb07d34ed20ba380224157576cce7a99.nq.gz
    ├── 599c74c4e45b4a2c01b62727c68a5be244dea078.nq.gz
    ├── 5a6b40e2c93c34d977ad88c43f55a122cbfc2783.nq.gz
    ├── 5cefd76031b85a7016491c2ac25f70c760dfad09.nq.gz
    ├── 5e5674ee3c50ea7c85af233793cef5d1a5cc88ed.nq.gz
    ├── 5e5d24f6b2f345c6e3d86069616280b04831e9fe.nq.gz
    ├── 5e771fe7b81f5ae6219110e832758306ed19cc19.nq.gz
    ├── 5fe92f9c648953c617a04d430f68a829f2c0abc3.nq.gz
    ├── 601f368b8d8f1e630b710283b4be457389e6878f.nq.gz
    ├── 6093c2e824d7f080441efada794b1a5661ad07d0.nq.gz
    ├── 6134ab324fc80538d039c03e7545943343d7f105.nq.gz
    ├── 61eaf37e11bd2ee3f497f87a5cf67353a3c9aa5c.nq.gz
    ├── 625bd9fd8e5b4383904bdf3d3bd445823238f42c.nq.gz
    ├── 6278c542a93fb9513defe9d450f6bb8bd661abc7.nq.gz
    ├── 63051b12de5569382d17b7fe56fc25f3ae93066f.nq.gz
    ├── 6384246e891c59abf174e7225ed7f793e814ed69.nq.gz
    ├── 63bca08d5ff37e585270a9736aca5823b5f08dd6.nq.gz
    ├── 645c0ccb86899df0cec21746c3221c498c6da41c.nq.gz
    ├── 64b9d03b670859e69a80dfcf38939e28ac3f2921.nq.gz
    ├── 65a3c01dbc301967604a568a94c126adc88afd39.nq.gz
    ├── 671a798b2e44594668af67c34c2165cbcd89a3b8.nq.gz
    ├── 6913b59e1dd7f53165adc56c068ee27ee3dccf65.nq.gz
    ├── 6970cb8ca9837db57507ed64faccf6f7002f595a.nq.gz
    ├── 6a0a98493e85da10d4f5ec698b624ede36e33291.nq.gz
    ├── 6a5ac46bb14bbafaa5b7ccde361c76851797f72b.nq.gz
    ├── 6a8d2874e22c4f715f0e38fc44cded7c96bb12c1.nq.gz
    ├── 6a940b9591d1eb4c9d03a563edeaaec06c6115e0.nq.gz
    ├── 6aad75d07109be9c284c5c1c5f80a087fd0f10e9.nq.gz
    ├── 6b5e14dc19056a1a18ac414204dda73cd4eb8b8c.nq.gz
    └── 6c049f72d80df54a8bb2c6f6f6c5318e1b6c0ec2.nq.gz

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

[deepset-ai/haystack-core-integrations](https://github.com/deepset-ai/haystack-core-integrations)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
