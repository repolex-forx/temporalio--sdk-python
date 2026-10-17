# Repolex Knowledge Graph of temporalio/sdk-python

RDF knowledge graph data for [temporalio/sdk-python](https://github.com/temporalio/sdk-python), parsed by [repolex](https://repolex.ai).

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
rlex download temporalio/sdk-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── da794611dbfc746ca27c65385d00d9089de5c57b
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── da794611dbfc746ca27c65385d00d9089de5c57b
│           └── chunk-001.nq.gz
└── blob
    ├── 00025a52293eed2a4026c6a97361a3fadbb4ea4c.nq.gz
    ├── 00714526a3c2a64fcf8ee37adf24379629f9e292.nq.gz
    ├── 00a192e855fff4588e60b6f1f204c0ec7bc12477.nq.gz
    ├── 03a623c21eef32eb7c74365f210a7aafed2c24f6.nq.gz
    ├── 04e5e98f8a3128bd4cbf522244047a516fe78e0e.nq.gz
    ├── 05628a7f2cd59e947dcc2a81c13b1df773979646.nq.gz
    ├── 057b301e4170432ef290787e0d5d33c73e776a60.nq.gz
    ├── 0586a752b88b2ac496071acb216139e4790dd57b.nq.gz
    ├── 068503e9e14ef30d1946f51880a457fe8948aa5c.nq.gz
    ├── 06b1546b378850e3676b40efe08f916cf91364d6.nq.gz
    ├── 07e866cf5600447432870e5efe95ebf55a642c10.nq.gz
    ├── 0890a547ae61b054e626f705a7d3806db8312ade.nq.gz
    ├── 08e0bd3da1c803840e45a0b3a9224c9a11b4410f.nq.gz
    ├── 0af468b44fedbccb8213bb4e3192237fde49d254.nq.gz
    ├── 0b21d19876ba4822b1503f51e4d6eb4d3ccb17a9.nq.gz
    ├── 0b32394d37cfca192cb3788d8a2b3f32dad1def7.nq.gz
    ├── 0b9e4a6cab3ff56b0e0a57dcc4f5fdee33520a38.nq.gz
    ├── 0c97f5f9b78bf79f7307058764e35b5aa3a80cbd.nq.gz
    ├── 0cd652d86bb1e914258f1f2444ea885c2db45467.nq.gz
    ├── 0d663bd976f7b9287b31abac0cc41ee46562dd15.nq.gz
    ├── 0e09839dc9adbe9d8aec6f6f977b08da4d17fe54.nq.gz
    ├── 0e315afdc96aef68bbd2f1ea0cbb54b6debf6f49.nq.gz
    ├── 0eca3edb3a8652bc449683ff9548adfc4dbe59ee.nq.gz
    ├── 0f7296d1bb15665ec2dc75c217b1348fcafb7a8c.nq.gz
    ├── 106b351ef0b11353725a3b1fe59cb28c46fe073b.nq.gz
    ├── 10d5c6b5459ee0a72fbeab7c8583fbc0351e732f.nq.gz
    ├── 11f748c9b92dc5c58a6847d23eb41a1a07256140.nq.gz
    ├── 120c25782e3ecd1e479860ae5c768ad9ecccc432.nq.gz
    ├── 132a4b8f0f53ada4a8f4b288e6f534adaa3b9f7b.nq.gz
    ├── 142285732bffba725a6d463f1efc2c70ee584c87.nq.gz
    ├── 143d7d7d90f5f0d4bf9d90c0c008751fbae26227.nq.gz
    ├── 148bd262cb035a26f0a6ff64479f9dfca87a9ecc.nq.gz
    ├── 14a9e11e29a9f82042b4cb8a02e798b64c025f27.nq.gz
    ├── 14ff7984d6f94d0a51ba5431a65f6c80ca3e86da.nq.gz
    ├── 156ba51ed19905c4ed9d0a661648c3490823b659.nq.gz
    ├── 1572428d09ba42db49cba19efbba9480a7f25e35.nq.gz
    ├── 15a8e8010260fe4b3388c840f6f854dad025f702.nq.gz
    ├── 16a23b137426dd10fdb385aa30a37de5a99aab2f.nq.gz
    ├── 17642e92e64fb12c055f31a0255b3d91b35cdc43.nq.gz
    ├── 17a5461a8bd7f9059c3390d622d529ab6ee864df.nq.gz
    ├── 18570b39766ca31e3ec701b806cea160589043ac.nq.gz
    ├── 18d0abc8be34a71d4c1388c164adbf77cb766dca.nq.gz
    ├── 191d51078a7e3fb0002b9dc5c25d76a96abdb201.nq.gz
    ├── 19f330433a54b6472378e83f82fd05cc31797187.nq.gz
    ├── 1a2f8c7d2fca20b085f9d697530e07d7cb363d5c.nq.gz
    ├── 1b40149fce65a62cd183102d4f23cd11d65e13bb.nq.gz
    ├── 1b56e72800a13c9ea04d92ee520781dfccdd8ea5.nq.gz
    ├── 1b93e3407da282b33f9f7e7367242688c7dfa093.nq.gz
    ├── 1bdc62954408b02aed8f0d3bfddc60620ba9bfd0.nq.gz
    ├── 1c1b1b350d09f6459d2bd3f2299b77ed82b75c4e.nq.gz
    ├── 1c398f0d68b4b54ae6db07d8266bfda34baab032.nq.gz
    ├── 1d297b9a671ca5c3862af551d97214f72ccb3749.nq.gz
    ├── 1d2f3de3154b752d1fec05fa76a53ab7112dee67.nq.gz
    ├── 1d3efb355b25361988915016071d0b9b3befaa1b.nq.gz
    ├── 1f0a7338eae65d17ffaa34fe32de69b381a4aa11.nq.gz
    ├── 1f1129851853aebfea252e549e01ad51e0a4635a.nq.gz
    ├── 1f8f7c6d291e1de3ab248390ec3dfa503189fd57.nq.gz
    ├── 203cf6be647342b428de03881b92d9d99a1d785d.nq.gz
    ├── 220b1b97122c8a5f3838752261ef339917faaca6.nq.gz
    ├── 22c58484c39e5901dd2b3c09c38384e3121fb267.nq.gz
    ├── 233e98118c4808c66028553d2ad8975e49337c4b.nq.gz
    ├── 2354de1ed66a1a7a848c98fdc6bebfbd6c0af5f3.nq.gz
    ├── 24034c89e88c4bf2fa139be254b27b52f0454b92.nq.gz
    ├── 245721d24f49b4b51ee68098fa81d15667d9d8e4.nq.gz
    ├── 2491881a3058f8d0d2eb6b93f4a965392e695d99.nq.gz
    ├── 2537c1776abc711f296d011af8e99bfcf1eb7be0.nq.gz
    ├── 26d2efeb182647d64983a88b800f54fec325e343.nq.gz
    ├── 26d921e2b80416a47d43342c3e382e968415721f.nq.gz
    ├── 27002271459227fe3348ebf4b0bc5c232a888a8b.nq.gz
    ├── 271ee111afb4c0a4ebc95473c8dd296090a71f31.nq.gz
    ├── 276933f6dbc93c5d116783fa7e8b978840a8c4b1.nq.gz
    ├── 28b3bb37c8157351b4dbb73197b81b69f5b6e89e.nq.gz
    ├── 28b4735436ae845b0c10519f2aa8c3a531edda7c.nq.gz
    ├── 28d82fb6b17c07d19efd6c076613159c002f93bd.nq.gz
    ├── 28f76e2022fa08fdd0c11c9fcf4d851452ebc75d.nq.gz
    ├── 292b2c182fa3589ba0bdf2f888fa5f1ad64c0269.nq.gz
    ├── 292cefbc5aa56525ac859823cee7e02eae173798.nq.gz
    ├── 29767cbf830c8cae3adfd16f6fb291589f100845.nq.gz
    ├── 298419f24cc7fe57e644639a1323a890d1eb0eeb.nq.gz
    ├── 29f3cb3f70d02f507d292c01a384d07c07c2288a.nq.gz
    ├── 2a1304f6b9cd7b48fee3e33b09aba3fa93537ae6.nq.gz
    ├── 2abc00d3199f817af32f3516f5428d2b550a706e.nq.gz
    ├── 2ba00890b264419a0ea1b5091ea991521066c74f.nq.gz
    ├── 2bae9551a6087d81b8b9186684f15ede3ca9d5a9.nq.gz
    ├── 2d34c2fedda59bc9c457d633da3ee1138299efc4.nq.gz
    ├── 2d39aec83f537c360ee9c99c84d17f6fe02a761e.nq.gz
    ├── 2dd2b35544d4155c939e2d3200d2e60c118ed4cc.nq.gz
    ├── 2f34b696090b8f552af3e35d659b686ced97e766.nq.gz
    ├── 2fb4f94855f0441bcc7d52354e167ffcbb979d6a.nq.gz
    ├── 2fc1d283b0379ca59bcee6d5b7443a944c39ef43.nq.gz
    ├── 301048ec487a168b21870856f66d422d49aaac92.nq.gz
    ├── 30e6ff0996ffcce152599020cf18efe863716c28.nq.gz
    ├── 3225d6d254278ec250db6581f484c21411a72168.nq.gz
    ├── 32f17be9a37f890a4cd0698fea61c01ec2f6957f.nq.gz
    ├── 33e22a99cb931d3387b4f85ba3b2d8bc0c66b853.nq.gz
    ├── 33eb2f789cece24fabff02d675d34784d5ed0814.nq.gz
    ├── 3439083f7d91cf20ee429e19a269c826fe07235f.nq.gz
    ├── 3475c8588817a9df18ab7160a1e0c9b3e8a386e1.nq.gz
    ├── 34c66fd792e0af641908dcf6887a5e69423660ed.nq.gz
    ├── 35eadf9d4d21577fecbac1a5db4ead6a65feb497.nq.gz
    ├── 362288f348d23d4eee6d85b6b508fa85190260cd.nq.gz
    ├── 36c44e96c2b2c5460c376c448c1a42d6ad33123b.nq.gz
    ├── 37fdd5e865a89055afd8b48ed6a0fc999650b1d1.nq.gz
    ├── 3804eacd5ac7201a7abd6143d7ccb8ac702371b6.nq.gz
    ├── 39652214d9f5a5623bb8cecbe1935742190190d1.nq.gz
    ├── 3a7ef493d822d6c20517a83b3d4d0a2e565ff5fd.nq.gz
    ├── 3abc9b0f21d21dc547d7880c385988697f9379ff.nq.gz
    ├── 3b247f0102c041abf143db6418e9671d29dc5074.nq.gz
    ├── 3b3f84024c701435cb4c237826f9af10126f9714.nq.gz
    ├── 3b43a559f4e36ac7e43f528502df9ceaf191ffc5.nq.gz
    ├── 3b94e226f1edef72f5dff57266f1bd414059afdd.nq.gz
    ├── 3c378a328bbea9e4110aca9faf9cb69371514d4c.nq.gz
    ├── 3c440fb75cb23b11d3b0d0e03b42cc81b0b2754c.nq.gz
    ├── 3c6effd80eb4bbef15d9afe2d60c1b06fa003985.nq.gz
    ├── 3cc0e6d21489b474cd8774f2f9c5d12a1e6d4aeb.nq.gz
    ├── 3cefbc6e2b11e568b953a7b4542e7cce56f2a72b.nq.gz
    ├── 3cfafac26e116486e768f46a2fc105a3fd6df68b.nq.gz
    ├── 3d0ab9f2e23b2bf3558e4cfb73e1d7c360294e94.nq.gz
    ├── 3df20337db53856162f461671d21361dffa10b06.nq.gz
    ├── 3f2cc48f0740c0a386c1b84461ef03501990082d.nq.gz
    ├── 3f69bc17f8c059a973a422d9c904bad218aa18d7.nq.gz
    ├── 3f790e1fde5b4200a9275d640b44b80f846e5595.nq.gz
    ├── 40acb5eaae7e5d4e9f78483125738ca06811a1de.nq.gz
    ├── 40dbbbd6e3e921848c44955199033709cbbd83bc.nq.gz
    ├── 40f34979797efdd6f31896c5808b2182e234743a.nq.gz
    ├── 4145313c2a05cb64873ae5d346a72b60ae38fef2.nq.gz
    ├── 41bdf7e4f86c97df4648a262bf0c38f6aa74ac08.nq.gz
    ├── 41f670f0c085a35ce4f8bcc99fa58434d32980e0.nq.gz
    ├── 4249107e894dad872787e9b7748f36d9a332d6b6.nq.gz
    ├── 42bab0b4f3b3cc9127ba51eeadb80ae7069ea378.nq.gz
    ├── 43a3773f26f9ce5d43e955f24e052f003c5e9405.nq.gz
    ├── 43e0e049be2a3fff888c7920bb8652ad51dfd59d.nq.gz
    ├── 43f66a855b58fc44e1dc728f4329c954bf6d03ec.nq.gz
    ├── 441f1cdf10f8e0715c19a70098e12315ed4a52db.nq.gz
    ├── 458d881f94bed7f16e51e7bf6f7d56da3264c46c.nq.gz
    ├── 45aa89030bc111b72100db2f42db9aebb23fb675.nq.gz
    ├── 45f407c7fbbc1cdbf7ddc18ae66ce4604cc10f79.nq.gz
    ├── 46d4b20790e36be4276b932a161673deeddfe3fc.nq.gz
    ├── 4733dec4cf96adf1418da60276a8c522f814f982.nq.gz
    ├── 4794f95a4acdae2d1a21696f04b58c158041ec9a.nq.gz
    ├── 47a696d83f1a2965b0340deafc54b9189e29de0d.nq.gz
    ├── 47e2da100b13d7bc25bf6280f07749eb72b9e3e8.nq.gz
    ├── 48019cfc982bfd73a89bc76ce832fb5e69a96b0b.nq.gz
    ├── 48e9ad21d01999fbbe9fbf47e070b582a3697efb.nq.gz
    ├── 4a375947e4206bcfb5a5214b0883c59cdf6ceada.nq.gz
    ├── 4b2ea045690036203468f923f592d10237464f41.nq.gz
    ├── 4b3ea62c58958557c1543de734d7602615c86fff.nq.gz
    ├── 4b7f55d092c1a7fc8b08137f46407ec984ad54bd.nq.gz
    ├── 4b8d7453da3bad2b3ae1def74009d6f23cd522ac.nq.gz
    ├── 4bbc0df1032d8c7d9595753557286004606f720a.nq.gz
    ├── 4bcf9de254b4553bdfbd15c64eb90d935c5f7f91.nq.gz
    ├── 4c0462bc0c532b79a6bbefbf48085f17f2dcd56f.nq.gz
    ├── 4cfcae525ec97c19b78dbd5b29e892940207f02b.nq.gz
    ├── 4d242cdfe8d9725ea5cd5d06f3391f3a29bf336c.nq.gz
    ├── 4d2f406a9aeeefc7afbf3052967e2bd5cfd62020.nq.gz
    ├── 4e0d8fcc6c9f784cd99e99b58a4715c14d06dda9.nq.gz
    ├── 4e45b00ba30cee34314be0fa6ccb4da21fd4e88e.nq.gz
    ├── 4e9346d96253491d3761a6f3e701d93a26246736.nq.gz
    ├── 4f23aac6a66cb646b5d54b9d43f8241ac2e0d55a.nq.gz
    ├── 4f4b43099091e502fe3273fc73b1c568b36a0ec3.nq.gz
    ├── 4f6efe68c3ef8955ab9ba1c62d1bd26e3735f0e5.nq.gz
    ├── 4f6fc2e0751c5b528e4db98fcc1367fc4258da91.nq.gz
    ├── 4f75a90e64a4577688a866e6ca0075db0d0d960f.nq.gz
    ├── 4fcbee2bb303c210d023933363da92fa6eec043c.nq.gz
    ├── 4fd34d93946fec77c8a09f8112172a2453b25cb8.nq.gz
    ├── 50f54bb8cfcbb197c3e20e42b6068679a1876e15.nq.gz
    ├── 514866ecda53756a8b8e20ad3b5bb309a7867267.nq.gz
    ├── 518a2f32bc1e42209eb3f85306b42e965e82f298.nq.gz
    ├── 52055ad5884856e495522c6cc3fa6473156e3dc5.nq.gz
    ├── 5207095dc35351b308f82074854f6e748ec74334.nq.gz
    ├── 526958f995a95856d1fda58e08dbc1b08e0b6dcd.nq.gz
    ├── 527e535985ee28e52158c039b74142ab4a51afd0.nq.gz
    ├── 53c89810606c5f65a8ef6c5fc75107c102ba565d.nq.gz
    ├── 5471475f6d59466273219a881de5cbf2a3273bfc.nq.gz
    ├── 551e0009624d9a2e73b54f5a8c35c74a9bff7080.nq.gz
    ├── 558f70660ea23ad5a7f3df1ccbeef4c5e3dace84.nq.gz
    ├── 55973f94ec23d7a939f5561bfb5659652ea18482.nq.gz
    ├── 55c7a214e2e394d8ee9be135b0352aa49db89213.nq.gz
    ├── 5618c34f5920c82d176fbd3f435090b8351fa4cf.nq.gz
    ├── 564fb708adba71b5dbbbf449949204db507787c7.nq.gz
    ├── 56687c370e6c9e815bd7cbd5135eb6d0486c4561.nq.gz
    ├── 56893d1d1020702d07d98257c5a3a1edf00f0be8.nq.gz
    ├── 56a89601e140c50c32a74f590375e155477ef3a5.nq.gz
    ├── 5714d3d23c4e534291e74d8195939f96e6a25906.nq.gz
    ├── 5784a25001f142204d6d497b309672d5d8583b34.nq.gz
    ├── 578d714c6a5f4c837e8ece1e0bb22f9779e43087.nq.gz
    ├── 57b0fe2e05dbc51f6db5b7da1d47c8a8aa5fe5d9.nq.gz
    ├── 58d4a78596bb4ba51a31e72dbe4d59a298f7e510.nq.gz
    ├── 59853e27b81398c66fbd70f07624ad68bdfaea85.nq.gz
    ├── 59a5ebbdf54c326861345f369e19cc24257a039d.nq.gz
    ├── 5ab1f4843bd9183c0887062e3a570f2cbfc1692e.nq.gz
    ├── 5af042ed68f1768566a18809728bc61662759373.nq.gz
    ├── 5b066c78db7a1e6eb989cd668f5c6e8262b329e4.nq.gz
    ├── 5b08e3a966ce61b9152c4f837aba8729ee4de6f7.nq.gz
    ├── 5b5dc91e11f1f82f3da39e61c23c733cc0d4445c.nq.gz
    ├── 5c178e2185d1346eb6677b3c863be58d016e1b26.nq.gz
    └── 5c62e00927f5f9427d6a869e249a318f601a2eb0.nq.gz

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

[temporalio/sdk-python](https://github.com/temporalio/sdk-python)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
