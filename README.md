# Repolex Knowledge Graph of qdrant/qdrant-client

RDF knowledge graph data for [qdrant/qdrant-client](https://github.com/qdrant/qdrant-client), parsed by [repolex](https://repolex.ai).

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
rlex download qdrant/qdrant-client
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1b5bb8589e5a8c124bcf80164736c7c92370c871
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1b5bb8589e5a8c124bcf80164736c7c92370c871
│           └── chunk-001.nq.gz
└── blob
    ├── 0395b92386e9b52db58e2b3bb6a48b0992acce4a.nq.gz
    ├── 04a518ccb5018e4e7ba3a5df9de610aedda0b270.nq.gz
    ├── 04d7edcf7368e3230d65a617e42093b20ad9f4b2.nq.gz
    ├── 058c73c279c324c3ff96aba20c40a7440664a8b0.nq.gz
    ├── 065c7c59824c4836fc91dc511326e4968bafcf4b.nq.gz
    ├── 0721f4abec7aa177344d889bf9adca2739e8f5ab.nq.gz
    ├── 0a0d8e1bd4e009ab6f1acbbfd098025d4d48dab6.nq.gz
    ├── 0aa9548c3032a7c8be51ba587f3343af8b6a7102.nq.gz
    ├── 0b4713bc5b1ddc7099eb16871b15c67bd01209d1.nq.gz
    ├── 0d2e21fb3a9934aef93ef3ee7975335e0666fb23.nq.gz
    ├── 0d70db1a91493152418f07a8ba6212863db5dc4c.nq.gz
    ├── 0e356d5af7e1b53dde9a80461e1e4207835bd858.nq.gz
    ├── 0ef289f5cea6ac568da4cd6321d1b5d799fccccd.nq.gz
    ├── 1053054fc8fd0769cde9b088e31c2b1c70534aca.nq.gz
    ├── 10f08712d35bb32655aef8011cdfa55bc29fae06.nq.gz
    ├── 110347c6fd097edc418888c4e84c37f3d4e22780.nq.gz
    ├── 117e4555e4797376fa5586e453e5d3e5b1b3dc90.nq.gz
    ├── 11d1182f3e715de4f33e50b6521e7b8020b7daed.nq.gz
    ├── 11ec3407124ea22af42395637e945fe869faae89.nq.gz
    ├── 12a035ce9f85d3c718549f812c837a3a92398ef2.nq.gz
    ├── 12e0e404d48d5648083be3cb6b5161c9951db157.nq.gz
    ├── 137a36d13aa1ab36297527334dfe133dba5512d5.nq.gz
    ├── 15426987dfd1f91691d403e0a7798b8a2f1dddb5.nq.gz
    ├── 174b71a1621b4d08baaee66325be7abf580df0d5.nq.gz
    ├── 17ef384a1dd8581425bcd6767777201a2676aa66.nq.gz
    ├── 18d4f2afc8f0813fccb0870cf9109120fed2e48e.nq.gz
    ├── 1a3d493d38f01a41f7bd1045e88533968eb528f6.nq.gz
    ├── 1c629e2686df6591cddac891ce0cf9f94ccf62f7.nq.gz
    ├── 1dc3da8169c4df35027eea70a26c80fd3664fc0e.nq.gz
    ├── 1e1d85f6f89b37bcf0935e799dd413fa99b7b019.nq.gz
    ├── 1fe2740cd1a4be92b2b63b433bbce728c915fd6b.nq.gz
    ├── 1feb115cf330a068e4690acdd6513df7670a956e.nq.gz
    ├── 21f2462fbc7d9dc03686ac4cf41bb6cef90704f3.nq.gz
    ├── 22a8b570b759aaad9f732fec20b44b8bac929e1c.nq.gz
    ├── 22b63c800499ad4612dcfa8edfdfe873387ace83.nq.gz
    ├── 234b8470949efd4dff993946883eb5fd9856581d.nq.gz
    ├── 236a3c0bff6e342156ba411986de946f79d59282.nq.gz
    ├── 24613e3e7d701d359957ed5283af617aefc81579.nq.gz
    ├── 24e98214f06f0f5de19c7c45d2ffb6a50350814a.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 283fdc3b0d5d4748ce05608414de9939e49e2342.nq.gz
    ├── 2d16d6fe611573b62a6e2f367510c334a526bb51.nq.gz
    ├── 2daafffebfc817aefe8fcb96eaec25e65b3903e8.nq.gz
    ├── 2e841d8d55ff1352ddeed3b5d8fdaa5b6d1c05e2.nq.gz
    ├── 2e8b104be16ae6627611a90b32d80909d2f4c761.nq.gz
    ├── 2f8376a73c7770b682fc161b2561463f52694c17.nq.gz
    ├── 2fa244d0b5761e4b2642822bc815b78c016a994e.nq.gz
    ├── 2ff9b9e838bbbb2c4010aff931ccdb0a118baa57.nq.gz
    ├── 30d6ef8d719d102671da5af257bb1b5a85239f83.nq.gz
    ├── 3119c742ab7703dc501e69be5f073a18ef223ff0.nq.gz
    ├── 32777c5899c833572ecb485715153ee92cc10006.nq.gz
    ├── 3386d1a60c0b31b17dc66b5a5cef2528d3a2f7de.nq.gz
    ├── 34e158d7a714d2c3ba81910ad7958cca1c713000.nq.gz
    ├── 3614a6d6229119f8a392a7f45f75f877ec954c79.nq.gz
    ├── 389f1aa46cb46b9824558357eef3ffd9050be255.nq.gz
    ├── 39e8e0af4be73640aa89e9911fe15c9e79a6b66d.nq.gz
    ├── 39e92d5255556771b1e1c80ed343b6f326bf60ac.nq.gz
    ├── 3aa770db0d65d536f0d82ab8bd19ac7ecf5b9628.nq.gz
    ├── 3b7ccb8aac469024a85d378ffed000d781bd0164.nq.gz
    ├── 3c61fc08dc96bd50e5562869aca364a0db4e0f8d.nq.gz
    ├── 3ccf1f81cae7115dba2d10d7933b735ab0934e77.nq.gz
    ├── 3d558bf9105fabc866a876897454bc7ba4f50ed9.nq.gz
    ├── 3e0340dada2f4ec16254f142a45cea468ff4d6f4.nq.gz
    ├── 3e2122afde7fd5a4abdb5fdee8cefdf8ce0ccfdb.nq.gz
    ├── 3ec29974266385585c511d79fc0576531e184a83.nq.gz
    ├── 40b2fae15add6475a031244f93ee81814736370c.nq.gz
    ├── 40c7a88626984ef82b37f760e36049be01148cfa.nq.gz
    ├── 4247f74c27201986ee24c78c73d8cce49d609ef1.nq.gz
    ├── 42545ffb6439211322257e8114ae83f5ab0e682c.nq.gz
    ├── 445625f818fb7791e749c1e1d7229244abf83eb9.nq.gz
    ├── 45437e1c0f7a395c2d80eb713b2c5453b41baac5.nq.gz
    ├── 45f9097a60c755e04e83d36fa4e3ac7bd2efa1fd.nq.gz
    ├── 4729da10934e1cc6834b1a3db82c5d20525f1fca.nq.gz
    ├── 47f284d1a74609b0074d1e64d6f3ebc098e61b3c.nq.gz
    ├── 4833a796205d6aa7eef23ef462749baba02b5cc7.nq.gz
    ├── 48e87a27a3b7f45a6d0be22c48e72de475896c05.nq.gz
    ├── 4915278511900e45df156bd1b78dce5888a13bc2.nq.gz
    ├── 4937b42eba2bb2e9c8335a6c6e7464826fdc9fdf.nq.gz
    ├── 4b23c246e7000005f56fb90b95443aaceb0d5e89.nq.gz
    ├── 4ba5d9da65e9cbc31c3fb55f5afe3a86ea5e7441.nq.gz
    ├── 4bdedb0df889b4c217f6c4eca915484302d7c1e6.nq.gz
    ├── 4c29f450930143f4cd00e34f272fc18db94e725a.nq.gz
    ├── 5058aff88bd685e95c51e960f36a3d712b9aa9ea.nq.gz
    ├── 523e7bc2bf6739879cb40df37596b30afc0faec6.nq.gz
    ├── 538717508985c016c1e85a2b6f6cc2eccc0ac65f.nq.gz
    ├── 557c54d91424a5d3d4fe0f8ede14a7b114fef69b.nq.gz
    ├── 55c88ba3cbd468fdfe922dd8177e612c26922327.nq.gz
    ├── 5656d7fed9d7abacd9e91008e19eb5fa683e43aa.nq.gz
    ├── 5690d00f191957cc182eb40b8d04f3a5dceb1fe5.nq.gz
    ├── 570fb1b43ad5c2223644586b9c564818145b813d.nq.gz
    ├── 5719963878de52d8fe5b431e67d0d9f0d14026a6.nq.gz
    ├── 57eaeb5fd168978753db9e27b3a787b69038ff5b.nq.gz
    ├── 585ca46ed7ab0af82b2fb3d8117d2ab0b81d6723.nq.gz
    ├── 58bbc2ef0b6aa27284a040dc8a1c83ca28714fef.nq.gz
    ├── 5961b29d607c3107b1038ae8184e66db127b4ace.nq.gz
    ├── 59fa02d201ec3aebd4f768037419babe265cf8a6.nq.gz
    ├── 5aaa4c3d8384aca4a65d56bf11338728ad9d53f1.nq.gz
    ├── 5d4856fcca764031a4be00d64f29110934f82aee.nq.gz
    ├── 5d7c0a9f9c2bae8b30cb5ca8fd07998e614ecfa6.nq.gz
    ├── 5d9459be49eb17f9bb301f47dbe05f78ac3fb856.nq.gz
    ├── 5db1cd92cc6bf1d887943708cb275847043bd39c.nq.gz
    ├── 5f4fbb9ab959fbf818cbf3c3ddce30b5a7e68790.nq.gz
    ├── 5fa5c692bd33ceeed6127bb901a0cffb02994de7.nq.gz
    ├── 63dc49126a0f7bb6ca9ef152a053e50cae1ce8d3.nq.gz
    ├── 65dbf07d5d73b9eda2ab4c1cb9d23143918dbfba.nq.gz
    ├── 65ede0e4d99c170fbd1eaab0f3776a6849b59ff7.nq.gz
    ├── 67562996ac1f444844ccab14cb3120b58313601a.nq.gz
    ├── 67c532c1fb74e885017cba8d7e9c6d2c61a1dace.nq.gz
    ├── 689b821325749ca95d116c3cf6aeb08b68a9d4c7.nq.gz
    ├── 690aa2eefa2b9025548e77d006f30b1465cf9724.nq.gz
    ├── 6a20624d4fc3956ba6d0e67234619f4bc5b2e2d4.nq.gz
    ├── 6a36a3cfcf72c174f8a3af9c92ffd477a54533ad.nq.gz
    ├── 6a3ea5bedadbbe94fa39a3931f57f338da01536b.nq.gz
    ├── 6a7834ef3392f388cdc0eeebb1cb493ec9c88a0e.nq.gz
    ├── 6cfdbddf92708969f84b6b00df6587389b7f60d1.nq.gz
    ├── 709cfde78c619893f693cbed73bc9ba9d91b552c.nq.gz
    ├── 723c5a7251aecc71ba7f6eab71078f979eb5c0d6.nq.gz
    ├── 741899c17b5cc10aed33c91d990b30035f883f15.nq.gz
    ├── 7430375895cb97d9379e76d73224b8263014a18d.nq.gz
    ├── 74b6c0286ac7840a0005446593a0cc4aff9388d9.nq.gz
    ├── 752d254075c7e19adbea9f29b9490e3e275e35e2.nq.gz
    ├── 761fc066273d92c3e0aff30b7148993e2cc02183.nq.gz
    ├── 77f5d5d3d4cce177648d7789f6c1a7399023ae58.nq.gz
    ├── 782a53afc9ef22e874d35eaf13636fd97d1461aa.nq.gz
    ├── 7851c36d1988d612b8305c37a408992f863a1b14.nq.gz
    ├── 79d6674f725e340c4d1095984a960cf0bf7d30ec.nq.gz
    ├── 79ff2dd48cab245a62234dce4b55ccbb324436c7.nq.gz
    ├── 7a560ee05e726d573e293b5df846c1836d6254e2.nq.gz
    ├── 7a5adebf70f66efc45d3f6e71f3c04920857f89c.nq.gz
    ├── 7aa5306e11494a91e49e2c30521e81a434653933.nq.gz
    ├── 7aed3540a1b67496e7833449b0aa78566b3c16a3.nq.gz
    ├── 7cba6ff02b38a432598d738d106443ca8dea3d5a.nq.gz
    ├── 7ebec5af2730841dade08a6c51f0bf6b70232569.nq.gz
    ├── 7ff066b155a10cbe13e1c9b7ab576db67481e130.nq.gz
    ├── 803932a5c4437f594a66935b76b82903eebdacfa.nq.gz
    ├── 8047bf069d2cc39f831f97c457117dfb1b52da62.nq.gz
    ├── 8055fc3f28caef095d08816ca1f3b6c4fb4e95fa.nq.gz
    ├── 80b51de04cdbc0aa7b98e770db827df8f25818d2.nq.gz
    ├── 80e1f5dda4c315123d3cb925f2533cadaaf3d939.nq.gz
    ├── 81992518c83b7021f183b395ab047bfabfd066bf.nq.gz
    ├── 82929a5b2daa745090212a922f6618edda350771.nq.gz
    ├── 837ef9e65f701aca925811a6a8805bcb0727d473.nq.gz
    ├── 83a8c43dfb8cc935f6bd7d1c5e76f7d64c971a9f.nq.gz
    ├── 83fa864f6a9c9bc91149b2a78755673fc90d048c.nq.gz
    ├── 8459f3a6697fe1d7f42395c3319fc9b3599d1778.nq.gz
    ├── 845ff4537a6219dbee3cfd46e44163c581f12c88.nq.gz
    ├── 85de9236eb78f01738bf1152e8a2e93c080b0eb3.nq.gz
    ├── 87a715f03e0bb6d3317b285c99a84f1d3882891c.nq.gz
    ├── 8861139cd925b6401f9b41a0275569d855eaeff4.nq.gz
    ├── 88a0ff112ad08a96428ffc8c61411ae479e38742.nq.gz
    ├── 895c7b9259f99f8c632146ee12b073a3751b2174.nq.gz
    ├── 8a2e5cfd210d93ac88ea3dc909eecd13efa11a47.nq.gz
    ├── 8ca5309d1efc53caaf907300c61574045a7f7e78.nq.gz
    ├── 8f576b9acc6bbc8ff0bc6a89154ec54cbc61df18.nq.gz
    ├── 925e305454b845d4e4bffe7014aa566e9047884d.nq.gz
    ├── 929ba2a07034716d637c4f7ad8afa5c4e3d28717.nq.gz
    ├── 942bcfd0b6afb69600d7d80b3fbac2100325b2b5.nq.gz
    ├── 952fd3c2504d848ec6d3103f8d6f8319c286ebf7.nq.gz
    ├── 95d026e4f22546c1c9067171eb20ea8c93613035.nq.gz
    ├── 960833755d1a1ba55d46725a529e0f5bce37a214.nq.gz
    ├── 971c381eb9cb82d17db6e0a414f5429c186a14d0.nq.gz
    ├── 99b8d3a2d3352e8b1a9f5a18975f2eb892e3bc75.nq.gz
    ├── 9b4b3cd82aa5aacb13d52d244d4976bdc17c8209.nq.gz
    ├── 9d91437e8c40abc613ebe7bb7cde406467230bef.nq.gz
    ├── 9ed877baa3277cca9a0b332e06009a57344473e8.nq.gz
    ├── a2209659936428e77d391d00e26deb2fabde5c9b.nq.gz
    ├── a65cd92f2188307dec7caf3694338f8508366607.nq.gz
    ├── a7de5ce52e36c6cd83a12d71dea98b75ba1cec20.nq.gz
    ├── aa22012383c9599dff1b521425b2a8bb01e53ad7.nq.gz
    ├── aaf3d3a5e0755f527cb2819b8a7ad1c8397102f3.nq.gz
    ├── ad287762e49070271fcd7cbab80b05109fc67720.nq.gz
    ├── ad89670354c57b9a182e85c20a9d2309ef5088cd.nq.gz
    ├── aed4fa323c2c8001593fdfdcd878a21718800167.nq.gz
    ├── aeea125a49609e12eef07816f953f249d018fe8c.nq.gz
    ├── b0b815e0685105c30ef673a43767830237addda6.nq.gz
    ├── b18eb25d4e5729acdea20f7f53fbdb23a9d1cb70.nq.gz
    ├── b1c099cd3f3f28953aed7f29cf163628a0c9c51d.nq.gz
    ├── b4e1b5da34b7767ecec24ce03fc320141eaa14af.nq.gz
    ├── b5e73de18df3adfcc05b28260aa60407dab3ae80.nq.gz
    ├── b5f53d09585e8e67ae4917716ee1ee34a5a6ba20.nq.gz
    ├── b5fdecccdead7488b4fddc03f575d18ee4ed1bdd.nq.gz
    ├── b648ac92333301658c4f49b315f21130c689c819.nq.gz
    ├── b7fa874c0d53b453bafb75a445e53c88353a37b7.nq.gz
    ├── b8198490c8cb0b7a0d71b67bf23c89ce7117d471.nq.gz
    ├── b90092e493a20e5ef73e75d102be82dda7ac974e.nq.gz
    ├── bb736642049e630d3caf3cdc1ece404c85278f98.nq.gz
    ├── bc31d1714d0de2d1eb1abf94a8e01c4d85b2f610.nq.gz
    ├── bced877f31454e062ab8d1cda30e0c74b00c2682.nq.gz
    ├── bdfa705ee6d7eddbf79612b6f7b1bc2686c7913a.nq.gz
    ├── be5f2b478ee922597b0026c6d02816b4bece0870.nq.gz
    ├── be8594ad0f38c03f453268cff2b7faec7a3a1eca.nq.gz
    ├── c086d7ebf514a12d61aa5620fa29c512f6dae1c5.nq.gz
    ├── c09b83609d1a4ed0e1448f9873bd5413f495ec86.nq.gz
    ├── c0dadf5cfb6cd7ce25ab1e2b401e8e00142fe162.nq.gz
    ├── c1f68ca3d260e9d3a1c3b96cb0af7b61ab4a9691.nq.gz
    ├── c2a4da85868e9c9cf755f3072bc2807b61ca29fa.nq.gz
    ├── c2b785a599abab85bea7cfe72ffe016c11e4611a.nq.gz
    └── c3ab49bf4601ae07e20aa11449123fc5636e7228.nq.gz

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

[qdrant/qdrant-client](https://github.com/qdrant/qdrant-client)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
