# Repolex Knowledge Graph of microsoft/windows-rs

RDF knowledge graph data for [microsoft/windows-rs](https://github.com/microsoft/windows-rs), parsed by [repolex](https://repolex.ai).

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
rlex download microsoft/windows-rs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e4bc9e32508a5de57c771d58274f74568d52a822
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e4bc9e32508a5de57c771d58274f74568d52a822.nq.gz
│   └── repolex
│       └── e4bc9e32508a5de57c771d58274f74568d52a822
│           └── chunk-001.nq.gz
└── blob
    ├── 0007a211caf6556d6bb8ca9f1cf0a244ba812ab1.nq.gz
    ├── 0064ef4b2cf092d70b1bd087853834de580aad82.nq.gz
    ├── 008707e176cfc93160669d324f894edda704b39d.nq.gz
    ├── 00f1a307ad5e469ea84fb5cc9291f5a1226e3a5f.nq.gz
    ├── 012f7ac4d540624c11e909f7c0a6219ee50c61f3.nq.gz
    ├── 01649a1f8e6686bdc06e51709b4c2b896fe08060.nq.gz
    ├── 0177de70b8e0a99fbfe3549865d8355f78eb4ee1.nq.gz
    ├── 01824f3c2cfc3299d6511864e5d242958c50e9e9.nq.gz
    ├── 01e6eb265aa3091f09887f8ad17ec2c9d305846c.nq.gz
    ├── 01e9670c295e792daa32b10b36971ee8dc068831.nq.gz
    ├── 0238e5fd0e85f2e65352f723a7b35a57e48d0d05.nq.gz
    ├── 026422f9fb1c27a73baabeed53e2cf12dd099d19.nq.gz
    ├── 026d63df40a42370d10cfa1d87880ce6104657c5.nq.gz
    ├── 026df4ea01a74841d919f6039dd6c663fe00aa19.nq.gz
    ├── 02af4413d5adfdba0ccd5587faa8baef8d298c06.nq.gz
    ├── 02b6a15d8963572d5276e34ccd200c0ab4f1645b.nq.gz
    ├── 02d5643596e73582588447825c658cebea591ed5.nq.gz
    ├── 02dc0afac3a5b160cfd946e476930bc0725c71fe.nq.gz
    ├── 0377b0ebe7c4ea36b42c508069120bbf9b3ec925.nq.gz
    ├── 0382c0e1ed4c30b40b405612e244489e9e986e09.nq.gz
    ├── 04109a6a6abe92acf7cb887a4a9ed2c51a87b9a9.nq.gz
    ├── 043ad065a2dacb04427a84207a26a646e00b2c6d.nq.gz
    ├── 0461e8c3e4cc06b03abda75217e6cdf9df53ea72.nq.gz
    ├── 046d7f8eac5c06b9e95daa197d63321bb5f28f55.nq.gz
    ├── 048ceebbe2bc624d2e020724287ec3be3c243c90.nq.gz
    ├── 05183b472ba95492680d0d11a0d33166001336f3.nq.gz
    ├── 052cf5044a049218f96115a714665ad5da3c509a.nq.gz
    ├── 053af31675f811b8f487cfbddc0377bc6e3dc7d9.nq.gz
    ├── 05ed5e393a75f9e0de19724cd9a281eaff1a5e84.nq.gz
    ├── 0650d6944e1a78a8eb18d9fbc43a9e18b3b60088.nq.gz
    ├── 06afa1b94561c845c84ceac6195b521d936252f6.nq.gz
    ├── 06e4911b78d25772756fe088db6a4296d313f0e6.nq.gz
    ├── 073ab393ddad2d0dadc00e8f2024bd77dbbef311.nq.gz
    ├── 07663958fed5e81ed9d81f3a8a5b31f7541127d6.nq.gz
    ├── 0776e803e4ce0a86040dbca0db3a2fe2f192a6f9.nq.gz
    ├── 078e6bb0184a914a77286e3e07fe3da4dea3f787.nq.gz
    ├── 07ac15aab55120fc22b2d274645cab4616f08ce9.nq.gz
    ├── 07ae186cbd84605fa881b278bac44af2627bec62.nq.gz
    ├── 07e6c6698c1f9b3146247e88164620ef4062e52f.nq.gz
    ├── 07e95a5b811bcbc6176c458d39ce5942bc0d74df.nq.gz
    ├── 0803c2d8f02d8814115fbde2b33460c9294f4ded.nq.gz
    ├── 084ac8174c6592c1178d457440fdf54cd87d832f.nq.gz
    ├── 086defad31a6c30ea7be75ef4b7d6ba796d35bb6.nq.gz
    ├── 087f1ceacdd2fe5c0cef65440156701f91c36f41.nq.gz
    ├── 089cffcc84fccc68b399d4bf0792df07c0d38fc6.nq.gz
    ├── 08aafbbefe5192c4bfd95d044adfc76cc02abf6f.nq.gz
    ├── 08cce8aaafea1f83ec1467af41409ad74bf573e1.nq.gz
    ├── 08e305afd6b8df311fc87d048526e8b54d7f7b69.nq.gz
    ├── 08eb89673713b792a6e5344804375507b0f01b65.nq.gz
    ├── 08f5c178e121ead53d6e319751a221d9bc4ba020.nq.gz
    ├── 0912037b521c22ea2323b211518b12f020d46540.nq.gz
    ├── 0933823761b1d0401228ad76a465453a87feffa5.nq.gz
    ├── 095bf52e40ee81314f7c8f5c6de0746d904ab95b.nq.gz
    ├── 0976d211b83a46bbce43e483d6d1f97bc9c81605.nq.gz
    ├── 097db442941ae85da2331da73146e44518efaf14.nq.gz
    ├── 09cf0bbf3f306e86805255a79acdb8fb234bcb8a.nq.gz
    ├── 09e692f6b4289a6d27900470e547c5c9af0adf7c.nq.gz
    ├── 0a264b55eaae6786c5a5657317855377db13f6a7.nq.gz
    ├── 0a4aa79f06ecfeaa42ffafff262e4341802d65af.nq.gz
    ├── 0a57f2c1ab5528e7a836c7b7e336e1a545453264.nq.gz
    ├── 0b25026a6dc33f552a4045c5677c3d9d1c05c807.nq.gz
    ├── 0b5d27eba81ecc731fa4cabe061f6aeeb580156c.nq.gz
    ├── 0b9a903b16bbfa837e5646dfc7a751b09504806e.nq.gz
    ├── 0ba3e2dd163dbac346eef2889ef61a42609fff6e.nq.gz
    ├── 0bb03e169abb7ec8ec78a92d2551b20648cb8973.nq.gz
    ├── 0bb2776305aa88c6887ce02e23bdc849b5fc94d3.nq.gz
    ├── 0bc68903dfbe2848b22ec916896fe49d79f468b5.nq.gz
    ├── 0bdb5f38adc448dc231f16f4f3f4b3e3318a82f2.nq.gz
    ├── 0c0815a56f25573212a57c5b52a25cf1a741d668.nq.gz
    ├── 0c523da07a87c9f0e5df3ba16504e3a472b93b45.nq.gz
    ├── 0c9ac1ac8e4bd702086402213af792ae0636d192.nq.gz
    ├── 0cb590b3bed2e3a70cb7c69a6fddf787d276ba8b.nq.gz
    ├── 0ce4f23af412617ed3e1f2c9afef026bab2ede40.nq.gz
    ├── 0d0eeff0e6edd6c13edead68534eb4d9c5649ec5.nq.gz
    ├── 0d13333788a7e9ca56a1b1660f9e8437e8403fc6.nq.gz
    ├── 0d24d1b96d4b04824ca48d9b958252df60720cb9.nq.gz
    ├── 0d46771dcd9d7ec9fd835c5c05223e96d89e65c1.nq.gz
    ├── 0d87dfc23841e7a93874546fb8cf3097fbed81fb.nq.gz
    ├── 0da67f3cce73d4ec5cfe0a36b1380801eddb6bc4.nq.gz
    ├── 0dd49714eb1076ae383144150d030718d47bbc5f.nq.gz
    ├── 0dde5778a9341646e68448fb96e6524201007d1a.nq.gz
    ├── 0df6d9adb82b8a853833a77d10ebd59e2cdbb96e.nq.gz
    ├── 0dff8e3ab43ac02f590d54c6d3a5d160f4152d81.nq.gz
    ├── 0e4a0411658acf0f97f8b4abdfe8d6aa227c40ec.nq.gz
    ├── 0ecd433b09bfece2c6683beaa95cbe47da00423e.nq.gz
    ├── 0f566557bde5fa845395a0819bd47f39ff2bd61c.nq.gz
    ├── 0f7b3f6714ab0ff170e67205598946cc833a5fa3.nq.gz
    ├── 0ff392079179ab631d7e8ed955be70c5af370b29.nq.gz
    ├── 1017bd218e9176bace99b865680fc2cca44ab341.nq.gz
    ├── 101a20964e63b44b46ad7128e9ab8033ad360ee4.nq.gz
    ├── 1036fa9b3b19c8581b429a092e118b1ef2d8b8ca.nq.gz
    ├── 10cb107972d377e2ea4f4429a47c3e30ad078724.nq.gz
    ├── 1160db5ef842bf9b9806007bb9de8c47630d92d3.nq.gz
    ├── 11617686010255be3d9b5931914e029323cf3da9.nq.gz
    ├── 117342584c66a675a03544a08e6623a028743ad8.nq.gz
    ├── 118d5eea5328b8f68edd87c34e898cebb9e240ce.nq.gz
    ├── 11a5ac0a602a9193a2c4d030ffefd9fbb7ee10ff.nq.gz
    ├── 11b4853ff2899e074a16300f3ac739bbaf80318d.nq.gz
    ├── 11dd6b46f92c14e0b09ceca431ce2ccdaa2c7a32.nq.gz
    ├── 1244e2ee2bfa193ed28a9ada76af206d10bd63df.nq.gz
    ├── 1249c4f3c92fb43d66a9e5ae6c30c9e69befadbd.nq.gz
    ├── 126a9b2b539f160cc998f230bae292e49f579478.nq.gz
    ├── 1289cfd1f2f6371875367f6eb6e5dc497b6ad9d5.nq.gz
    ├── 129c79668e8ae5e868496dd1f744ae97bc2a2602.nq.gz
    ├── 12a90b595f3ad3c4fe876e03bb1f751167cff509.nq.gz
    ├── 13f0647db5551ae30d9b5d6bd4ba839cf48cb79d.nq.gz
    ├── 1460101bec3454e96cee5d920e2585395552a1ba.nq.gz
    ├── 149865242f1f38a5db8008947b5d9eb146df1c8a.nq.gz
    ├── 14cb7adb7a81dfca2b3c2755f0b91579e4754523.nq.gz
    ├── 14dc7df6360a44552d81c4c7fc0d17032456efa9.nq.gz
    ├── 14fc091c2cb5c0eeb509d309b98df216f332baa3.nq.gz
    ├── 156cf929339302a9d63f1d4d912c924349ef5dd1.nq.gz
    ├── 15807e2695a5fe5612f598d25d00ef77c190df29.nq.gz
    ├── 15b5fa15191ccaac225e039956055a29a700dea0.nq.gz
    ├── 15f203c4df9c0f8839f0ee0fd95b9a9c76ff73fd.nq.gz
    ├── 165500d7fa806c3d2c24b84a4ba5b4dbe1bc91d0.nq.gz
    ├── 16a0a3acd2bf9f934d347a86595b46a71685a5db.nq.gz
    ├── 16ba8fc6d2e87d16a8f8dde642d89c6e7f3dc728.nq.gz
    ├── 16c1caa6ac9146f5ab535f33725b2f1164c6a4c8.nq.gz
    ├── 172d27158f1683c85e34da831f26cc224659bc58.nq.gz
    ├── 1745de7878cdbced4e886f006c3b427e7425b034.nq.gz
    ├── 1750c5a82103c6555c39ee93e1ab65c4080d9157.nq.gz
    ├── 17d13b31f3b6084cac510ee1298d913671dcaa40.nq.gz
    ├── 17f34027113bea029cff8e91022cd6d585768986.nq.gz
    ├── 1864ebbd8308bada5a4bc45c7901226153ff9c75.nq.gz
    ├── 1881c055717bd2df893ef3075da0f4b5c09f1150.nq.gz
    ├── 1891fa0caa6d7d079ca3ec8088bccb56984e2914.nq.gz
    ├── 18d24345bdd0128cc4226fba20a853499b508da2.nq.gz
    ├── 19213e7b3cd26457a8152d84bb3b4a92f5ee5d43.nq.gz
    ├── 192804a511e50150cf8010e8991a103c7a05c57f.nq.gz
    ├── 19a38c2a31eb8e9696da879acf2beda09d456e3d.nq.gz
    ├── 19a892ff61f03f705926e09af50d7579fc921398.nq.gz
    ├── 19b09936c8143d32b4cbb6df1a12990698e2b305.nq.gz
    ├── 19bfbf64f40a71a33198dc8f855385f78ed2e23a.nq.gz
    ├── 19bfd72a7b039bc9424253cb49b98a88f7da3496.nq.gz
    ├── 1a3ce66fc29bb3cb215ec15080df7e77552ecb63.nq.gz
    ├── 1a7c4fcc5c1f47d0dfacac019e4aa5397d88a18c.nq.gz
    ├── 1ab0a5cb759126010b502c6e2df157a67398817c.nq.gz
    ├── 1ad4b05c6726a2276c60a95f5f66bb33a118e4be.nq.gz
    ├── 1b0abbd0dcfb6327457bc230438a10aaa4ee201b.nq.gz
    ├── 1b52e51081bee82fdadd8a20c596b84157091d50.nq.gz
    ├── 1b883f2c61bfa337a0e8fc9dd16fe59c40a19323.nq.gz
    ├── 1bfcab2a80950960f28533b8d4f6702a616664c4.nq.gz
    ├── 1c1792a07fd4a190be1363d44ecccc06e3f3ceba.nq.gz
    ├── 1d1162768aa7f744080c980c24c4100c3e24cbe3.nq.gz
    ├── 1d27cf02b521e756dee9833c08e05a14812da38a.nq.gz
    ├── 1d43504ea5f886c30f1d5c8154277c619b4ce28c.nq.gz
    ├── 1d6aed1aef34936e6571fb5ce0edd8520a1de778.nq.gz
    ├── 1d6c3768c602a41d6bacb9b69683680c9d6f27e2.nq.gz
    ├── 1d9e1f8dc5068ec5e9f5fa17f7ef8e6981c4b1d6.nq.gz
    ├── 1d9f38c57d63f197d552a5283424f75f885bb1c2.nq.gz
    ├── 1deb52109114c4684b2fb681eb321d56dfd0f7a3.nq.gz
    ├── 1df65463dd3c602e0ef9282be8e34c7fb95f8f39.nq.gz
    ├── 1e261cfd7614f36cd53d357a9b564422a352f5e1.nq.gz
    ├── 1e5185b5d9525d9142df8f5e0cbdf7505d93bc8b.nq.gz
    ├── 1eb892ea0bde894f25a904d327c2c42fa6e9937c.nq.gz
    ├── 1ed6b6f0abe9bc46bf7373bec520444e2eba0148.nq.gz
    ├── 1ee2a0d4dad14cc8a965bd161dcf6a8ecf839e1c.nq.gz
    ├── 1f3a0f7a42683891a304be96872e1ddf8e700ae9.nq.gz
    ├── 1f44c60e306b79aa297ae7eb4fad1423890ebda2.nq.gz
    ├── 1f6b5618f5f8f9f8e69a58c607c51d1c22e786e5.nq.gz
    ├── 1f7b2b9ecfd8ff5eb0499a353740a6e473de179f.nq.gz
    ├── 1fb176065cdf60bc1eca81147b5c87d9c875f4fa.nq.gz
    ├── 202198db99d764f2091bb6686c0054fc18713210.nq.gz
    ├── 20254dda734eb66beb9668bf76cdbac8cd41a919.nq.gz
    ├── 2025e893b64ed2a2d0d7c6a247c83b0d31b10e84.nq.gz
    ├── 2034cd491c90f2a1ec6d2a820b262005c79ef94a.nq.gz
    ├── 2049fcff1e553fef2961111708c1ca2969cb3f4d.nq.gz
    ├── 207102991dc558bcc6c79e66de3b23493947c151.nq.gz
    ├── 20bb86839bc6f7282517b24bd63af28a8a031828.nq.gz
    ├── 20d2766cbc328fb87ac189170b1bd73088d1837f.nq.gz
    ├── 20d44a0c9655ed21a835238718988a6c264b449c.nq.gz
    ├── 213b1567407409558164a32aa94a01ff32e61f56.nq.gz
    ├── 21459a170a3e38b4f7b4ec5783ea5837f21f4ae4.nq.gz
    ├── 214ef64753facf8ab42dc3723a6a5d61b3d7eca0.nq.gz
    ├── 21c5c677c482bae6c5259b63d53d2b42570619e9.nq.gz
    ├── 21c8b9d38392b801ca491fe19422e1eb48675411.nq.gz
    ├── 21cacb99d995442f74664a049b19410e75e61d03.nq.gz
    ├── 2213067209c4e466db4eaa29a0b62ece04af9feb.nq.gz
    ├── 2263618819f62ec237f7a30f62a9a4ce87deae63.nq.gz
    ├── 22de444592c76efa1d05e1698e8bb85c5a8dab6d.nq.gz
    ├── 232c7583ff8b0c8f24bd09a0af0dc3405a5129d0.nq.gz
    ├── 235cda941abec39a5c723be2e3ed68c40f9aa314.nq.gz
    ├── 2361181b2e98efdc32f6188616434a606ff78ebd.nq.gz
    ├── 2386d3dfcb1ffafefb932194702e238464061769.nq.gz
    ├── 23cb22794349df4d2cd50e8b0c5818e475f05bc8.nq.gz
    ├── 2437efbf5dd30e4b450860b2ce034f6f6b9a06b1.nq.gz
    ├── 245a15f69646656cd0d35996d95927e52f7b3975.nq.gz
    ├── 245c6df21fd1b7ba9c1834edcd926c328771d03c.nq.gz
    ├── 2538e077015e0ec142da0f865f29b704e5b247d4.nq.gz
    ├── 256e865f0e25f7b57f263e9576ddf3345ffa4495.nq.gz
    ├── 258432c461e02a7b8798983663aeef3da3fb0333.nq.gz
    ├── 25a0a9d2661a23ed4fd2657d2932936b56fba2d2.nq.gz
    ├── 25a0cd6f7143fd54b0ce7cf5f42c533c9db13829.nq.gz
    ├── 25bc5953e81e3941a398d716d6ac9e882c80e2a4.nq.gz
    ├── 25c59d6c78a4c81604fa6e72da66b3c1b5b1f0e0.nq.gz
    └── 25e930eee74d90ba5417549ab5c0ac39732e0948.nq.gz

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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[microsoft/windows-rs](https://github.com/microsoft/windows-rs)

---
*Parsed on 2026-11-26 by [repolex](https://repolex.ai)*
