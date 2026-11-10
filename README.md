# Repolex Knowledge Graph of ruby/debug

RDF knowledge graph data for [ruby/debug](https://github.com/ruby/debug), parsed by [repolex](https://repolex.ai).

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
rlex download ruby/debug
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6510cfbc7496c55ebbefa437a25c17ca58f7c5eb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6510cfbc7496c55ebbefa437a25c17ca58f7c5eb
│           └── chunk-001.nq.gz
├── blob
│   ├── 00c6252f192f817a19d93b3fbd4a59d206cbe314.nq.gz
│   ├── 0a3c7d266d2a697f41bcc9691f1bfd44c71b0ca6.nq.gz
│   ├── 0a92fe356e7c6586340170478fdc549aea097fe2.nq.gz
│   ├── 0c98435bb2449c34cab8e04c4a0338a8354b6d86.nq.gz
│   ├── 0f18e14acd1802263fcfddb7a2f8a890c9b3ce59.nq.gz
│   ├── 1388558e1f1ad0d605ace816732bb64a1cc10fce.nq.gz
│   ├── 144904eab6d1a95d9f2a44d725e1682173179db3.nq.gz
│   ├── 14b5e978c7345e417398a8d38d831ad6e6754af0.nq.gz
│   ├── 150cfb4b2cae5b55c453052e5d5aadab776fe1c9.nq.gz
│   ├── 16f5c4436a2ae67fc95f0725f2b5602c93d23ffb.nq.gz
│   ├── 1b1c723cfeeac7141313150c98b60cfc1965e0e5.nq.gz
│   ├── 211af9e493e2ea8e0c103eb29296eb6675427528.nq.gz
│   ├── 31432291d4a39c9233db8adfec40127c89313631.nq.gz
│   ├── 31a7088bbfd506b1d2c9862684af885b5698087a.nq.gz
│   ├── 32b94be0992af39f5e517f116a589dbabd65eba7.nq.gz
│   ├── 3d937fdea5dcff6aadb00fa9c15ca8d29f646c0e.nq.gz
│   ├── 3e6a3c437aaf5c10d5ee18e17427ca8727fcd5f2.nq.gz
│   ├── 3e6e8b2db25badde3ab907b8f538f184b70ad9b0.nq.gz
│   ├── 3ed26afa8da233617c1b3c942b55077711ca203e.nq.gz
│   ├── 3fc92ea61efe1a4219d1b177cd9bec1396002677.nq.gz
│   ├── 418e0b2e4d036e2bdf36863175150387404dc42f.nq.gz
│   ├── 458870818b503a2cb6c5677e4ed98e53f98c0831.nq.gz
│   ├── 45fe1084337aacb704c44ff2a72fa877bb24e48d.nq.gz
│   ├── 4733360ff6d1fefd85410a2e03b75761aa760ec6.nq.gz
│   ├── 47ecb4765cc40d0a3a6da028ca3c9e59aec198a6.nq.gz
│   ├── 49c6923c1ed7dd64e0c87f818e346935c60a3e47.nq.gz
│   ├── 4d9dc631acaf93585e615843e29421b9d740c893.nq.gz
│   ├── 4ede33d41d484abaa59f1577e4b764c49cdfaec3.nq.gz
│   ├── 51a23faa2613ce15dc291027311f77577dcc65f4.nq.gz
│   ├── 52e43cf7d32eef03fc8128668d6899216c08500b.nq.gz
│   ├── 5427959d3b603153ac4b4b3f97d25d9d29a3b0b3.nq.gz
│   ├── 558f5466be3673f40b1fe6e9ca2a20c1db0a7f55.nq.gz
│   ├── 57f49b96b6266fcaef94b3a6ee527fc7dd319cc3.nq.gz
│   ├── 5fc0512ccb905b9b98484239ab835867c45b09c2.nq.gz
│   ├── 602381d6432b0870e438fb4cf1c1c438dbf45523.nq.gz
│   ├── 61109da2e20ff0877093b1568c325198afb6761d.nq.gz
│   ├── 634f707921c9e9ee2311f8f0b23357462801873e.nq.gz
│   ├── 666ab43758474862d6a9ad3e618a3d859b904017.nq.gz
│   ├── 677becd63e5c61a2b395964e295478023dff784e.nq.gz
│   ├── 68ca4679865e049be1f0f9fe02df164a57dc9d92.nq.gz
│   ├── 68e1df260c0d35d6120c58433f82a5aaff2c62a1.nq.gz
│   ├── 6b8d355a9d62993c2ab644373ff4fd3896ca2416.nq.gz
│   ├── 6cdfb608c0870ff7d7c57d8bca2d1756559f2b21.nq.gz
│   ├── 6d87b6da4cc4cd4284440b871a5cd2cc1bdf8103.nq.gz
│   ├── 6fbc7afa0fedec5956d0608609d6a7bd6ebb0c56.nq.gz
│   ├── 72e31affb670f7eb2bfd5ca21c1df24502b70875.nq.gz
│   ├── 73b9a5481105054cb5e1e3fae27fed10c5476adb.nq.gz
│   ├── 746f9acdb6cbc0bdeada0f58c5e685664929fc91.nq.gz
│   ├── 77560e82c88cc7af9651297702ae3ddc43182d66.nq.gz
│   ├── 77f6caa66b8b7eba2180a41197742eca948dd402.nq.gz
│   ├── 78c4d2174fd814ff69f8a57d67c20441a0a5b4ac.nq.gz
│   ├── 78e0b5bb059f425ada51a413594ca9c818ac6ba2.nq.gz
│   ├── 7ebb4bd3131bd804f88881c18cf574172b01311a.nq.gz
│   ├── 7f01a48e6d2423861b9d36b172d6db1a9f713b81.nq.gz
│   ├── 84a60d1e409c64f6d7d2b198541c456d781065fa.nq.gz
│   ├── 8bbcc75b9ea031474dc211a50bffff5dacb2c6f7.nq.gz
│   ├── 8c6056a6a13ecc8530ac62cdc8b65eaeb841963a.nq.gz
│   ├── 8f0580fb1d6cff7aa762241ffba1f616e3711913.nq.gz
│   ├── 8f78128f7a7edb9833183b9828d7b00b8e97529b.nq.gz
│   ├── 902e3a24f1986170ecac3865ac5ab622d567e670.nq.gz
│   ├── 907db2d1f16a638152e84fa742b90eda53b9c797.nq.gz
│   ├── 9565a74da556a35c8dfa3dd2a941086232e254b4.nq.gz
│   ├── 96e8b2b1c7990fc4efa316535d8eb742be802c83.nq.gz
│   ├── 972d181039df5927796ebc9d80892bc268738ef2.nq.gz
│   ├── 9797975f2c8295ebfb75cac5f2227351767c08d7.nq.gz
│   ├── 99c78af1db3a949848aea926535880aca68eb324.nq.gz
│   ├── 9adb0979525c9ac12771d1443f17c2a97ab31580.nq.gz
│   ├── 9b82419e8dd23aa7c09785c6f23ee2191f7be6a4.nq.gz
│   ├── 9c4f5417a730749cb48ae49d730b0d49705b8af5.nq.gz
│   ├── 9cf32756ea1a810350427eae9da0d45612575ab0.nq.gz
│   ├── 9e23904d44d1568afc28d532fc086723afe00920.nq.gz
│   ├── 9eef94f2110152594b1881857cd9d6e5275e6f7e.nq.gz
│   ├── a009caefea81f259e19d842356cb43ecf1710fff.nq.gz
│   ├── a3ec885bdb4d27a684cfac3ef7757c8099f8f4ad.nq.gz
│   ├── a4890123af44b83cd14563b1acd1682bf64dcd4c.nq.gz
│   ├── a5af775af2f541ce01e70bc5d33aeaff85783806.nq.gz
│   ├── a78f70ebd73f70cf88e4ab619ee6426dadd14945.nq.gz
│   ├── a801d350248f767bbdf9fae7acf59b8e63e53292.nq.gz
│   ├── ac44c6fdab8f19c5719aea0205db333477a44ba5.nq.gz
│   ├── acc71c9034913ad142a357045201a10e91d84d90.nq.gz
│   ├── ad89f2c2a13ac5d70737aba5f8fb1f355d5fd33b.nq.gz
│   ├── ae1e1228c85cd0f1368fcc1482210b1f73bd580f.nq.gz
│   ├── b0f48ba62d0181257dd5f821e476eaa1ad3ecd4e.nq.gz
│   ├── b1749b59e61323425878a00692f9660b0b2ae7e4.nq.gz
│   ├── b174f9f9661995b15d35f9dd395ce65e3c5500a8.nq.gz
│   ├── b18fd2935736768f4b1eb12f15709ba4c2f05171.nq.gz
│   ├── b26999c653156284a4f56a144ebbd47e5f795ee5.nq.gz
│   ├── b27263d46affc5d49cb8fe4dec1888a8c968d8b8.nq.gz
│   ├── b27a4229ff67429ff27f9aebf2efe69aacc1cda7.nq.gz
│   ├── b3f2403576111b4e108a0ac6ceb8285e6feb9561.nq.gz
│   ├── b4b617ed9bc177e5aec837c905a1eeb827591207.nq.gz
│   ├── b5c0c920f03d978ff0cce03b8bc80db9b64e91ea.nq.gz
│   ├── b741e42aa29706ee8f0319f4b8057bbecdaaa4f8.nq.gz
│   ├── b9083d1a2602c1347d45b83ebeec80bd2831231c.nq.gz
│   ├── bf5d31a2c9f467cf0b2886eb3049bfe75e14e27f.nq.gz
│   ├── c025521cca1e997bfb57eb3f20db98395946cfcf.nq.gz
│   ├── c152b3f0161838d4c6afdb271903d8e83fcafae1.nq.gz
│   ├── c173c33bdb72f76ffd3319f42f7675ee501ffd19.nq.gz
│   ├── c20bff001ba5fff5e5da7b743eb508fa26f39409.nq.gz
│   ├── c3c3b8d5ee540c2630067ad1cb15b56a56c51ed2.nq.gz
│   ├── c83c63a5f76c8a232bf72f49e4217cc3d66e05c2.nq.gz
│   ├── c867f2f95842d917abb8907b4d1230406ffafee1.nq.gz
│   ├── c874f112052105b3c5a22c0129b64718a28cd6ca.nq.gz
│   ├── c9049d65bc47857562e7ae0213ba10961eb70bcb.nq.gz
│   ├── cb24999605e68d1ef7ba86ce94a84fc1755bf19f.nq.gz
│   ├── cb3fef1cb9370f962d3bbf3c4f7fa9d13bae65cf.nq.gz
│   ├── cc511416e5daee44ff11a638e25a877e0a37db99.nq.gz
│   ├── ceb41d0525d7b9f3d55aa2bba81b430aab308908.nq.gz
│   ├── d17a38ac26711b26e691c76af83d1d02012bcffa.nq.gz
│   ├── d448417b4fd0ad5699ade3591ce39b07933814d5.nq.gz
│   ├── d4addf997835e2a978942c0093b4f7eb3cb128e8.nq.gz
│   ├── d5b3811a806a6f3f8a778b480793ae09f52fd9f8.nq.gz
│   ├── db47ecf621999e43a712f0754bb66b16be99bfc2.nq.gz
│   ├── dc84b68f95c6911e10ebf3490cf348a97462c44a.nq.gz
│   ├── dce67d860af47a4eb630117ce03624bae45dcf26.nq.gz
│   ├── dd483a583c2c380efed0bd5bd2a9b735a31c068e.nq.gz
│   ├── de19c267bb4a4f4442550d4fda77f640292af0e8.nq.gz
│   ├── e11c9482a970006763970fafd22b80162d5eeda3.nq.gz
│   ├── e3a8d20854428cd2b62d7fcd03df32ad7100f279.nq.gz
│   ├── e48eeb2cf175d4b0d28cfab37a2620e4b236d7ab.nq.gz
│   ├── e82c616855198526bf212c6fd88c19ec46f817db.nq.gz
│   ├── e964c7b6a6b7ae03f7d8f2693e57bdf28867ef27.nq.gz
│   ├── ec2f28403f360b36f1dbab758bfe35a836c05e04.nq.gz
│   ├── ed2ec9d6c7cfdcf7bb409ff77b2df68e1f187726.nq.gz
│   ├── eee84d8e2298f05793a3176a584542cff97b4178.nq.gz
│   ├── f0225147b2652f77b553ab4a8db2f3368ec6cfd5.nq.gz
│   ├── f0fa56673257a469e694d90f5b03271e31374148.nq.gz
│   ├── f32f43d0cc08547e20fe7365acd8441400f9ef58.nq.gz
│   ├── f42049b63bf834e64fd5a0537b287dc1358943aa.nq.gz
│   ├── f53c61da72a921d8d69ff807e30a98e4e200a679.nq.gz
│   ├── f77ae68aedfb14fa9c68cb759e90cf102513cc82.nq.gz
│   ├── f836e4d6f1bab0842ceced9543ebbe25a15379e1.nq.gz
│   └── ff710cd90e305456fe167571bdbac2f04ff534e9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6510cfbc7496c55ebbefa437a25c17ca58f7c5eb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 141 files
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

[ruby/debug](https://github.com/ruby/debug)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
