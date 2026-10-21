# Repolex Knowledge Graph of sanic-org/sanic

RDF knowledge graph data for [sanic-org/sanic](https://github.com/sanic-org/sanic), parsed by [repolex](https://repolex.ai).

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
rlex download sanic-org/sanic
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5ffc7b3710838eaf016d2f9612a86a08626915e5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5ffc7b3710838eaf016d2f9612a86a08626915e5
│           └── chunk-001.nq.gz
└── blob
    ├── 002d4476a899f1092d8fe23be27bd73f31e1046d.nq.gz
    ├── 011570da5c20ad0947e2b8276fe6e83576b27008.nq.gz
    ├── 012e6b81248b7a7d25c3fca162aee058aeaff716.nq.gz
    ├── 0147f75516123065b2aa15beb51e8cf7549f4f1b.nq.gz
    ├── 01c6c14cb45fccf2a0fce85feff09f4abbd54caf.nq.gz
    ├── 0237c73871a65101c0d02f4905c1d27d316c418f.nq.gz
    ├── 02459ab7f0ea88b0f6aae842ea8dedb2f437514b.nq.gz
    ├── 027b621c817c3ef7da1246b391e0e5e4f2df990f.nq.gz
    ├── 0321dbdb63c248f252517a4ef2504551551f5762.nq.gz
    ├── 03791fb93863bda74aef731661bb904ccd1b84a3.nq.gz
    ├── 038eb81790b02ce5134116fb00d25d59553338eb.nq.gz
    ├── 040e6cf45d615a7b87567ed0564ffc92a492c8de.nq.gz
    ├── 043fffb456e0a2771147c97309e849eb155c291d.nq.gz
    ├── 04962f5f6cfd62b8f1261dc278df5c2496d837f7.nq.gz
    ├── 0526b499990f1912f1b473325732670f591d79ea.nq.gz
    ├── 0602d06523d00d81c653cd5293f65a663faa4c87.nq.gz
    ├── 07259ea8bed55a8d41b98e683dc68be868d6f3e4.nq.gz
    ├── 0725a6efa8e8b2671966d1678280c671a63d9d93.nq.gz
    ├── 082842417d298bd23fb1735a78f2a9f2fcc3deb1.nq.gz
    ├── 0957886f4dca51dd2a2d1f5e2e54193456217396.nq.gz
    ├── 09881aa7676651635703fc67684999caa886e95a.nq.gz
    ├── 09d241539297bb5af7610a16f0b46762d8018971.nq.gz
    ├── 0a15f80a17b9b032fc096ef119056deabc1a7654.nq.gz
    ├── 0a2f56a2412cfed4329370ba70bf379096be2385.nq.gz
    ├── 0a383c19f12b16aa7048dd1eda997335016dbc26.nq.gz
    ├── 0a416474356094830c3eeadebe4dc442981104a7.nq.gz
    ├── 0a70c09f790e14bbe4f9b5797ea75ecf62a69146.nq.gz
    ├── 0a890eed687dace223baed28453ab4736a4d0b46.nq.gz
    ├── 0ab5ed94c86bd42afc07eeef812575c4f8f6c4d0.nq.gz
    ├── 0b5ed31095957a573b4b91562edb5de5a27d3009.nq.gz
    ├── 0bb7a4f95c00732dd4e9cd9706fd6b5cabd87747.nq.gz
    ├── 0befe2b105bec741968034cd22b191c2136bf248.nq.gz
    ├── 0c7b1549c869abd70a1a0fa15c9fc8a18df6759f.nq.gz
    ├── 0dc25dd1781d42fdb52674e47a97a52c5c6d7ae9.nq.gz
    ├── 0dfc62d35bf98728b7b510dfa1dcd0b95e0f0985.nq.gz
    ├── 0e6acc7ff4407af453219349c2c54ae59bf96401.nq.gz
    ├── 0e87b7366ef37ce9faca87cdb3f52a5c7b4cfd20.nq.gz
    ├── 0ea5a9cd558919bee01a1da50281412ce1cf6e60.nq.gz
    ├── 0fdbd0d9bfab302d699a82fdf758f15bfd1631eb.nq.gz
    ├── 0ffc54c41f47cce64e6150fa7cb3d04aecab4ba8.nq.gz
    ├── 10cbae3047d5080a8228eeca614ed5ecf7c359bc.nq.gz
    ├── 14d1d7b70d3c429700eda99fc2315bd912d8a1ce.nq.gz
    ├── 158936446e20027ac05ce51a2b3d191cc096a9c1.nq.gz
    ├── 15b0689f9f8aec5e2bd628cdd101157a39b07160.nq.gz
    ├── 16648168a4136190adb55f88bb08c0a675ea6ca9.nq.gz
    ├── 16d1df79106d1e5e1635087f518f1653682ce745.nq.gz
    ├── 1798355e9453c699fe806eb2f6f3f70adcbd42cd.nq.gz
    ├── 192f71e44e41507ce934ce3c7353d3c4d2a2c08a.nq.gz
    ├── 1c5ef13cb5d587ff10a7bf14a965d0d7b74573ec.nq.gz
    ├── 1d40d992ec6a34e34ace3b46af4b20873910aa83.nq.gz
    ├── 1d9046ab37e5835e191715aa19bf7bf02acd1557.nq.gz
    ├── 1def3977554bb11119ca0a9da6f26933ca05c14a.nq.gz
    ├── 1dfc1ba4df3baf5d5b03cacda002d4b0ee69b98c.nq.gz
    ├── 1ec1670a0673dc8d4caf82e2c2e816187f5feae0.nq.gz
    ├── 1f53798bb4fe33c86020be7f10c44f29486fd190.nq.gz
    ├── 21084267cede5e24f938367739dc52a4f2e300b1.nq.gz
    ├── 2157da7e05fedddb9d9149f4cd9e77ce15a0d80b.nq.gz
    ├── 21b9b8e9b5d52a95c7aab6d89e0fa672c0ad8935.nq.gz
    ├── 220481c67ece4faf5839ca8876ad5fcb8acebf01.nq.gz
    ├── 2220b3fed92f56abcfc8ebb0a667fb4bbae8d06e.nq.gz
    ├── 2270ea9d18276e4d2ab53a1ccb4143eb3917551c.nq.gz
    ├── 22c259054021cd1d85ad512dcfdb4f52fbd10455.nq.gz
    ├── 2339feeb99bf4a45dd1b68a1db4eae3047c8b47a.nq.gz
    ├── 245c197b9f77bfff7cef9df64cbe54fb48fbeb3f.nq.gz
    ├── 2487b85ec117fb1e796975bfb6486a7dff0a624d.nq.gz
    ├── 248e4f2c2141b1dd340ef30c6f895d4fa09646f8.nq.gz
    ├── 24d1c08c0544f4c0765c6e40e46e441f7ed4b415.nq.gz
    ├── 2538a2db93ea251abb684740d047ec9893dba5e4.nq.gz
    ├── 257cc5642cb1a054f08cc83f2d943e56fd3ebe99.nq.gz
    ├── 25dcc520441b6e6fd0d77ff101c39981908d08cb.nq.gz
    ├── 25e3d2f7acb34477dbc23566e562051bb1347499.nq.gz
    ├── 2826be83027912820e31bc94c9f68f274e7ddb56.nq.gz
    ├── 2842844723f8d9e3fd1b84f0cfbe856311db8fcf.nq.gz
    ├── 285cf0df8ec9639e7cfec54ff8b872f999fe8601.nq.gz
    ├── 287055f3f7f245e4528a7db73a5ff989085ad014.nq.gz
    ├── 2a44f4902fee965dbc5ac57451d6978b9bcad549.nq.gz
    ├── 2b7eadeea2b3c7b07cbd3acc5204043e14cd3771.nq.gz
    ├── 2c1da4ccaa06d7110ef11d491be76143dd0bad48.nq.gz
    ├── 2c309891956db2c785652290b4f50e0b4f0cc941.nq.gz
    ├── 2c6870c2598422fb8e2588d725a10a2e4bce0744.nq.gz
    ├── 2cb6a5431cdc13afc35ad772b5fbb90cf3f4a1e4.nq.gz
    ├── 2da0f7a11f7ec229dc02a7488a0ee287ec224c33.nq.gz
    ├── 2dc4973e852d83b61922ca24de93efc6bf578743.nq.gz
    ├── 2f43b3fa925c06a0aed1585e31168274cbf76364.nq.gz
    ├── 30077178f2372937fadc049d5dd0f0245ff4a22e.nq.gz
    ├── 30632946e2d8496af233a229b688ce17d69e4e0b.nq.gz
    ├── 3122dc4c5e85ac9e18674ac4eef4700b56565f94.nq.gz
    ├── 31dc56fd0a28b65d64f10c52652dcdb034de2717.nq.gz
    ├── 31fd1a28e73f5d96a5613963c275a5166d6f23f9.nq.gz
    ├── 3200f17376c6cdf5599985e11ee45fcc2aba44e5.nq.gz
    ├── 32195bfa1378be85364143eaf2a779de031c1f8f.nq.gz
    ├── 322f6ddb0192eb00c9b049eb5c0ddc815f6ec6b3.nq.gz
    ├── 324d05d50c453190b18abd7a42f2a7012cdfbd8a.nq.gz
    ├── 3269a12d131c4bddb9f8feb5c1cadd4899251c30.nq.gz
    ├── 32d689a2b5b5c03724f69ebf256c6196047351b7.nq.gz
    ├── 330c8e246dc82e91e069e94703d5066fd15bc66a.nq.gz
    ├── 3321f234395bf5bd50e60bea5924aab44e73cd49.nq.gz
    ├── 334edde3e4e5fc2a7fc71a291fd1519f0bd43470.nq.gz
    ├── 335a3be8a46c902094d44ebf7232e88ce6f9d82f.nq.gz
    ├── 33c7142de31fe4db2190c31431ea3eb4d5fa2a26.nq.gz
    ├── 344159610d086127ce85a0f837704ddd571d7a07.nq.gz
    ├── 347b489c6c8a911f6d19f6ba31a6009dac1a9f7d.nq.gz
    ├── 347c46b207fb7cac3c8ee1a78eb5726d1aed24d2.nq.gz
    ├── 34c15d66485653c6483e3493c559b89e1b38adb6.nq.gz
    ├── 35740e3da6ab512bbd79437bc02e85ecffb6d2b3.nq.gz
    ├── 365ce5cfc2a9b5e228eecbaf52080fac03a4a2bd.nq.gz
    ├── 3743cb77ef9114ef4d6386334e00f9991608751c.nq.gz
    ├── 37932fe1af69f5ddedd9b397c777a27cf8c602f6.nq.gz
    ├── 38555e4da9f2ccf6258ae4c295db6580fc5a53a4.nq.gz
    ├── 3887c127a6c7d40c731deb4c875b086f61c51e93.nq.gz
    ├── 38dba024689428090c33db5873273c34f4d65188.nq.gz
    ├── 3932e3cdc878d18c1f867f009b12844f5db25be5.nq.gz
    ├── 3a01fc104ab350942536d85a3f0acd0cd418c34e.nq.gz
    ├── 3b2fa5fb86d4edd3880279544702d5b941f4455a.nq.gz
    ├── 3b39e5d7f68d70bca8d607aeee0496df4b17cb5b.nq.gz
    ├── 3b961ed8d4d8d84d51e607095d292b980242d660.nq.gz
    ├── 3c038a6a914f922ebb25fcc6c13bf9756150dc14.nq.gz
    ├── 3c172786028ae69a9c3152b1e63ae2628bd54039.nq.gz
    ├── 3c2d2827ded37ebcea7328a87d184f7c7bf30f8c.nq.gz
    ├── 3c478dab4b993662f60e764507309e9cbe90eba2.nq.gz
    ├── 3c5bb59ddbfb909dbcffb5ffbb27fc585bebca9a.nq.gz
    ├── 3d6e33d03e525278ff984bafc6a6943d16bb7787.nq.gz
    ├── 3d8028f8fbfe848fd6c69ed5a9a87b65b357a6be.nq.gz
    ├── 3f6cdf553e4b0bce6227e2c292736435b26a2267.nq.gz
    ├── 3f709ad79842cb9bae564b69d01a54e39f23c315.nq.gz
    ├── 3f8bb075d6d0fda2db6d7a9ff1bbd99e1428e1f0.nq.gz
    ├── 3fdc17cd8ffdcb1ca8c1d3fcf29fbc4404552439.nq.gz
    ├── 3feb38fbbf29b5470356ee73cf3639474af4fcef.nq.gz
    ├── 403a06e5a9f98bd32c266346424b070f83e84544.nq.gz
    ├── 40f0f5a43d074413680f515c301cb01c483781cf.nq.gz
    ├── 4107703b0f895822160f109d1c9efd40cf8bd4ea.nq.gz
    ├── 422d7aa37d97d4c3d36384f4246154afc841723a.nq.gz
    ├── 42c736ae08f97b061e5bd0e965a80f7c235a606d.nq.gz
    ├── 43864b3d4872f5521ad8edb459e2e201e1bc4617.nq.gz
    ├── 441eb13b6740cfd985ab86357552ecd75832f6db.nq.gz
    ├── 44f07a120c62fdbd9ee17c70ba0a4717b815e35c.nq.gz
    ├── 45dfff08521f6885375001b9a8597282447c4a29.nq.gz
    ├── 45e7c25afdeb47f2a6f31323f0b6c397e99bdb55.nq.gz
    ├── 4680949be046dda2fd35e3e69fd8f1352fdbee8c.nq.gz
    ├── 4777a8da22755e99743ea8b2c35a37aa1aec96b2.nq.gz
    ├── 4958e83bf8ef2a5b5d77c3c3e9394ff004d2e56a.nq.gz
    ├── 497deda92a7de25e20567a6bc1684d0ae0290094.nq.gz
    ├── 4a08fd03b4f7db7f81979f6c67f28bcb47b182e9.nq.gz
    ├── 4a2e9de8a0e8318548c9f2da6ce462a666370154.nq.gz
    ├── 4ab7feab98fd9257fcf2d13db342e85c593f0184.nq.gz
    ├── 4ad68cbaf957afc1815b4675f04c354b633514df.nq.gz
    ├── 4ad7d4fc2e0d3fee96855fafbc5e2b3d7b684836.nq.gz
    ├── 4b6f89e0e86a85d3f8c7a096713d27f2e43459ba.nq.gz
    ├── 4b8fda479b3b4b284fa42692bbba6a1a64fdbcf6.nq.gz
    ├── 4c0b29a0fd813d04c71cdd39672591900cd681a8.nq.gz
    ├── 4c5c3dd1b26c2cb90aa08b1d0f6284d8d2fec130.nq.gz
    ├── 4c738c7fad36f3b24971450466325d213335540c.nq.gz
    ├── 4c821449f9b536195f3424d40c1284c4eb1e90cd.nq.gz
    ├── 4ca14a9f6eac3df261585039cce7351b01ac57c3.nq.gz
    ├── 4d1df5b72026986339234f39e306fae69b6e8219.nq.gz
    ├── 4daeb8072e42ef3d40fcd8e43106d299f402e65b.nq.gz
    ├── 4e6ebac619b76465b5d04bd22cc72675d885d5a5.nq.gz
    ├── 4e9187e1b2640279b46eaa6134591bfb42de3ed7.nq.gz
    ├── 4f487059db73fa3b6782f850eac6be86b697c6a5.nq.gz
    ├── 4f6c051f14bfbba4e93211eb741aaa1a79d72ee9.nq.gz
    ├── 4fb2f9b70c99111540039087f55fbbe7b1403288.nq.gz
    ├── 4fee1c11d81824fc4715b63b100deb97844ff991.nq.gz
    ├── 511047aaed1a32ff3a77d650ee97cfef6515d9c3.nq.gz
    ├── 5184300fd1c3c2326245b9bc86ecbcfcb716d4b4.nq.gz
    ├── 51cf348ab31a7639aa501c9214b1a85ce3033812.nq.gz
    ├── 523f11a1ed7075f0ad4b1ceef4c0161406550e47.nq.gz
    ├── 52471a68efbc78597d9bec35555da5a0276fbfa7.nq.gz
    ├── 527128eb8b4a857b71a1cfe667bcf1c4b74bfa96.nq.gz
    ├── 52fda10994c155f51b3f26c566371d44a9ada87b.nq.gz
    ├── 532343ac32f77270cbffa296e9600986e945c579.nq.gz
    ├── 5328919bf04e865410c847dad6fb38c670b7d8b4.nq.gz
    ├── 53c134a532dbfb68b756c66061a00d13cb606330.nq.gz
    ├── 53d53c5a9bd47bc5c57be0a07b3a1a4c32af9c01.nq.gz
    ├── 547e53bfdcd4ee0de1928355f92f8ead643a0366.nq.gz
    ├── 5552a7cd373d5bbf9aa0949b0afb563c06d94958.nq.gz
    ├── 56715acca6c4ecb5c3bca8b28e6dba83fb039795.nq.gz
    ├── 567bbbdb9cdd0a3f33003930f3475930b6ddf74d.nq.gz
    ├── 56aa16c509e4d5d7c1f8473708be9333e7695783.nq.gz
    ├── 5767b14812a00f12fb49805ecd9208c0ffdc4df5.nq.gz
    ├── 57fdbc6b291849563e7f94443cd4f71c6725c08e.nq.gz
    ├── 5853160987d185f1f369f56d95583036ea3bc198.nq.gz
    ├── 587c0a7d446c71b8573c3c185fdd8176610adb88.nq.gz
    ├── 5ac28bc445ec2c2767be587f0d49bf1047df0745.nq.gz
    ├── 5bc1beb8ce9506d3fb7ff8f10a597968dd55cc36.nq.gz
    ├── 5caf94e11f1e594f5d4f8f934ef1530de7e26119.nq.gz
    ├── 5cd99bfa481a38a862c364fd32e3e6c4e2f9b3f5.nq.gz
    ├── 5d21caa23a15b68c9fb7182d2b7cd485c23405f6.nq.gz
    ├── 5d5b9e913b0a8dc2342c746500e8a12b1040af1d.nq.gz
    ├── 5d742efc1cdadbf44ad07ade97358ed840f4a072.nq.gz
    ├── 5d9de7f73e7cc22e3c75d8f580f91ae4f308d049.nq.gz
    ├── 5f7e99feb3fcf8fd16e890c0e8faa22da4c98a8c.nq.gz
    ├── 5fae68082eee03731a2e3daae3d3b39285023983.nq.gz
    ├── 5fe2947c746ed2f031102fb05a9dad3c4c4dc987.nq.gz
    ├── 601d4e2e65f264e55566f37a02af110e7a11ec68.nq.gz
    ├── 60bb17b02f717d6bc105c88c14c46e926b505338.nq.gz
    ├── 612568aaa5452cd82b1ac647b2b207d8f224e939.nq.gz
    ├── 61dd968e94d4654813e77badb3c13c32ae9d7bd2.nq.gz
    └── 61e67d03aa32e76999fb88aa8157ad71938eb9ad.nq.gz

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

[sanic-org/sanic](https://github.com/sanic-org/sanic)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
