# Repolex Knowledge Graph of Pythagora-io/gpt-pilot

RDF knowledge graph data for [Pythagora-io/gpt-pilot](https://github.com/Pythagora-io/gpt-pilot), parsed by [repolex](https://repolex.ai).

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
rlex download Pythagora-io/gpt-pilot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9b763fdaf0020c7d8abacc7b58b2b09e57494623
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9b763fdaf0020c7d8abacc7b58b2b09e57494623
│           └── chunk-001.nq.gz
└── blob
    ├── 008a7405f28b2efed3df8624eb01af7aa6612c51.nq.gz
    ├── 027b117a41bd16c595d29ffae255dc6250fea1c5.nq.gz
    ├── 02908a40ed57cfe08851da35c9dcbe65763e1c6f.nq.gz
    ├── 03f938e0607803acb0a846a28c80a23f09f0c0f4.nq.gz
    ├── 042a5b3b6e673405c87d515f330d361e0469f75f.nq.gz
    ├── 042be28795b0b0a22d46eeb4bee941c8a5048506.nq.gz
    ├── 043a340ada718beb3f84816eecaaf5f0ebe8b8c3.nq.gz
    ├── 04c73b4680af6835929e8b3283b863f1566ad7f2.nq.gz
    ├── 04dc3ca27c08adf2f33b2dc41159dd4210858b2f.nq.gz
    ├── 04e8ed25533ea75bc9dc98ff9a75224c5c885ee8.nq.gz
    ├── 06049c193205333ddbb482538153eeb65b39ebf3.nq.gz
    ├── 066c7e7852e6b9e183cd09040aa0dfe5f4d64108.nq.gz
    ├── 06b8692b197e1fe9be79777f09d29a77f7540fc0.nq.gz
    ├── 06bf365db327f072ae26d167f247dcfc6ac526af.nq.gz
    ├── 077ff52266de3a48329b828f1821a86adb9b174a.nq.gz
    ├── 079f70191736f1beb1078d9b03ffb1691a82dc63.nq.gz
    ├── 08986c534bc03ccf4fa21241986f10600b3ec755.nq.gz
    ├── 090e82969aba3a1f741965a112f5d5501a91766a.nq.gz
    ├── 091cf7c17fdb792b1def6bd01b7ec1354f29d4bd.nq.gz
    ├── 094dd94a77ad32a408237cc611d6b38371b190ca.nq.gz
    ├── 09e7b0b9280f103381132869c063a16c6f58f161.nq.gz
    ├── 0a5e39af60054a085cf6076d2e8aaae033cef296.nq.gz
    ├── 0ae2c27b2c585763e42ca8d5406b9a8f49afd362.nq.gz
    ├── 0b7db8019bef464fc13df6e81cacd8f2886dd08e.nq.gz
    ├── 0bfffda7d73cad64489193efa53c08b993cb9c6f.nq.gz
    ├── 0c2f50846736dd80afdaa1dfc556a44331f1e241.nq.gz
    ├── 0c3cbca186f0bbda13ca787bd7adfd1d6056a7d8.nq.gz
    ├── 0cea71cfae1af45e18730f39d6aeb2cb7e3fdc76.nq.gz
    ├── 0d380dcd2d9aaef0db82e08faab846c12e2a4253.nq.gz
    ├── 0df1f1dfd9acc5e6b368917c134df10aa9d91bff.nq.gz
    ├── 0e1a76aa1d901a3706f19415694b433baf930390.nq.gz
    ├── 0e2f58250239f005a215f848fe34bf420bfd5a45.nq.gz
    ├── 0e7e27b8502cc3a1b95cf78910718284aba1c58a.nq.gz
    ├── 0edbd9f6a7cbc1086c43f4f289398f183e509606.nq.gz
    ├── 0edf725903fd7643be575dc7a92b71f8ded385b6.nq.gz
    ├── 0fe2700e6b735b499270fda760e258491c2bce25.nq.gz
    ├── 11cc8717cd28169201d9eb049e9d372dded095cd.nq.gz
    ├── 14298001465fbbd1a760920446d246cf8ff07444.nq.gz
    ├── 1456779b0ef49157a39e1a6c31faccf533817e7f.nq.gz
    ├── 14f92d0b862e26a77657b4e884fd2c7c4cdfbeea.nq.gz
    ├── 151865e7489b1886e5334ceaadf9da33ea7b78ef.nq.gz
    ├── 159a87b1dd6b8a9142aff1f6f17bcf06b9b366fe.nq.gz
    ├── 16f5d406e0583a9b4a16b8ec96189e2822911e7c.nq.gz
    ├── 16f8aadc7f29d8ebe6c8fb833fd7c5e8277af6fc.nq.gz
    ├── 173c3a3fd6d7a0dea14da15d5a5a332ffc9cf300.nq.gz
    ├── 175a2b0d8dbb3d5f00d03ee8954e47400ba974ba.nq.gz
    ├── 1874bb5cd15b1e08a023f56320c5edaf2d5fbf06.nq.gz
    ├── 1933ab54ab640f01204bd085c6510b3325cbae89.nq.gz
    ├── 196c3c7e07898f218d92355db88c5cc219b36bbb.nq.gz
    ├── 199305c2a64fe61e3decfa080012eb9533a1e41a.nq.gz
    ├── 19f201d6ab9bd15ca5219a454a1d80fee5c30430.nq.gz
    ├── 1acac014d4907d55139cad66cb1d5adab35d92de.nq.gz
    ├── 1b889c3336f9db05a1868bfd9d32ba686fd067dc.nq.gz
    ├── 1bb2e5138ec7143eeaf3271b7a1be49487e9653b.nq.gz
    ├── 1bca66fbab8964b5a8ac7eb794363ee0dd6a95c7.nq.gz
    ├── 1d66c47596ead6fe0d4d4e2a4b53e0eca4c43aaa.nq.gz
    ├── 1d83c690a6cc0edcfba14311504a60217b45695d.nq.gz
    ├── 1f16d367c133ea7e1aaed46aa88b69b34c9b0ea6.nq.gz
    ├── 1f7d4d7b159a2b5e1ff35381c975286965a3e366.nq.gz
    ├── 2021abdccf5264a4d8fa77d45ea58caf93bb8bdf.nq.gz
    ├── 204f644eb9450dff70d9f0114eceb737a9d86f94.nq.gz
    ├── 20aa6031c9b2fb524feb6f39a92d030ecbb2fd4a.nq.gz
    ├── 21ffda862db56670222e1d870e739d3b03ef1c28.nq.gz
    ├── 242be94c3f84ff22affa3c0799e550bd7b668eca.nq.gz
    ├── 247f47ee4bc7009fb35ed62bb51707207cf7fa27.nq.gz
    ├── 2500e9ef991e500cc8d624a3d2cc3432045c10a3.nq.gz
    ├── 26c80e16bd9bc3545f1019014cc7db4b1c741e6f.nq.gz
    ├── 26d2f9a781f4fd30ae91a2ea0744d9f05d3a93b1.nq.gz
    ├── 2841d2dbbd09134a1e54a88eafa3bf254777b82c.nq.gz
    ├── 2897458662bf059e6c5b6e99b4ad6227bf0151d3.nq.gz
    ├── 28b8c8deb664e6bfbe3887e48329d89292e5c307.nq.gz
    ├── 2af9a8b49569271b49e8caaabf92668d05e1012d.nq.gz
    ├── 2b0fe1dfef3b17850bbac040665f514a8ffd0f15.nq.gz
    ├── 2c8f3fc87124695ab4759e40960d32b904f14c4a.nq.gz
    ├── 2c93e94f9cc04a49b9d6370ca4792d3d0cdfc358.nq.gz
    ├── 2ca25c0d029cc429df5f40b9b18795ab3dc0f4f3.nq.gz
    ├── 2ccea96b53ba9ab5d2694a2819be64b5f27f4947.nq.gz
    ├── 2d564e8237a09c95203b03011710080061024faa.nq.gz
    ├── 2df7e37d473bf4fafaca09e721e853ae3f51087d.nq.gz
    ├── 2e7af2b7f1a6f391da1631d93968a9d487ba977d.nq.gz
    ├── 2ef8a476d6412a144562d6704a32769c803caa17.nq.gz
    ├── 300bbe450bcea13f28482d0c34996a9b77d37226.nq.gz
    ├── 3064d1d0067404c17aee554367eec87ccea2f5b5.nq.gz
    ├── 308bb85ddd48ac3d7362d8500b1f7d78de7eceab.nq.gz
    ├── 30c41eac0eafffb863a7da21b62bd8a97aeb5a69.nq.gz
    ├── 3384dbac59f91ca84f5cc36006c29a0e5b2d22ce.nq.gz
    ├── 33d9d26357a85d05f83583625d7e6ac52f85ead4.nq.gz
    ├── 348ee3e5d6953b8112e3f37845d6c33519788b11.nq.gz
    ├── 357a10fac02f55ec887398fbd273c3ac1c921511.nq.gz
    ├── 35ff1df3a640beec696704c71498049bb3c99cfd.nq.gz
    ├── 3704c9303a28c01abd5dfab3d0fe36fb9f37bccc.nq.gz
    ├── 37ad93b3ca544089d145663129e23fa20fa5c128.nq.gz
    ├── 384ff0f6dadb830a1747ab5a98c5bb68df4078c5.nq.gz
    ├── 387151180ec2443fa51a6992fba72f4db0b9e8a7.nq.gz
    ├── 394c3a1c4e5716141ebd950f4f7150b3c446e673.nq.gz
    ├── 395bb2d28da8f837d2cb210c4b10f85624d51712.nq.gz
    ├── 39cc638e941396ea1dcf99d0970fa1a459084dec.nq.gz
    ├── 3a4279a43ad6a4d67fdf5ac9f4bc1be2962de813.nq.gz
    ├── 3ae00d93a34143d0d59b4f30561eb76bdd2d85c5.nq.gz
    ├── 3b490b4e134512721b00f3dcbdebce5074292ceb.nq.gz
    ├── 3bf0e485ddede5c8c7f5a6f59198246a88f50204.nq.gz
    ├── 3cc4d4affdea859854301016534b6db30d90ad3b.nq.gz
    ├── 3cc5af6c97a89301a7f5f614b27ffdfa33562bf8.nq.gz
    ├── 3ce5a5d9f5e55fffe5d33256ffb19627aaf1cbbf.nq.gz
    ├── 3e212e1d4307a332e8511f530bc48a4ad5ed6f95.nq.gz
    ├── 3e22c7ae30b63e60317a9c9c0da60bf4a312ca5d.nq.gz
    ├── 3e2343e54f3ff32b87bd14bfde40eb0c9f799bb1.nq.gz
    ├── 3ece8cc1ed07cdf559c70d8a7b6adb4c593fb21a.nq.gz
    ├── 3efa726f843e64328cb241900f5475cee2b2eca6.nq.gz
    ├── 3f8aa603a8fd165d4daec2cc10934428e3c59109.nq.gz
    ├── 3f9daa1438392cacadad6dc8dda62f46e1438b9f.nq.gz
    ├── 4014cd73b393b639f9ae11a05ec519a360ca52ab.nq.gz
    ├── 41756d2dc840f09fe177c842bfc398aa7d2a8506.nq.gz
    ├── 42fee7d1fd337a0423976929e73bf0ce6ca2bf48.nq.gz
    ├── 455581be2d08060364f994848fe41ed6e31026a0.nq.gz
    ├── 45715d8fe0c98bbea8133e57e63af8e4d113e8a7.nq.gz
    ├── 45ad34cf0530acf2952b080882347c09ef43900a.nq.gz
    ├── 45df7d6143bd13dc92c666328a5b392526ed3de7.nq.gz
    ├── 460d2769acffba4bb3ed4342b80504132f783e21.nq.gz
    ├── 464e65079f7483d31324dc1a74816ad84b81fcfd.nq.gz
    ├── 4737cdf363e18010ebadb378d885bbb7c5e43ac7.nq.gz
    ├── 48550906fc2f9adaeeea7c59e00550ffe60841a2.nq.gz
    ├── 4865d2383d40c8d8cb1d24452015c4c2fcb6a8ef.nq.gz
    ├── 4a94a8257c7473e186a70c67eec6d964819c6087.nq.gz
    ├── 4aaefccf253b0a5f3df08aaa414a20bd0367c78a.nq.gz
    ├── 4b1feff3502f100963c08ca9bbaba454b8f74506.nq.gz
    ├── 4c135d1bc4369f6757ecef4bc632e38a814acbb1.nq.gz
    ├── 4c385d34cc2f920b68fb40fbaf8bd935906e0514.nq.gz
    ├── 4c543e6f11f8df34ffe5c3731059ac92b153d79c.nq.gz
    ├── 4d2b1713c349ca169ee5100f687e589d04914dc4.nq.gz
    ├── 4e9418e9e2d0a9e388c450f2532fe0b6084a2e49.nq.gz
    ├── 4f079ba86d8daae1f0b2be8ba4a4645d918f3991.nq.gz
    ├── 4f5cfa8e6c75271958add381b8fb83a395183c3a.nq.gz
    ├── 504afef81fbadc8c0a072e1ac93f1376bca7f4a9.nq.gz
    ├── 50974616597fa78bdd362753d0077b3e3c6e619f.nq.gz
    ├── 50d83840c55239e07ffd4f627860a10074057b0c.nq.gz
    ├── 51e408c7f73747e8f7553c921898ea2e020125ff.nq.gz
    ├── 51e65d7c426f811f89a8167cb7541019070aa6e0.nq.gz
    ├── 521f2fe1cc63b86ae1dec85ceb7f422e8a2e9b7c.nq.gz
    ├── 522f6075b80c25c231a4dfcdcf0bbc0c5d12d60b.nq.gz
    ├── 5367d58639beb1aef569816897f3ab7cfd8deffa.nq.gz
    ├── 54b39dd1d900e866bb91ee441d372a8924b9d87a.nq.gz
    ├── 54f586422d9d4e05bc4ed9f6c220ab69499e698b.nq.gz
    ├── 54fc5d10dd8423839ea9d9cef0b15a4743e8f89c.nq.gz
    ├── 55e338b75cca732b0b3f2933852dff32367ab532.nq.gz
    ├── 560610d46ac571fbd4e400bbf6476d094fbe7909.nq.gz
    ├── 574a616649c3f5c7ca7256b1781d18fc4cbb3ca8.nq.gz
    ├── 5a25ff0fd2959de7bdf3f333ce7ff10c320859f3.nq.gz
    ├── 5a33944a9b41b59a9cf06ee4bb5586c77510f06b.nq.gz
    ├── 5ab1ee599f84d6f363b7e48c059a919be32cbed3.nq.gz
    ├── 5ba7fc24979afe19650cfc11d4accf379bd19d27.nq.gz
    ├── 5c16cca1fe32ded0779dea55ddcea8f906854a55.nq.gz
    ├── 5cdc74083b8c1992268de4eab7a55824d8b80e64.nq.gz
    ├── 5d76dba8ce20f65676ececb719af836bae15acaa.nq.gz
    ├── 5d7ba46109ced7a8062138753c522f74594e2184.nq.gz
    ├── 5d8046850e2d86f91eed37d7be6a70b5991fa301.nq.gz
    ├── 5e4e079c22fcd7d8c067a94263ab1812b3df4499.nq.gz
    ├── 5ebd9245da6714f630398db9fa553e2fa642e3e2.nq.gz
    ├── 5ee09e201fc5bf8239e3a7c2008fae1656df3d61.nq.gz
    ├── 5ef258597fc2e4e288939dd3a3209637b4362196.nq.gz
    ├── 605a4d39a55a379d8038837916cc10079309f3c6.nq.gz
    ├── 611b1ed2b9f48fd593ed9e719510ce8056a0bbb9.nq.gz
    ├── 612b9a94066783acbd1a783ab2accecd61a75a39.nq.gz
    ├── 6223fa4dcb235d3c3844fd5ec83f29cfcac380e1.nq.gz
    ├── 630b2fc89604ac4dc649128c924f79cdf3adfb64.nq.gz
    ├── 63328ed485502d0529484d0de4f39138723c5f60.nq.gz
    ├── 64e775bfcf894144017bb18c9d481d7327872937.nq.gz
    ├── 655466bd034b224afe83a35dd81e498b644efda6.nq.gz
    ├── 6661c13ae8695f5f951e41033f9f4ab3ce6cad11.nq.gz
    ├── 667ce857d4bbfe1309154b2355bc9035c2e29400.nq.gz
    ├── 69a7f88ec2a5d935fddfc1ee680e54d22646435b.nq.gz
    ├── 69f4c91a1f9596d7ab14d19559ab5efaa494eafc.nq.gz
    ├── 6ba0503aa57ab28142257cd69f1ac41291f07525.nq.gz
    ├── 6ca2401556c7f438d49eb273bbfb0b3dfe10909a.nq.gz
    ├── 6d1e60a23cc802bcc7ac3c9b93b3637273a8dad2.nq.gz
    ├── 6dcaf7ce0ac372c68720f783dbebee6f1a474743.nq.gz
    ├── 6fd38704125605d48498e45e13cb8f2b630cb400.nq.gz
    ├── 70c869d0605fc01d7860b21716b91d8d4f9aeeea.nq.gz
    ├── 71d954261c6ad0e3f12223f2c7f20b524a7447f5.nq.gz
    ├── 72135e3b0daf65d2533b8dbe7cfb6131cc1a7237.nq.gz
    ├── 72317e95dc56c2a43cb76e9f63c7f502baa858a7.nq.gz
    ├── 73c906902ea7b3d070983cf6ff69d0f45578e0f1.nq.gz
    ├── 73cbe288514be1000ee1789e203d0fe21fd85ea2.nq.gz
    ├── 74887def946db0da0a8eb754bb3a6acd7bd4eef3.nq.gz
    ├── 74b7ed92444b609c5c7ee50d5b9df9d4555f41ab.nq.gz
    ├── 752ae3d494bfef3ac874d72ef138dcf2d1a5266d.nq.gz
    ├── 758089d72351c7ca7b78a4ff075ff6f39d3b593c.nq.gz
    ├── 76253982c408572697d0134317887a2244d842e5.nq.gz
    ├── 776a8af80ec7300a44b82e547799b41d21ac371b.nq.gz
    ├── 777a275225c6e9ad596e5e08c4895dc31a89e37c.nq.gz
    ├── 796766dd1e010e45f7cae64a72a016f5278976a8.nq.gz
    ├── 7b3a54798f2dbfc40ddf98042ba7a95faa527ceb.nq.gz
    ├── 7b61cd42d72221983ef97e00094350f60fe50086.nq.gz
    ├── 7b84964db4e75c22a20ab62493892b0566915607.nq.gz
    ├── 7d39d60149ed457958c4b640255bf6a025df3354.nq.gz
    ├── 7d6952045581824676ea85d48c914be9cc77bdc9.nq.gz
    ├── 7d76cd4e53377aeace68b81590b36ab776416da3.nq.gz
    └── 7e2839c35300b8fd78d95a0b87ce71c04bd0cab7.nq.gz

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

[Pythagora-io/gpt-pilot](https://github.com/Pythagora-io/gpt-pilot)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
