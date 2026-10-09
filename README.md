# Repolex Knowledge Graph of NousResearch/Gym

RDF knowledge graph data for [NousResearch/Gym](https://github.com/NousResearch/Gym), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/Gym
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2d538be189de0e21c21b85af05acf7646b1b092f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2d538be189de0e21c21b85af05acf7646b1b092f
│           └── chunk-001.nq.gz
└── blob
    ├── 002e9c95cc8471fc9748f2e14201cfd6d672659f.nq.gz
    ├── 00ed83213ebed1708cd6025b54367cf45a09b0c9.nq.gz
    ├── 0188df2ff0e3b50112ab73f69db9664f20248089.nq.gz
    ├── 0193b5337ffab1ea0345fa3a6c0444bd918431d4.nq.gz
    ├── 01a34fc7d9d1c699032101da8cb9e1a7d4949832.nq.gz
    ├── 025490f26463c7289455290b19e4bbeb075a0d45.nq.gz
    ├── 02a3268969113b8f9de2d9911eeb6bd535ed92f0.nq.gz
    ├── 034371a33bd8539f3194e929b541d24017e3c0af.nq.gz
    ├── 038ed6754ad4c92cac9872d26cf0dcd69407ce57.nq.gz
    ├── 043581349457f8e9d3f1814953ba4ea9fc657b48.nq.gz
    ├── 046c389420296c4de18e7818591be8691844bbf7.nq.gz
    ├── 052f55d02ebe2ba5f432a8f9d95d1785df91c5df.nq.gz
    ├── 05487a80db717e274ec406ed7db5386a353a1614.nq.gz
    ├── 05732737c6577c3f9fda6bc60f0176cc4760f07d.nq.gz
    ├── 059152644c768e1036658b0a8208611cd0427b60.nq.gz
    ├── 060c48dec96afc10e9f0e6f28a47e75b49229774.nq.gz
    ├── 065b68e1e1de1786e8fbad4e4be6e8582e373d3c.nq.gz
    ├── 067247bdd9be424c12390340bd4985484d028b6a.nq.gz
    ├── 071f9b7371acc7cdb19592749bc2508ac84840fd.nq.gz
    ├── 07b94c30711719d692fed4f7f25ac3203bffdce1.nq.gz
    ├── 0816162d8f02b9049fdff500dee38b161a056190.nq.gz
    ├── 0836f0fdd555ff5fe6812ca31d1db722fc76b828.nq.gz
    ├── 085bdc30847ac8fa6bc940e3c32b6ecec477ca08.nq.gz
    ├── 0942c4085f691da9f0e61a1c5ac9cf69936684ed.nq.gz
    ├── 09c0b295a632d082acd64ea25810848d7627509a.nq.gz
    ├── 0a4bd92c5dd9cc2a98db30c709d5b14eebf81f7f.nq.gz
    ├── 0a8dbab2084dc4cc5297227903f48daf21ed9bc1.nq.gz
    ├── 0c40f0ec1a4d7df7adba5f4ae202399815396178.nq.gz
    ├── 0cabaf4132653a2d9bbd9792448102411033e764.nq.gz
    ├── 0cf05807629b5d14531ca870a41d1797a1a9892d.nq.gz
    ├── 0d6826a43a7eec469d3020cff896c19a69b3c4e8.nq.gz
    ├── 0d6bc279518c1fda29a7522117ee8d76bf31adf7.nq.gz
    ├── 0f16e4d4a7accf28d5dbd6acc00e880ef0e587f1.nq.gz
    ├── 0fe7f47b0ef9af85ddbe0b06f3b8688b3c591625.nq.gz
    ├── 11311eb435957103133d652ba29a7ca6e617eeb2.nq.gz
    ├── 11a233986b7a69237a27abb72b252134211fc589.nq.gz
    ├── 11f3ce623785e0e813e4814efeea9db28e7c9f3e.nq.gz
    ├── 122dee20bd3a6587f1c5d68d926070e1966e3c74.nq.gz
    ├── 123e227aed456c578060ee8fe79265906ba27418.nq.gz
    ├── 125746c74bacd003c0671541cc776c89634c3142.nq.gz
    ├── 136471dd3dd3720fbeb9eaaf5848f758505314e3.nq.gz
    ├── 1389c580d7ab702275c8eb00095fe20b81178f37.nq.gz
    ├── 13afe166c155322c7ac2da81049a4a4dc30ca1fd.nq.gz
    ├── 13e22ebddae43cedb1ff5a6d7b95d43bc2014b25.nq.gz
    ├── 13e370cd345bdfed63f45c197ca9d17361a70399.nq.gz
    ├── 143ce6b113511e075e8ee83d59af76d3317a3349.nq.gz
    ├── 1460153ed29466b6a9af70b2b83c1afb077fc8f4.nq.gz
    ├── 1479bf692cd7415d32d9395a8bab630f4ad4766d.nq.gz
    ├── 148b7d95f460d02e694f210d86c7a0ce632f2a3a.nq.gz
    ├── 15b7751ce87413dc60dd9c2e9029dbb10bb56e8e.nq.gz
    ├── 15c1fb408e21d34a618b7b3f65625f0ed77e8175.nq.gz
    ├── 1672a56513aed92371a28c8b660b01ac4646196b.nq.gz
    ├── 16b2a3247c06d65baebd3a31e435683fe2f1efef.nq.gz
    ├── 1770ea3dcd2d5133ece93a1a408db9251050b1e3.nq.gz
    ├── 177159f871b2b4ff573c7d245fc9fafec8b0f0e7.nq.gz
    ├── 182c3b727aaf3a01edbd62c18296241c8a9c16f3.nq.gz
    ├── 185b0cb0d553abcffc538d63b3b85a87852b32c0.nq.gz
    ├── 192aa9c20ad6057cb6651ab410876d5678cbcbcc.nq.gz
    ├── 19303698dc1c20e1070d040acd108c3331603ce1.nq.gz
    ├── 19f0cb99a6526dc690523fde78c9b4a0eb279efa.nq.gz
    ├── 1a8431c3e31209eab125755986b2cf5aa20553e6.nq.gz
    ├── 1a8a15a43e61e49796ebfcc653a34c28f4f3095b.nq.gz
    ├── 1b9c713737be59db3ece80a4ff08e6bdef8be7c5.nq.gz
    ├── 1bd9d6532688d3c5da1e9d1598838d5b62a3934e.nq.gz
    ├── 1c193ea4bed4e720af1a44ee3f857e64115cc695.nq.gz
    ├── 1c56ff65c73395df1741d2d84191e7d2f7314e9d.nq.gz
    ├── 1c6f9c2fe80f79c8e637afab9f02f27f4a959bd3.nq.gz
    ├── 1c8fea7738e1dbf8b183ca9288af6a763b0526c3.nq.gz
    ├── 1c9325bccc8da7d7164013d82f257c1e78b7be3f.nq.gz
    ├── 1cdd8238d847b0be7edeb64f9c651c4ae961328a.nq.gz
    ├── 1d192a2850257d5e36c9cdd5978aca36694e5969.nq.gz
    ├── 1d9cd14889477730d8f4f2102b3873ed1cae6bdf.nq.gz
    ├── 1dcf246dc9fa512484caf66ebec80cb43f1c5749.nq.gz
    ├── 1de32862be9a199ddba65933babf5c0e08d25716.nq.gz
    ├── 1de3d354f0394b781ee51c9353ebabdd7d3d4763.nq.gz
    ├── 1ee868d3bef81b6fbc7cd7525ed5039ef505a24e.nq.gz
    ├── 1f6eba3464885f5c7537303b59ef2eff97ae2205.nq.gz
    ├── 201852c36be2aa421c9213e8a107ef0a7b585d23.nq.gz
    ├── 20264afaa0219fab4002eaa3a22b8e5dc0076a73.nq.gz
    ├── 20c5f174a53bbf4b1e8711a8652562476d910c03.nq.gz
    ├── 217ffc40d27eb3f3c0d43e64ca5415e6c7e84fdd.nq.gz
    ├── 21e14eb1cf58d7ff37726b60c1f08bead54f75ef.nq.gz
    ├── 21ed3ce03a1cc3be3057c439d6e2b7bda90e9d93.nq.gz
    ├── 2218c0903d62db3a31116abbc441164148731499.nq.gz
    ├── 22a15a03a2a27d914470f9f749f9f8c907cc5e80.nq.gz
    ├── 22db707d534b97f8fda45d7bb92b4d66199711dd.nq.gz
    ├── 238be2930c3ee5dd0c54572c03c17449e7217b62.nq.gz
    ├── 2395dc3b4230471295bd7138784b34d7e9ac23df.nq.gz
    ├── 23d64e9389e793324188a1d45673496973cc1d69.nq.gz
    ├── 23f145180d2ca18eb87d923ac280cdd0eca83076.nq.gz
    ├── 254962589d0c86952f3fa728b3f94305849e1857.nq.gz
    ├── 25779b9729a1a4df2972489edee63019b2e1b692.nq.gz
    ├── 25edce220b0d3e6c7b67b35f5999d7cbebf001cd.nq.gz
    ├── 271864987d63adf474836a92a329eb45e12b6896.nq.gz
    ├── 27dc547379cfc486afbae2e58ffa2c307718fb15.nq.gz
    ├── 282a6980c44dacaae7da387ebd9e8311223f2856.nq.gz
    ├── 28ecbf236988abad1725c763d8debfbc9dd8bbcd.nq.gz
    ├── 290021ff0f47b4f86eecc142e05ba6d090b7227a.nq.gz
    ├── 2a17e8cad1925b8b018596c08003f843ee54e57c.nq.gz
    ├── 2ab6b05a85bf16566907e2ff4c265d3bd6810586.nq.gz
    ├── 2b4a6c44fefed6643b2e59968347e3013aa0698e.nq.gz
    ├── 2b90e9b90b9d028e368ab04159dde3567b3bb3fa.nq.gz
    ├── 2bacbfca2c32d606030b6fca0e9848a39f195cf9.nq.gz
    ├── 2bb6fc05da10daf4efed725ba34420eeb9f714bc.nq.gz
    ├── 2c9af87ef175906e20ab0b7650453ab17d2e3865.nq.gz
    ├── 2cb3f1bc5b6e2d389373fd9b3d15837eac78458e.nq.gz
    ├── 2d62d10614a17bfe3876cd659e200ee05f536f88.nq.gz
    ├── 2d6bf776a4ff441e137e5702d7a076dac371cf7b.nq.gz
    ├── 2d7bb7a20a2bc7cce5aeaff080a0d31174392a18.nq.gz
    ├── 2e01f14f9259a19b26fb8cefb4f988ddc69e0f52.nq.gz
    ├── 2e340abf20382b284ef889185e58fb8bf93310f2.nq.gz
    ├── 2f3c6d6a24ce6a85249fb7e158ce9a9b8c21dc9d.nq.gz
    ├── 2f8b297a0c2d3d80547372c167370c7cf486c3fe.nq.gz
    ├── 2fa9ef935fe2c149e42b505f27d1c9169073037a.nq.gz
    ├── 2fb35c43a42dd4e9fb79c7a7a2c90c939cae6bb1.nq.gz
    ├── 2fb4e2d9b7708a6b5883ddc66382f48be1be1f32.nq.gz
    ├── 2ffb477ef87e5174b810497a810817bee253a435.nq.gz
    ├── 301668cdde56fc6b35cab7a2d9d372c37a96d2f9.nq.gz
    ├── 30171547f490c8dc22ad000ca7ce49e98a8631aa.nq.gz
    ├── 3159bfe65645499015bd92609b99d476d69544e9.nq.gz
    ├── 31a16678d7c18f71bc3b77bc76a04fbe57a2969d.nq.gz
    ├── 324613257cf9149644d2fdea18760ae49ff260a6.nq.gz
    ├── 32ee4ee2b43efeefd5ba3426f8b271c9e9cd9a94.nq.gz
    ├── 346f0b448b5f822fe7a0227b7b8badbcf70e5ca1.nq.gz
    ├── 34e3aaa8c58fcf77b7fb5f5545a9ba8750349e6f.nq.gz
    ├── 34eb130a2d0b6820d1151d82f7965013d339314d.nq.gz
    ├── 3503b1f264ad0867e301e5cf6129210b4c0c2146.nq.gz
    ├── 3567dcfb53c0fc7fdbcf2a4bf5e38b6e997451b9.nq.gz
    ├── 358a3991d76c49ee43a2b99fed8b2163ba0f1dc7.nq.gz
    ├── 36e3564030de0537acffec7a1be0d06fc1239ce1.nq.gz
    ├── 37218d9e3d9265f592e3890bc369f317d30d4249.nq.gz
    ├── 37ca68d05acf80045f20382b14eaf111a0f67f7c.nq.gz
    ├── 37fddfd37d464486ffbf16aa069a57115629ae53.nq.gz
    ├── 3855b5341c79a57705f6e210140b3e0e4d321071.nq.gz
    ├── 38a43eff8bd8d5cb2b8d26221f4ef342b2102bde.nq.gz
    ├── 390ef39e5704f60b1f9344c51e41a112a0435081.nq.gz
    ├── 393b2fa0463ea3d44a3641e296fb85ee2d098c4c.nq.gz
    ├── 396ca58a9cc855df44c292ccf043bfb762691f42.nq.gz
    ├── 39cb7b032f3d296466a56834318a661913428573.nq.gz
    ├── 3a12fca8e4f2fbaa61d3bc3bfcdb2c96a9363022.nq.gz
    ├── 3a5c7c90a4111bae9220f31b85b07c6373dc1e08.nq.gz
    ├── 3a637cbcc78375ec7ae9856e201e2fe8cfceb3e1.nq.gz
    ├── 3aba777412ff53464cfdedc51ce3c2b4d47aa77a.nq.gz
    ├── 3b1a82c7522295423467badfc409c8c5f61f30bd.nq.gz
    ├── 3e04fa8db075ef32ef97615dae92ae1dcf6082db.nq.gz
    ├── 3e1dae139131cc47b21a7232354f459a9ab416a1.nq.gz
    ├── 3e71b46442014f872df39b6a9d8b5cf0af27d6d3.nq.gz
    ├── 3e97784558e66f1273e8696316ceae5bc83bd2c0.nq.gz
    ├── 3ebb660aaf43e64efa404730622c611b6bd4be2c.nq.gz
    ├── 3ee47efd21fe1d9e35cf081ff5eaf54549f2f439.nq.gz
    ├── 3f552c2573c5767989e9a28348e386333e191a9e.nq.gz
    ├── 40402bd6fb0bd364d11570535cb3c7bcff59bca7.nq.gz
    ├── 424d9460df00ae1306cd661f50b60470e8cad10a.nq.gz
    ├── 425bace0cce20d9f0a7f5e295aee2832caa1aba7.nq.gz
    ├── 43628cce248d635748b98c65bcfc5181f68b4b47.nq.gz
    ├── 4424b6fde073b7129c8c182e0eaced827eee2424.nq.gz
    ├── 447c36bd6a7e33af015e086ae3b8dd83af0ffe7f.nq.gz
    ├── 467079831e16b82ab14d173aa9f6b5fe840fd5ed.nq.gz
    ├── 4713959f6080fce391533031ec7d7db7006f4c7f.nq.gz
    ├── 47d09aaa25f60b59c89ebd53ae66d87109b2db37.nq.gz
    ├── 47ea66fe54cbffe4e20753339fb5f04b4491dc3f.nq.gz
    ├── 47fd6b3b05a02fdb286c2b60cc971b7c324f456e.nq.gz
    ├── 4837b8aeb276e77df02c78e66770f90b501fd7ac.nq.gz
    ├── 4a19feb9ad5a9bf7a5892be5adf30e24804725f6.nq.gz
    ├── 4bd94d4a4424f5b55528f1f308bb00d6cf02bcb8.nq.gz
    ├── 4c3a2c0fc9e5bc26019a9412fa88030f433dfc43.nq.gz
    ├── 4c980b6beb3e6d946a4ffd549340f0a086c133e5.nq.gz
    ├── 4e2cf38089355c7eaa7440f2954c10bc117b7574.nq.gz
    ├── 4e4990cf7f921408018967dcaa1894fe8f33f414.nq.gz
    ├── 4efa071e35d38c043b4e118f8e7891d7ebdcabd2.nq.gz
    ├── 4f661cc96b5bb9bdc634ea68e3816bf5a8929a67.nq.gz
    ├── 4fa675af98dbaa4b0c954ba82fc6c108d4c4f7b5.nq.gz
    ├── 4fb6fe95f9684ff44a94be7490db8544339ce42d.nq.gz
    ├── 4fc25d0d3c9856b04e2b1b565777ed4655415b2b.nq.gz
    ├── 50422a7d3a362aae94473bfceb299c420a652ace.nq.gz
    ├── 51701a62febf2b8ef3d23c164cbc92f081063c99.nq.gz
    ├── 518fa95ccb7f3da9bdded0db0ba03e9b532919ad.nq.gz
    ├── 52a7a9daf028f654d6a02f65c99cc609a57b492f.nq.gz
    ├── 52afeb5ec23ea1bbb7c8c971aa0bcf5cbc67994f.nq.gz
    ├── 52fc16c9a7ffe3485cd19f63190af278d17cc783.nq.gz
    ├── 535b42592c19a4ff4bf3069ffe65c76b694b7ea4.nq.gz
    ├── 53dfd9afb0893ab59137f294f182bd1efe2a5e26.nq.gz
    ├── 53f8b392458e150b18e0f0d00fbc382c53c29bc4.nq.gz
    ├── 542405bfa62569725a56ae3814836199eab72e60.nq.gz
    ├── 549eded01c880c89f0278891e0b30ee23461133e.nq.gz
    ├── 55230fc3ca463355bc6c3d58eb0e5df9c06fa109.nq.gz
    ├── 567e2faf76fce35269dc4aa2493a728fa1fe6bfe.nq.gz
    ├── 573c5b394b69ece5e9132dc552c4b34ae4ad06b0.nq.gz
    ├── 575073b9102c81c1838cbf83063e6b817bdca827.nq.gz
    ├── 57bc08208cce3b4f9c047b0976d96317dd1a92c8.nq.gz
    ├── 5821012d3967dc24bd52de0f28b305f7bcec2a32.nq.gz
    ├── 588ca6cd7d3c496664f4d94e6b6128b8ac9e9e1c.nq.gz
    ├── 58a64272c930012f330dcaaac7961df4de40fe5c.nq.gz
    ├── 5a534665e412e86c2a11000692bf350507468616.nq.gz
    ├── 5a8b160a254302bc33ebaa105e04a790e856eb46.nq.gz
    ├── 5a8efb5f2662b73b5a0da361433f87947202019f.nq.gz
    ├── 5b192affdc926c75cf8625eae59c18ba1815c4d3.nq.gz
    └── 5b842ec31c693835c7824181e0efed49adef46ed.nq.gz

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

[NousResearch/Gym](https://github.com/NousResearch/Gym)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
