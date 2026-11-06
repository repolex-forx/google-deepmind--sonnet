# Repolex Knowledge Graph of google-deepmind/sonnet

RDF knowledge graph data for [google-deepmind/sonnet](https://github.com/google-deepmind/sonnet), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/sonnet
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1c3b3e4dad22de663e992107531d2966fd7904aa
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1c3b3e4dad22de663e992107531d2966fd7904aa
│           └── chunk-001.nq.gz
└── blob
    ├── 005fc1b1bb916116d00ee25058f6da5edae0b96a.nq.gz
    ├── 01930d81f50081e0c9f66dd55e100c51700715d3.nq.gz
    ├── 01fab6c4d121ba91facc6a93087a7944dd095282.nq.gz
    ├── 034ad7bab8ce0d0a6d94cd4151a6e15098598d77.nq.gz
    ├── 042551852483c9970daca28692132aa4bccc3b94.nq.gz
    ├── 04f196ac782bad0d3f50899e002cf4adb14aa3e3.nq.gz
    ├── 05a986e390119ed2c08876f8fb4e145c569629ea.nq.gz
    ├── 0717f9cc573f490a30b2eb364d78592e1ec7daab.nq.gz
    ├── 077095c547b884a222278093dfab78cec8fd69fa.nq.gz
    ├── 087600685a33d3070aa29ae2abc55dd95d751729.nq.gz
    ├── 08d0584983ac7a7bc47a4bf3d499ea1966a7ddab.nq.gz
    ├── 0a63446af31e9ad028520515537c253b486f3af1.nq.gz
    ├── 0a6d2df11553ea4186e59672f6248c503dbd8700.nq.gz
    ├── 0ac57020b2d2e0bf8b6e66d222cc1e5f666fad9c.nq.gz
    ├── 0add1f5147b08136c2b6ca1d42f3c2c1f574fdd0.nq.gz
    ├── 0af940753b1ade5f8168f2cded899ccdd9f47dd5.nq.gz
    ├── 0c0fe4a6f3ea91fe5184811924e5a9d7642c0b7f.nq.gz
    ├── 0cbf905858f3bd7eea262b501ecd2c5e0a83a264.nq.gz
    ├── 0d6be358b90381d269ed6a674b58968f73fead09.nq.gz
    ├── 0ea97673f7d7a8728769093182a41ab13e2a68a0.nq.gz
    ├── 158df9688eaa3966974deeb129eaf13e9db834e6.nq.gz
    ├── 15df5ef625e8e86f263e83e1c0f4fd856f65bf01.nq.gz
    ├── 16c688d98580917bb0ff03059ef951ceab341f57.nq.gz
    ├── 1883b21562ad4e7f2720b9ea84b58866efa2d7d6.nq.gz
    ├── 1a9508e25b8d646b2b5b5fbe526fd6b14ad1ccdd.nq.gz
    ├── 1b05c36c83863fb01ec4b5257a7749257ed3b0da.nq.gz
    ├── 1c58142673fa9d8671c03525a6bf5c2a9e940083.nq.gz
    ├── 1d287b629a2d437da3a294125d75b9de41199384.nq.gz
    ├── 1dbf9e966879fd3b1ad4224e1e1cba8f9e28bf56.nq.gz
    ├── 1eed01ffc79c9a24282cde8e417857cd67089553.nq.gz
    ├── 1fc78af06c9de01afc934e68be1a617441926d7a.nq.gz
    ├── 20a54b3286efdec9e42c6a713abd1aff366f145c.nq.gz
    ├── 20e2e09b0ae52e3f02877049092d861b3f88f4e4.nq.gz
    ├── 21cd7eba78689ce3e77ed6dc67796c228e3009c1.nq.gz
    ├── 221298f40895e7bbeb130b4574a3419c1ffce25a.nq.gz
    ├── 229621a354d73802310251d98d948f3fb12a3c24.nq.gz
    ├── 267e461c4cb5199f33bb654eee531796e79b0834.nq.gz
    ├── 29e3e2e7247a7ece82c2ceeaafa98c090c27354b.nq.gz
    ├── 2ad678fb258c5c11b655105b9f5d6491656654fb.nq.gz
    ├── 2c29871762ca3ca9e84638fd31857d937684830f.nq.gz
    ├── 2e8f0c2559726a9576d5b187a6b32ba5c8cb3a74.nq.gz
    ├── 2f57d72210bab5c8e58b4aaa382e42fa2f76c0e5.nq.gz
    ├── 327dc43c51d64ec17871a4d65551ee91ff55586d.nq.gz
    ├── 3367b356568799494e66b8b602487c68042d8d35.nq.gz
    ├── 339bdbf7e4c2c4461e46818043a7c156bca61c6d.nq.gz
    ├── 33ef1aeadff248f2359a8324829f283ac603ad3a.nq.gz
    ├── 343c1d8952d3544941708f85b4675e4dbdea47a0.nq.gz
    ├── 346707c6e13cbc3abbcd29f426327d19e0cfc0ca.nq.gz
    ├── 3495b6b1014f92755a8a110092ec155faae7c479.nq.gz
    ├── 35e2dea78a5a869cf7f4d4774f30de00913c0588.nq.gz
    ├── 38a89255e3d014295ec9e6587327e79632dbb24b.nq.gz
    ├── 3b1404d3f68ed3efe9b5eb3c935e055645ce3edf.nq.gz
    ├── 3eb7b4540b4c760fb6d23f0edc67b05dd624135f.nq.gz
    ├── 401f7b830f4a3ce60e128456a67e8fd3700228dd.nq.gz
    ├── 40d72079fbdd61d97a40ee19f3025c8d14db40de.nq.gz
    ├── 415be39aca0928599f9ba299c07d2bc40129e357.nq.gz
    ├── 4251a5dfdf068c09da4b706cfa640380b99f8d70.nq.gz
    ├── 427ad6df69cfb69f089f4811f4e5bee74450d517.nq.gz
    ├── 43313a56fda63a9f24f1ced1ea9467b515996701.nq.gz
    ├── 448370c62afe25266cae306945baf1b417c96f28.nq.gz
    ├── 44ef5373065c6d92e6d10ba1258c4f0d30830373.nq.gz
    ├── 45bd7b2e15185c012335bda5cec18dad006f2cd3.nq.gz
    ├── 45c886c973613845388b7760750e5cef039140a9.nq.gz
    ├── 463af8e1233ed651f83109b24575f39421fb9db4.nq.gz
    ├── 46563c5cb44415481348d81fe417d4518b2f07a0.nq.gz
    ├── 469b7a8770e45ccc02ae804c3805a3fc8c4be9da.nq.gz
    ├── 48aaa77fe4378eea04da061a398a3dded44d38c5.nq.gz
    ├── 48c0d7a3e8deaaf8f3a7365602b54472d1d34f85.nq.gz
    ├── 491ce71db37385772e5ff2a2dc51b98d14779c08.nq.gz
    ├── 49ca31f87027784cce96d058312c2cd66afaaf84.nq.gz
    ├── 4ba18921e7fbaf17b34b33040c002f84509087df.nq.gz
    ├── 4c79849f2367b9c7a6944cb81aebad892b4a5fcf.nq.gz
    ├── 4d65b4cfb2e7af2057d80a9b0672f3c81f4d8e1d.nq.gz
    ├── 4d8004c13528bdb0a2fe47edd76fe9b02e11f52c.nq.gz
    ├── 4da585d7ea7c0fc9f1650bee060b22fa54261ea1.nq.gz
    ├── 4dc34b5d4fd74cae125b0ca4249fd67531a6d4bd.nq.gz
    ├── 51285967a7d9722c5bdee4f6a81c154a56aa0846.nq.gz
    ├── 51ac4eb56f5db5644a5cfa01c5353f6440d7bd20.nq.gz
    ├── 52c1cfc8a9bc001c4e50dbb333e8d74a4af33070.nq.gz
    ├── 531fe60ef021dab7d63a6e11a4b688b8cca947e1.nq.gz
    ├── 532d68fa5dd9c5a3c9932b0076b87ec27c416df4.nq.gz
    ├── 56b3178fd99f6daef0be724997699bd782b33e7e.nq.gz
    ├── 56eec8ec58e1a6754e75f50f7af99742e072ac11.nq.gz
    ├── 5b136a93c7594fa3712b239fc9f6d8bbd35a4775.nq.gz
    ├── 5ca90d4519209f84912e0b9762cc0d345a1d6dd5.nq.gz
    ├── 5cfd2bde20593a8263a8ac54af13e3a88eb04636.nq.gz
    ├── 5d7e286fce65b02bbb505a551034d0638886042d.nq.gz
    ├── 5e68cdd9d93147b8bd7d0daa1d7745da3fdbd534.nq.gz
    ├── 5ffef45f662700bbd349fe2cf782ad8c883fe850.nq.gz
    ├── 62a4d5f228f6585b398de63489b72a30aad9b014.nq.gz
    ├── 630e704b83216349f8e670541ea0293edbef100a.nq.gz
    ├── 6322fbca778bc83b9318f1548ae2d5e6b8ba0c52.nq.gz
    ├── 639a802630667be0fc08c82b3d9b492ab312d3e7.nq.gz
    ├── 63bfac30bf53e0af0bdcb9af65507dc2d15b6c1f.nq.gz
    ├── 684a7be88dc1349bb0fc3c2267c1278327b5f4a7.nq.gz
    ├── 68e95baa7185515b86a4e10fb31b696d2db55977.nq.gz
    ├── 6a039156fb5828b1668de55f61ae416ec8ed4c46.nq.gz
    ├── 6a99ca3593e9327a00d55387a0b78f83e8dfa265.nq.gz
    ├── 6bd9848f3df175159a2c65a2b0ecb4e5efe09497.nq.gz
    ├── 6c3ae24280ab097f7a754b3d87b02ca988212650.nq.gz
    ├── 6d7fcb181e1121b5f7aaf818e2d0d9226ea26abe.nq.gz
    ├── 6f816ee6af48864ffcd813c76c1a2f673500477b.nq.gz
    ├── 6f89bcd50b89cff6bad0fd8424ab38e736f3d338.nq.gz
    ├── 6ffb87fddb3b33305b2ec662be4501031fe7838d.nq.gz
    ├── 701bc0059a5cbdf46b5eb4ebc3ae9a4f1675be7a.nq.gz
    ├── 702e44a44846bddab286c13d72d9bd13cc7b2c5a.nq.gz
    ├── 717294c151a5ad32289ab27ef8e1486705f78056.nq.gz
    ├── 737cd517383ff12bbae128477c8119bb5902f660.nq.gz
    ├── 75b37b5e063ef9bfae3525fc65d858188b4d0920.nq.gz
    ├── 75e8b7958e658d41aa5f6e2a06ef40ecb2147e59.nq.gz
    ├── 78d6a24dfee903388490038643e3940eac29012c.nq.gz
    ├── 7b4a42526768dfa590193628c6c37e4b9a71b3b4.nq.gz
    ├── 7b721beeff90ba0a95bfd8b1c6c74a11382ccccc.nq.gz
    ├── 7c1bde61e14896383bdc3706e47c986cc1016a20.nq.gz
    ├── 7c589edaa7eaebd7ed1b15876c7ffaab1bb12981.nq.gz
    ├── 7cdacf0839ede38919c5a64c0ab8a7f726b4432c.nq.gz
    ├── 7f2e2a480a7667ed3b2d86182ef5a215b928c5bc.nq.gz
    ├── 7fc1a16e3881d8c00217e470c753d2f22d03f0c8.nq.gz
    ├── 8148459362a0e11143f3016462d7a28d82ab69ff.nq.gz
    ├── 88d7b5224ad0e9942d465d75d97a8b169d31cc90.nq.gz
    ├── 8925cd2cd4799bac5d9a4318b2c01fddfad4b802.nq.gz
    ├── 8a628e9d1488b184a1860116a1ef76a374a56c80.nq.gz
    ├── 8a9c3ae4c126b8e5a2ce1b81fa3c7e6e5f09b28c.nq.gz
    ├── 8aa79ad4dee83f0c88cb219cc04394b5b109f991.nq.gz
    ├── 8c52e5c23aaa811d4fb724283c945169a5350697.nq.gz
    ├── 8cf284ba7ced2771b40f10bc732935a348b11550.nq.gz
    ├── 8ded0a87caf349f78f16d5a5ec2442744437f1aa.nq.gz
    ├── 8e0921004d63156977a3030099a4d5a9c9d11823.nq.gz
    ├── 90bda45a17bb840084e878d53298f7f29a03bc07.nq.gz
    ├── 92ffb444495d19f8e78ff535044b9d32f049138d.nq.gz
    ├── 93640b6a574fae1f4cf9ccae7dc4f1447aa3e14b.nq.gz
    ├── 93705178227550765427cbc98b4776bc3a024b14.nq.gz
    ├── 95879f3808c3ac43c4bf928bb75ceb047b34d387.nq.gz
    ├── 96460d3481773a03f308e1fb8ab6ddfa8b9ff8c0.nq.gz
    ├── 96beb521e36650f7a6cd0114b50ab6657c414f46.nq.gz
    ├── 98e7024f6e6d4f2f30605663699375a30b0e50b8.nq.gz
    ├── 98e9dbbdbdc1e7accce3ec59f64b5da7e36e1497.nq.gz
    ├── 99ea6b7507de5438bc44cc98e173589b66736474.nq.gz
    ├── 9aa91bc2dc525999e69ef54d705805b1ae355f2c.nq.gz
    ├── 9b81d7db29684ae1542892106349035c776d24e9.nq.gz
    ├── 9d581605f7ea344bc0f171210329ae648e24ada5.nq.gz
    ├── 9d58e769a18e518f8c68f5656ffce86cf19d2319.nq.gz
    ├── 9ffd85146f0fd5afea33259ff60faeaa0a77b8eb.nq.gz
    ├── a25e7db9ba50a6ed0acce1bf3e40117e0f53da66.nq.gz
    ├── a2f61a7e4619909e8264a77ee0b372fa090af795.nq.gz
    ├── a36a3e3b551eb282bb9842ba2b390059265eb4a7.nq.gz
    ├── a4b56193a6cb5a99b434e361452a279068cbdadf.nq.gz
    ├── a6113c9bb75d1cc2524cc0d60300be2f8eebec3c.nq.gz
    ├── a6aa27113b16d4c56f6ea31e6a36b753ec79c8f4.nq.gz
    ├── a8610eab7217604213dd682559e6415b4fa76e51.nq.gz
    ├── a8b6c27796729da799f307a1c95b5a9a4d625086.nq.gz
    ├── ac77f10feccb5090dc5846b2d662e95361fc5d88.nq.gz
    ├── ac894ceca9609adca7a7154e9487841253f726b4.nq.gz
    ├── aca3be9a50f110047f38225439bbf98cca139beb.nq.gz
    ├── ad463fdbdd76a91223a100ebfac6a37722808015.nq.gz
    ├── adfce5aad5e13c937ff3aa087cde5bfed92368cd.nq.gz
    ├── ae6bb1d6c4fb1127211b10f131dfae5d1b4ea4a9.nq.gz
    ├── aea930e98770e9968d056d278b05ad320cfbfc97.nq.gz
    ├── af329bd907e89d1347afc8e6896f186a5c097202.nq.gz
    ├── afd73fd1bf103cb49473831debb3d711c3187533.nq.gz
    ├── b1de25aa3719fda125536e97ec7f816bbd6715d1.nq.gz
    ├── b2e3f5ed62f78895cd38a8fba5b19254cd140bb9.nq.gz
    ├── b4ad3fe7c5e752505dc7f5ef5f35034347fc5472.nq.gz
    ├── b5697b94aba3725e41df3c93416cb40e4c7f9a21.nq.gz
    ├── b5f652ba1ae55f6a6f81ffb8a0687ddc8c94314c.nq.gz
    ├── b829fab85aa815b5922a12e308e5b95f2432c4d8.nq.gz
    ├── b88f0ffa8ce6ce81ef05fa0350e6b33419aa2ea8.nq.gz
    ├── b896c5564cc8a456e121c960e43648abb3f47d74.nq.gz
    ├── b8fb9c9666ac524cb8e153e77b476a0f1aa937e4.nq.gz
    ├── b9cb1e17b64c4ad1058170548bccca04da4c1f98.nq.gz
    ├── ba90fd20d2cda40be188c9717d5daf310c68d1aa.nq.gz
    ├── bb0f2d4569aa3dd228c011832abf35faf616e3c8.nq.gz
    ├── bbb1d393ececfcb8723d287e9b36fc1c1929ecfc.nq.gz
    ├── bdef0c9c5ba888a6f0c89575728ee3dadf349f6d.nq.gz
    ├── be0741c7a146baf85217de4773eb6720a8ab2d6a.nq.gz
    ├── be42e5853680434331bb1df68f6df32ed9572488.nq.gz
    ├── be9a3164ec0febfc3a9a5129388db46526db7432.nq.gz
    ├── bef9d8e6f222944234a970dfa9710be23ac80583.nq.gz
    ├── c0744b96269dcd1a7ab577f1ead06552ef397e1c.nq.gz
    ├── c0b715840a8b29c5fe353ac3b97af0704c8657a1.nq.gz
    ├── c2f3e1b61b025f12317c8bb80a112107d53ac936.nq.gz
    ├── c40dee3501c143e8773cfc4491dc831b3d613725.nq.gz
    ├── c5a503ab2d8afe7e706de5a6e2f15ad428552907.nq.gz
    ├── c5ae7277b8aeefe6a0dfcb4cd82c2ae65d426924.nq.gz
    ├── c82f2dbe1e9f16f776e461f45960f8c5f3814b52.nq.gz
    ├── c9c0343111ba5e8971aefe5f1af4d3f1f7e24936.nq.gz
    ├── c9c7a7bb4294cf9c84c88ff9d093567dc561f118.nq.gz
    ├── c9fb9dff7d7bcdb67891218f33bd9c93c74714e9.nq.gz
    ├── cc0c62629897e3fb8b5b25c30847a93e93ece1cd.nq.gz
    ├── cc38750a44c17ae53310202300f9e03122ebe79e.nq.gz
    ├── cc6aa42096c8a3929cd0e3e35fa6507bd5c4c597.nq.gz
    ├── cd318e1119061c94e684f37be930082acd9db4bf.nq.gz
    ├── cd3f32da85426cca36c61d2eded576437aee3bd8.nq.gz
    ├── ce7db246a61baf12ce0d28a213cfe36e28d87229.nq.gz
    ├── cf2590a5f406400a3c580055fd61bdca475ce553.nq.gz
    ├── d04ddb5a1e402291a60108b5b179f2e546950f23.nq.gz
    ├── d1fdcdfc265e65f033d6c37d867a194aa52057e4.nq.gz
    └── d2908cab8906614641e35994a211327cf3d6bae5.nq.gz

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

[google-deepmind/sonnet](https://github.com/google-deepmind/sonnet)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
