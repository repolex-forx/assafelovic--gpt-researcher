# Repolex Knowledge Graph of assafelovic/gpt-researcher

RDF knowledge graph data for [assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher), parsed by [repolex](https://repolex.ai).

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
rlex download assafelovic/gpt-researcher
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3582a6841fe7dc801e2a34e34ee408641aea9bce
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3582a6841fe7dc801e2a34e34ee408641aea9bce
│           └── chunk-001.nq.gz
└── blob
    ├── 001f8404e75097b3c7394c595df37e7a19331fa0.nq.gz
    ├── 00aff8f589f78ada6dba901621f19455d1186723.nq.gz
    ├── 00fe7197c4602aa02b89375fbdeefd768a5224f9.nq.gz
    ├── 020120b957be359e2579d8e9a5c0f36a60253e38.nq.gz
    ├── 02a153747f3299b8d042247f5575a325093e9aab.nq.gz
    ├── 031c230ad96d8e08a86c73b8f33106f727fd1b00.nq.gz
    ├── 04c5b39cdc49ab398ef84b139ebc30986f8cc3d6.nq.gz
    ├── 04f2b633b280d94f260b06cb880793693f637ad7.nq.gz
    ├── 052c3fb55ec63e6f01443efb9c8e465f33c7ebcf.nq.gz
    ├── 056f83beeb681605ee9e691db40b2ac4f76a2dba.nq.gz
    ├── 05e0088339f011d2dde580f4bc90118ed9f91b6f.nq.gz
    ├── 05f35b126dd61eeed4200fe6b65d082a80833026.nq.gz
    ├── 05fa965fe869ed5dcfb05d99b3b6f46fc524fbef.nq.gz
    ├── 0606681534acf4129e3302659ab45158fa833feb.nq.gz
    ├── 06107f21f17eefead2952d4b6a18b7d538b78a28.nq.gz
    ├── 065a32f4021febccb5cee695e9129cdb9d186349.nq.gz
    ├── 06d5c653f54e2db7b06d49c543249a8810237c81.nq.gz
    ├── 08165d4efe4be2b0dc607c6d711f776e193f6c04.nq.gz
    ├── 081a2faa553b8888b6ddc2d13b9aeefb3ea45ddd.nq.gz
    ├── 084e9ef918a93b94757db482d96128da40259ec2.nq.gz
    ├── 0873025a69e47565875852dcea68b08425b9498c.nq.gz
    ├── 09eba96a47a68c5de1031b1158ca726283609165.nq.gz
    ├── 0aae89d1456ebf1e1fcc9da99c0f4c853fbddaaa.nq.gz
    ├── 0bb7d2a5c34d9ee915c56f4562d22cb341382db1.nq.gz
    ├── 0bc3892e5a9119f9dc03705d14d269e28eb4ce4d.nq.gz
    ├── 0d7756f1cfd215f18b85d5b915e9cc3bc5257b06.nq.gz
    ├── 0ebc2ae3b80c013fecde398611b5ce57303bef2c.nq.gz
    ├── 0f2ddb991f142a5db476d94cc4c0a1eee366b629.nq.gz
    ├── 0fcac8674eb61c7ed97594696cce8dd65e93e730.nq.gz
    ├── 1025b2611196ad3c48c488d0e50da193c3eeae15.nq.gz
    ├── 10b0f0ff48d0a1241209fc3d2a64b24c95b103b3.nq.gz
    ├── 10de4af5c413a1e779cd1964f2723b62c47de946.nq.gz
    ├── 10eca66783a2dc03590d73b0e5dec223aed1cf18.nq.gz
    ├── 113ca2af9601605437b48c2cb79717fbf20866dd.nq.gz
    ├── 1174521a4997c50059695fe6bafe0b6cf47fbc88.nq.gz
    ├── 117f152e881c64a2305cb34842eac02a814b6a0d.nq.gz
    ├── 11a0951b15bda2e2a4871bc18f5816410dbe6cf9.nq.gz
    ├── 11acecf6cc89d2d9aab021de08f0358368ae7654.nq.gz
    ├── 133985c4d56344890e6388656060dbe0a6e88185.nq.gz
    ├── 1440dd5ce40c1ff1049fab43971f30c13b7ea1f2.nq.gz
    ├── 152ce0a27b302fab572865ec17f9a394198c0365.nq.gz
    ├── 157bb5a6d260718e99cd877cb6156ebf1ada3d82.nq.gz
    ├── 1597a30116dab6b17a3425fbdf68f7a156e383f4.nq.gz
    ├── 159ec9d97f8f3e24e14de4700fcd221aafa4ce8c.nq.gz
    ├── 15f82dba7c6b9aea4a178bfef4929584d8f0f474.nq.gz
    ├── 16342fd8a367306129bc75b01413602dc0ea2ae2.nq.gz
    ├── 17161a7e8b9e6af9e9f84f1d26e821e835eeba24.nq.gz
    ├── 17814fb019878121699fb8234574cfd39d26ea12.nq.gz
    ├── 181edd287dacc54f363e923ef53022f247413211.nq.gz
    ├── 19293d9dc1967b75cead8ee14b36140f72f6eb4e.nq.gz
    ├── 1975eb688b9dd1eeb46d479f8bfd8a591a9f428d.nq.gz
    ├── 198089de147eda172dea7d4fc49c07f1df78afae.nq.gz
    ├── 1a295fd2fb87c9613d740e0b4ddebe29b04cd738.nq.gz
    ├── 1a42018390194ea0b7d51e4a021298558a32cd72.nq.gz
    ├── 1a6959010fb84b8a95ad2c015941b3a392b63049.nq.gz
    ├── 1a83756eef1377280652bf7c63bb63f4bddcdd30.nq.gz
    ├── 1b58f31ea77bf827f54a2edb987965f473a1f456.nq.gz
    ├── 1d5cff6d155d0caad3689cb505fd25eaa1006a52.nq.gz
    ├── 1d763cb026e4a70ccbff82dd0864b31a89c1de5c.nq.gz
    ├── 1dbe8448f999e468d98c4ed26db01f02ed2f8d13.nq.gz
    ├── 1e025587a78227bbabc1c733e6402d1413fe3123.nq.gz
    ├── 1e9877e8c9305443981fa6223029e4d8f0d51ea6.nq.gz
    ├── 1f0011e3fcb18800e75f40a9e36ddd57b68633d9.nq.gz
    ├── 1fff1cfa5355d2de7cf0a1cb89a3ad0a44fa3df3.nq.gz
    ├── 208acbcd2a5dc268b30f8ef69dcb8fef3612bb9c.nq.gz
    ├── 21886c76a258bb46197ed735216e34617af626e0.nq.gz
    ├── 22397a83f9b6ea8537471e459b0a27d93e7b6ab7.nq.gz
    ├── 234245ad849ceede91179d603bfbbc96fdeb37f4.nq.gz
    ├── 237f6110ab3475b936dbf609437bb9e052230aa0.nq.gz
    ├── 23f482855ecd374280dc98a97b2a5ac88f20aed8.nq.gz
    ├── 23f943d28cc6c3e0322f2b47b6974001705e7871.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 2649d2741f340c45ace30ada9058f4e77bb09efe.nq.gz
    ├── 265d7b6aea8f9f3da9322ec9c589362e256a2c67.nq.gz
    ├── 2707547697d003b4d1c173e5686eada1fd724458.nq.gz
    ├── 277c1e8faa3efebd2a9fc230e8e5da3d82cc3843.nq.gz
    ├── 27b6a9db53c92f5f70504dffed448ce017d7fa00.nq.gz
    ├── 282bed57cebbc5ee468fd4269447315b8bf2495a.nq.gz
    ├── 2947398d6e579e03d80aaaa7fae9e88afaf2854c.nq.gz
    ├── 2980be953ef588f4d877b8acd89748437dde6393.nq.gz
    ├── 29a168137239cf5d1cec23fcf00b1850c6f1ec1e.nq.gz
    ├── 2c03e840b84fef6207272525e797ac3356ec82e1.nq.gz
    ├── 2c378c8adaae2d6bc64b41c9b398177028ee8301.nq.gz
    ├── 2cbfc9800d21b716adffd2caf6bb867709fe1f4c.nq.gz
    ├── 2cdbc7b53517b5fc4275eea8938d021990a0d479.nq.gz
    ├── 2d1fb84f67cef7018b78a2b7693d4e0c410e4f7a.nq.gz
    ├── 2ddb19d1047e00f966743911d160f4368dc3082e.nq.gz
    ├── 2f8c07af8c224a21028aa5d3dce3095e8f03796a.nq.gz
    ├── 2fc00d577ef58c4acd607f26e9d0e6e107b42e3a.nq.gz
    ├── 2ff381d3b5f3c49d980f240cd65a86a3355d9549.nq.gz
    ├── 30b90f2dd6c3ed4b5fb989c1e0889f6083101214.nq.gz
    ├── 3179f87dadd2cbaab8d210b868c74404a7bc1cd1.nq.gz
    ├── 31a46a5f9bcafed1360350e1a2a855baac0582f2.nq.gz
    ├── 33102081c9651b6c6d522bc22be4d777f3db48c4.nq.gz
    ├── 33477fe5311298c834af00fbc0158e2a3e3a8554.nq.gz
    ├── 334e993d5114e6f22dc62d9f0e8082f60eb265fc.nq.gz
    ├── 3374f66f8dbe202fc3b7f9395a6b3d58bb04fc7d.nq.gz
    ├── 338d46c25e7a6a68d3e6a3f1e7708b707b31cf85.nq.gz
    ├── 33f6fab74e7ca63704b5897ebdeaf75e83704031.nq.gz
    ├── 35415807a20cc553b5b75443cc9cbed7c4ba9054.nq.gz
    ├── 356beba9e75c749190360dc9ef21458ad380b17f.nq.gz
    ├── 36321d74f780f2bc4e534b5d40e6f3f0c572056e.nq.gz
    ├── 37cb5d87daf682fa01b0be77417f39fe1d166f8b.nq.gz
    ├── 3831b2fe6c9d8b308570eee6428709674553420c.nq.gz
    ├── 3835c10362bc6d0038e1f2fe3161e4eba1805c70.nq.gz
    ├── 38de033e488943ecd61a5d45c6fc20584c090895.nq.gz
    ├── 3975557e957bb932d862c11872f3580df588e582.nq.gz
    ├── 3b23dfe5a944c487185f30345be81bb184c9e6d9.nq.gz
    ├── 3b5d6069df6b0301ef220b7f399894eb0527ce9b.nq.gz
    ├── 3d2cd9fd0e6f9969413c6231ab78ae1ccb8147cf.nq.gz
    ├── 3d2e25ba1841bb607b92ba33636fdc1e9123e854.nq.gz
    ├── 3d8abc9fc1aee40137c7bbe92fab43f835fa9859.nq.gz
    ├── 3dc63778e14ae6fd9a12a9fd784474c809249a0e.nq.gz
    ├── 3e67af0309c47fc83916f4dd049b0ca7a847a6e2.nq.gz
    ├── 3f582af32b6002ab8ec743c5c784bf53b943e3fc.nq.gz
    ├── 4075dc7f5681bc1573d41831e12ce514fe3cf951.nq.gz
    ├── 413b3c830cf8cb53d280c8612ab318e0cb548ab8.nq.gz
    ├── 4159ad948a12a5aa418c1e6e543b2794dcc0aaa4.nq.gz
    ├── 417e483bde56cf8a2d8de76e0ca26f7e876137c6.nq.gz
    ├── 42668cf2fd422445c199209b9a20c7e6d146860e.nq.gz
    ├── 43d55f48b62bcf29465309e422218048bdfd520e.nq.gz
    ├── 46430f88f02a80719d05c91bc5c5ae5193efe312.nq.gz
    ├── 468013909821cbb36ea69c9d6d09304bf2407d06.nq.gz
    ├── 4795c26b41b36dbf154f30deca03033e38dba637.nq.gz
    ├── 47c62c4055fbd4cb9f78498b3a9ebcbad0b67155.nq.gz
    ├── 48593de74a47244986705fbaa81a770da08cfe1c.nq.gz
    ├── 490cfd93cae9e5de1dbabfe8985438a9afb255f6.nq.gz
    ├── 495be88d3fa89fc235f059a5c6141ec9db93d7da.nq.gz
    ├── 4967074abc00ae8e97aad0068c111f4c1fff45fb.nq.gz
    ├── 49bf52d0a42a6159ec40cc036412205311c1969f.nq.gz
    ├── 49d2e4a88784df13391a55d89fa8c4dc4225cb4c.nq.gz
    ├── 4aa48a6545c8395c2e92229486264ad82628c4b3.nq.gz
    ├── 4ae9c9f6df1cd6f223451bb06e8d1fb8867cfefd.nq.gz
    ├── 4af734ac0db649c78fd40feff6a43b1ac0c2a247.nq.gz
    ├── 4b740389bcfae3e542f537572bd4d3f7652b49c6.nq.gz
    ├── 4b8c39624af6317dfd62a933b38a273bdc2b9f0d.nq.gz
    ├── 4c6a1c8f12667b30ebf7313a2799ed28321110d1.nq.gz
    ├── 51703b8d00687a6670b26f04eccfe09379e11fcf.nq.gz
    ├── 51afb955dddff4c81d220c54f2e37f56d2501b0d.nq.gz
    ├── 51e9d5d697a14aedc9f33d839bcfa22d75f0dcbc.nq.gz
    ├── 5233f349d5d404d8ca1f8e1e6aa68566ebd5a48b.nq.gz
    ├── 52ab87b76c66299cbb4d2d039150e47b8abb6880.nq.gz
    ├── 52be920ac97a7b52829e90922578fa611f7d799e.nq.gz
    ├── 52c84de85d8f21d7142bfbac83131479015ef51a.nq.gz
    ├── 52cb55e2df5a6956dfc236fe1b3d49f60c433bcd.nq.gz
    ├── 534e0c99093dd795afe8ed705e040e50fa3c5d35.nq.gz
    ├── 53aa545c3357b8008f5f2fc230cc61095e32f468.nq.gz
    ├── 53e88ba080bc96c1c2f4749eb9513dd821616562.nq.gz
    ├── 5430eb0e539d9ad6523d347c2a33e5e6ac5be165.nq.gz
    ├── 5434d3ca0c3b554e3d574ff49d64895962cfe651.nq.gz
    ├── 5445b6248c720c81986a823ee4a7351277ec79ed.nq.gz
    ├── 54d1f4ff3764e1c032ff56c43aaf12e1024ebfd9.nq.gz
    ├── 5610c67f6d8b9c490c9d8c929370357552d39bd0.nq.gz
    ├── 57f2da2d129a70175ec3c9d7eae8480c6954cc60.nq.gz
    ├── 5851a663096aa26bdbe93564b7c55ce3e407c00a.nq.gz
    ├── 590921b5894c9e14b7eec09e8c09b466a7061dfb.nq.gz
    ├── 59e688e764be1feef316301321baba0301a64f00.nq.gz
    ├── 5a718e1db3af9dbd2d38034a39000056db9f3fb0.nq.gz
    ├── 5aa6fc8405be2045bd9303b6b53277d1db2d25cb.nq.gz
    ├── 5ad2884a095fbb2d8a6553e9c1484f095cf1056a.nq.gz
    ├── 5c2b5236cb79a8566cf2b024773a92751cf97f83.nq.gz
    ├── 5c97f1e2410dc0887696f7cac9aa87e5d20736b4.nq.gz
    ├── 5d8a737f0737df438396305b87a3181b953ea2d2.nq.gz
    ├── 5d8bc0c834c1471f08de8ead381dd38b5e9d944c.nq.gz
    ├── 5db9ad7cee8660b9c59be91ea5abdc2b4c1799f7.nq.gz
    ├── 5e3a053020573aa339b52fa2f132831f139ab3ad.nq.gz
    ├── 5ecd91544d6d7b668cc31436e1b5c29e7258c0bb.nq.gz
    ├── 5f7b46871b7a9081c983292e585fdb11bd27248c.nq.gz
    ├── 60625127d75f93c0eb6a97c509c2f334e0ec2899.nq.gz
    ├── 6072cc935f1c1dbb1535df97234d2bf4100a5b4f.nq.gz
    ├── 607f018cba865501f0181590c892148661407120.nq.gz
    ├── 60eaae19550c5eb37ef608ff99ca72e588c71d62.nq.gz
    ├── 615a302e5ad05ec0e476c39db5bc6b8b5389349f.nq.gz
    ├── 616587c321ea47e86dac9d5003121f15907e07b9.nq.gz
    ├── 62eb29b48351f1da5876fe4e5bad0119b2b9e982.nq.gz
    ├── 6370dd03d451fb3a99a8a75a591fbb3d9bafd3f1.nq.gz
    ├── 63a270c2e816b44ae69857279a04c17d23c6f892.nq.gz
    ├── 64130b5308a706d8f3ef0b7a174de6ef04dda4aa.nq.gz
    ├── 6417dec090728878b6ebcc513ffa505781b3d91c.nq.gz
    ├── 64c5fccdda450978e39c50b380ae9bed94fce685.nq.gz
    ├── 64ea9d9e81bc5934c897486f3e6ee12114a38f47.nq.gz
    ├── 65841f98f379368a37b239599154c814c4d197ee.nq.gz
    ├── 65a5bae040b51dca8771b250344517a73cb4e5cc.nq.gz
    ├── 65b56fc12356acb5a37c6188027affa782620a60.nq.gz
    ├── 675370817865c6fe2d633af751f3516fc0e3382a.nq.gz
    ├── 6768a856bde87d972099300587f226d0f8bcb67f.nq.gz
    ├── 67d873d5f79fe386247e672d387a6843f65f53f0.nq.gz
    ├── 685848c8c589b4620df1d77bf319c1a793966c43.nq.gz
    ├── 68ba00dd6c681d2419dcdfdc9c541ac6d05677c6.nq.gz
    ├── 69287bc2b3a49dcf89154a265a65bc2683225ed7.nq.gz
    ├── 69bf3896bd8b4413db3707bb0ce75d3f9f6876cc.nq.gz
    ├── 69c8afc2e1246557ab989e6008385da3dd4a4a71.nq.gz
    ├── 6ad101711d5d37bc92cb5c62c9c6c0c8cb72e286.nq.gz
    ├── 6d338f1fd7251234e6db2924f80201f61cf3ae8d.nq.gz
    ├── 6d57bef6d10f38e669e429d0e0260d868716ac50.nq.gz
    ├── 6d5aabb5068950eb9412b8ed7220c699af6fe031.nq.gz
    ├── 6d7bdb3e1fc0024a3f9a1315736dcfd12a3f3206.nq.gz
    └── 6d8e690605bd6f5233da7ef91d419ef612c7188c.nq.gz

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

[assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
