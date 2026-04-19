# Repolex Knowledge Graph of webpack-contrib/style-loader

RDF knowledge graph data for [webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download webpack-contrib/style-loader
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 091d37d68abfb071c4fbdd335385cd6f1af114c6
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 091d37d68abfb071c4fbdd335385cd6f1af114c6.nq.gz
│   └── repolex
│       └── 091d37d68abfb071c4fbdd335385cd6f1af114c6
│           └── chunk-001.nq.gz
├── blob
│   ├── 00b4210b800c7d559287aaf8797f222bd3da245d.nq.gz
│   ├── 041c660c92b36e939248b12a0fb99f203d210be2.nq.gz
│   ├── 05cf37476a0d6a1343f75c617a3d77db4cc86518.nq.gz
│   ├── 0640883947af16c27f28fbb72b0ef637ad7bb200.nq.gz
│   ├── 089c8925954d26bda11f170dd690f9784aad1ddd.nq.gz
│   ├── 0987760d0d4a9972861c1bd693072c7b68d497d7.nq.gz
│   ├── 105cefce5d311548ea693c66ddaf9ac63c2c26b3.nq.gz
│   ├── 1250bb3b295768c0ca97c0b499e7c95952c22f53.nq.gz
│   ├── 139242747745133624821900cf1b2d1e57da7118.nq.gz
│   ├── 141005fb5f9fe9d2ac065efbfc749fd9d97c15a2.nq.gz
│   ├── 145f6313edfc4a440263477a8c41280f269189c9.nq.gz
│   ├── 15648e5bdfce2ed1546f10738e16da97aa7a7809.nq.gz
│   ├── 1576d9481755a16d365cc110465e0189fbbe0686.nq.gz
│   ├── 157ef7e9536c1b47d7d6a9b1d5c08571ae25f0f0.nq.gz
│   ├── 15b9dca28f77aa557562d3903463b3d835f02529.nq.gz
│   ├── 17530ce05d3f03d79afee6aaf46d54d19fee7ec9.nq.gz
│   ├── 198b4c016ff285d02b41d7ac644a85473d2a7f21.nq.gz
│   ├── 1b5e7db847a74a5f41d1244002f3da6d37c98ffc.nq.gz
│   ├── 1cb16aa594944e2e97fff708d4b155f064390f43.nq.gz
│   ├── 1d8ac1c834a6b6cdb531d33f1998ff8698ef1bde.nq.gz
│   ├── 1deb2b998a234875aac01fd1f68763572ab4c48e.nq.gz
│   ├── 1e5304e1f64fb27bd80d09a413317b28389e3652.nq.gz
│   ├── 1ecd6866a6c85962ec3e3840ee56b9f52a4ece1d.nq.gz
│   ├── 201d0297ef003933862fcd34125bdc595c2b27c3.nq.gz
│   ├── 20b6494c46528d80c0b7368dce759a6684de04ee.nq.gz
│   ├── 23b7bcec5326b795b697b78ef93b6442ca95f192.nq.gz
│   ├── 2a760cdddfc721b466451ab73581fc0e47c7839d.nq.gz
│   ├── 2a993ade7d82065be92974039308526ba908078d.nq.gz
│   ├── 2e464d37178613e87ee71dc6c406ae88e1ae2c93.nq.gz
│   ├── 3010843382c225130f37f367ecf3e3b76e3de587.nq.gz
│   ├── 31d748d80f6cd9d1432dfce1d659a41cdec25d07.nq.gz
│   ├── 341bdae36414afdb20f8071e3ed085ba871dad6d.nq.gz
│   ├── 364b6df76b5d2d0839ba60a27ab3ef0cfe52e603.nq.gz
│   ├── 374f34781f4a4a83812e99dd082bb8f396f459aa.nq.gz
│   ├── 3a1531504058bc843ef629471ab3be982cc1a9a3.nq.gz
│   ├── 3ce9cf3263f968bca7e8d56ba82b243c5f2919d0.nq.gz
│   ├── 3d649a26a66bc29fc31710d2b24998f7631af894.nq.gz
│   ├── 41d2e012a5c359fde0d0e2c281346570cbd09dd6.nq.gz
│   ├── 424c7d92616918e176d37fc0fdc963fe0670650c.nq.gz
│   ├── 42fb95b3ef001b084de41c954c51598381745de1.nq.gz
│   ├── 44290da64dabdde92c056bb223598d6f9beb339a.nq.gz
│   ├── 490afd69cf93805c8235b5bc6adda763d3e036e0.nq.gz
│   ├── 4a11591a373164c99bfa484b7f247038a3eefdf7.nq.gz
│   ├── 4a6474c2b7fb12abcc15a56031a704dcfe9e08df.nq.gz
│   ├── 4b1c9c105d2514f53aef058d1104520ff846bfcc.nq.gz
│   ├── 4b2609cf6c34c207cc6999ecc56791d770c13ade.nq.gz
│   ├── 4bf0b136eae38ab555f536d6245370fef5aafe07.nq.gz
│   ├── 4f0f86cefd6aef499f37d0a47fa2d4e3333461ea.nq.gz
│   ├── 514756d06d008d81901e7e7e210dc640fe7e6e22.nq.gz
│   ├── 5293132ef067f9469a392fa8abf23ee5ff9ebac0.nq.gz
│   ├── 53d87601d5c7f73f7668f0308ecf5c1e1900e9fe.nq.gz
│   ├── 550abc2cf8aaad512cd7aef9b7a2fe757e2a846b.nq.gz
│   ├── 56f1ce5b8a9eda1fb627f79b14e59a733345bb80.nq.gz
│   ├── 5886c93ab4d277e859405fef018d07e807ffb063.nq.gz
│   ├── 5e7c7b6d7a63b3ae8efaf4dd3aaf741c71db767b.nq.gz
│   ├── 5ebd8cd59045b061aebedb793d74ff2c737177b2.nq.gz
│   ├── 5f7952820781fd0eb6556e4bfd7a00ffcab1656c.nq.gz
│   ├── 60c8aad3b6b77c24d201bc910038ff8a0d2bdd59.nq.gz
│   ├── 60f1eab97137f7dc51fc53c8e4f3e49f63342c38.nq.gz
│   ├── 6418e7358c01e3f684240e2e34254c600877838a.nq.gz
│   ├── 64e7176c51316fba56d91bca31c46698cbd4ac89.nq.gz
│   ├── 6734d7bfc71b8d4f3945e58f409398f64bce5d54.nq.gz
│   ├── 67fc140b98f45a8903b6349554e9ab0f86f0614f.nq.gz
│   ├── 6a37fe73bd3d8ff931d91720ae5b2141965e8801.nq.gz
│   ├── 6bcce77aff648094935da8465e536c43ffd247f8.nq.gz
│   ├── 6eaf1da8e7a0c43955c666aec84c98d68d145ff0.nq.gz
│   ├── 7248532e0b9ee3698264b8cfb6a91606e45a93fa.nq.gz
│   ├── 74212b5ef136c30efa5c6ca7126391b0b35e2217.nq.gz
│   ├── 782ad5ccb5c65bcdad39aadc355463212d3ba043.nq.gz
│   ├── 7a92f252ea47a622f6fb5b7d11780ac2bc965159.nq.gz
│   ├── 7ce19077aa1cb1e2c583aa7ec19f45a9b9874d16.nq.gz
│   ├── 81c6f9e036a4ba43449ec1ec1e0311ce5fd7628b.nq.gz
│   ├── 834c32ce5313064699dd78e45983207b2d5a3ca6.nq.gz
│   ├── 85f47c2b421f93240f08c144887b2b789707129d.nq.gz
│   ├── 86a8e2dfa89e6abcce655fcf9a6f65b285229e15.nq.gz
│   ├── 88e0f8fc657666841ce9c32364cd06063b8c409d.nq.gz
│   ├── 897e08c5444388a1e86e3e535b22ee9ac80ed6ff.nq.gz
│   ├── 89dc5b79ec6b27e23acb6f3ed3808dc7ae4bab67.nq.gz
│   ├── 8b3ce0681c3b37643cc88813a816dd258bcd1b6a.nq.gz
│   ├── 8c11fc7289b75463fe07534fcc8224e333feb7ff.nq.gz
│   ├── 8caba14f7ea1e8be9772f95a5130a7e7a24bd36b.nq.gz
│   ├── 8caf799d12ee4ca4b44cde922ff29e8eb11b703b.nq.gz
│   ├── 8ebce4e41427c5bc6bd4ccbdafbb09cd0ea611dc.nq.gz
│   ├── 8f6dbb0b9fe75363673a6cb604d2d4fcbb314658.nq.gz
│   ├── 904b2afdeab2ef8aba2e43b33acc8b5bf38f7ba7.nq.gz
│   ├── 918735a0cedb95faf59b2e567f74ec455a2eec48.nq.gz
│   ├── 9415670d00364810adda012049e8df10772072ee.nq.gz
│   ├── 94cb3c326b24b300f511f6a235bfcca4c3073526.nq.gz
│   ├── 96b8cb8dc565868dd9381f790da92c34ea04e6d2.nq.gz
│   ├── 99b5418f82ff3e5c2c137b572f24efa6076115ca.nq.gz
│   ├── 9b32e75c59922502b6171c01d1b56cc80111cebf.nq.gz
│   ├── 9fbacf7aa21ec977dec96054739d973483420149.nq.gz
│   ├── a15c877ac01f4146af0d179f365960a37fe4632e.nq.gz
│   ├── a1b05e5c77f8e52d753eadb492bb3af66fd934f3.nq.gz
│   ├── a3cedd77e3296d1f5f0c68e47c533513a856d620.nq.gz
│   ├── a6e481232c35dbab3feaa50111e1ec45584f17a9.nq.gz
│   ├── a82f7eedea04689d121937b25ee04a0588a66f4b.nq.gz
│   ├── a94c0c958c414714ef7159e42324b180ea732e4c.nq.gz
│   ├── a99281855f0ca590473f744faff10f38b6496898.nq.gz
│   ├── ada9d35186bfc61edb572c012313a5d5f1161c32.nq.gz
│   ├── b0217867514dc6699fafa29910e966e82c700eaa.nq.gz
│   ├── b0a5b1bda578e3b4bc048784ec18e0e6628b6237.nq.gz
│   ├── b1875fcfdec3b721de18a363db0e3fb68266658a.nq.gz
│   ├── b3256b6ddc0bfb2983bff1e2175f705f0525997c.nq.gz
│   ├── b4afcfa753c47e002c3523a0a137ea3cc62dda1a.nq.gz
│   ├── b64790266a93eb5c353b7c135588e325ac01dc4b.nq.gz
│   ├── b69906493b508ec0d42d805b2a4ae50be2fd3025.nq.gz
│   ├── b744e13189e93d9e5b4a04b99fff18922fdf35dd.nq.gz
│   ├── bb3447d41dbed08ee292a36fd926acd5d951e5cc.nq.gz
│   ├── bb3becb0c0f54e6366aee13fc40e1f741afe2535.nq.gz
│   ├── bc50ea8f0caed75317cfce79e7125ccdddd17eca.nq.gz
│   ├── bd1ae2765501b752240b64dbae7e7fb921901663.nq.gz
│   ├── be100a9578dbfb6785d98ae932fc01b8cd360a9a.nq.gz
│   ├── c52afd163090a6173ab86e623c45839a511b5f0c.nq.gz
│   ├── c60a5017a9c3b7b64cabfee035224ec6d6ff3686.nq.gz
│   ├── c773dfd6cf41ea709662404080272fdd61e6052a.nq.gz
│   ├── c9f0e85d1a716c3344f5c6334987d2c608afed4b.nq.gz
│   ├── cada69437cd6b033d683673910fcefe20dc201f4.nq.gz
│   ├── cb4a8fa615adfd79afe2ac9c968a06fea0f52ff6.nq.gz
│   ├── ccf22a056ccf7f683ac9f0094883115ef39da781.nq.gz
│   ├── d1c0037ff0d8e65a1296804104bfd33f692ddd8b.nq.gz
│   ├── d75d83275b9a6b95751c3c5eabdc7bc45269a32e.nq.gz
│   ├── d92ca8c8a9c9c046e3f53218fd1ce1fba42ccbd1.nq.gz
│   ├── d9ad4e154c1317e3115c25d3e29f3aad67cbe761.nq.gz
│   ├── db71418e884fe72c26fff56a0c3d7e89b0c4293d.nq.gz
│   ├── dbfeff1deba712b004271f641ab291796729a35b.nq.gz
│   ├── dc8321a3c337cda6ed16baea9311bd82f8b2a8dd.nq.gz
│   ├── e301fe1703af8a72478913040d4c969d5b9d46fb.nq.gz
│   ├── e3947c7abcf04c0ae24d424c92fe19c9cfeac8d0.nq.gz
│   ├── e45ad5d1c65e3bfaf51d8df76506b0e668ba1cbc.nq.gz
│   ├── e4aea6d23e30bab68fda8ddd66c59cc3d12acdf4.nq.gz
│   ├── e500e77a394b10d49b50d696ae9c3b9097baea0e.nq.gz
│   ├── eba301807ce317cef0be4b2a0e916691474e71a1.nq.gz
│   ├── edda5bbf7bb1e6bced376d9478c7c10879bbc48b.nq.gz
│   ├── eee9f1078b2178743823758d2f4577df4898a66a.nq.gz
│   ├── f147ab69ddaa3f07283895671ed8c9ed67bd5b1e.nq.gz
│   ├── f2d8a3c4f5ef4f37bd554582ab08f63297f8f21c.nq.gz
│   ├── f2feb4c72bc3d2953d219e7da29e217b27ff9b75.nq.gz
│   ├── f38a931fa5c1ff71aa4037e0096de91e9b0e48d2.nq.gz
│   ├── f5c21c128a328042ee4e708cd14b83ff6ca0df8a.nq.gz
│   ├── f6a6e752f06f6a9e3996c5497feb80a9d4ad2173.nq.gz
│   ├── f78c7d145653a7d8b640e9b8901e6c0f43f03ebb.nq.gz
│   ├── f8f1e3121b45ab5f3772a81500e5e3c7af9a9163.nq.gz
│   ├── fa381d83f535eb758e5a7619bcf060a88c5d91ef.nq.gz
│   ├── fae640d02bf8274a08980c35d9e83c8a90d910ca.nq.gz
│   ├── fd2bf708ee9629270e492529e39b2cecea4732e2.nq.gz
│   ├── fda929a8a173052fb1b288e1ff4a6e7caf62ee76.nq.gz
│   ├── fdd8138a6bec115f9a2d9af4a28df023b0c582c4.nq.gz
│   └── ff7e3b3d8d79841e999fe68a061592294926b28c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 091d37d68abfb071c4fbdd335385cd6f1af114c6.nq.gz
├── filetree
│   └── 091d37d68abfb071c4fbdd335385cd6f1af114c6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 159 files
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

## Source repository

[webpack-contrib/style-loader](https://github.com/webpack-contrib/style-loader)

---
*Parsed on 2026-04-19 by [repolex](https://repolex.ai)*
