# Repolex Knowledge Graph of Delgan/loguru

RDF knowledge graph data for [Delgan/loguru](https://github.com/Delgan/loguru), parsed by [repolex](https://repolex.ai).

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
rlex download Delgan/loguru
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bce5dfd3b435b1d1658507d7e095ad7a9919bf1c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bce5dfd3b435b1d1658507d7e095ad7a9919bf1c
│           └── chunk-001.nq.gz
└── blob
    ├── 004e63222505b4319a22042c7343204b6f8befae.nq.gz
    ├── 01bdcfbd39016c9036a3f64e7e89fce94edda5c6.nq.gz
    ├── 045ec216fd0ab3087e216c0f9b658ace25cdcf76.nq.gz
    ├── 060dbdbca196293734471675259d9270332d576d.nq.gz
    ├── 063c5615c99370d474c2c28fdb4bbdcbd0352979.nq.gz
    ├── 08681d74d9c157d10b5207bb1ec37161122ee24a.nq.gz
    ├── 09433b1878164d58f8d44d80015fd74c32ecc8d1.nq.gz
    ├── 096fc5e65cd56f7fb73537c97f1caf84624cebe3.nq.gz
    ├── 0a197fa0ac738a3ac116675e2ee4c28eb6927465.nq.gz
    ├── 0aada1bd1badb35da9083942680426ba08a174d3.nq.gz
    ├── 0d33231dcf683e8b3e15d498b75f89eb0e438c10.nq.gz
    ├── 0f2c4c65eca70954d0809ecdf6de9c64fff2282f.nq.gz
    ├── 0fee04998bda3cdad5ebb15b25bf9248c63208c0.nq.gz
    ├── 105e2a9eb6da4c7b1721b1f3898805807603b5ba.nq.gz
    ├── 10a96a4d6992028fc1018d0fc3d5697736f9f7df.nq.gz
    ├── 113429380ba9565ddf26f1503eab56eef4c0f23a.nq.gz
    ├── 11b2471e49fc0cfe7e8e65c8f2fb83ecc2377a61.nq.gz
    ├── 120bc4cf0d79e69f4b6140238d28351641414a00.nq.gz
    ├── 1320aefa6f8e5d5dfd81cddd1556a48c6014c4d6.nq.gz
    ├── 1374be9e3625dd160b9c895c018cae7cc50cd513.nq.gz
    ├── 15e0fea95b425d6076903e4c729b396928f7b9e5.nq.gz
    ├── 175f71d215fe4c44c1073659f70814ad1529c322.nq.gz
    ├── 17fdf8148da54ad3c60c598826cb93a0608a015c.nq.gz
    ├── 1a14ff9289e56362744227bb1212dd9d5bf898c4.nq.gz
    ├── 1a2e118c682c64fc47186659337683ad1a5d0638.nq.gz
    ├── 1a569255cc067cfdc526c3ed6d2967055a8196a8.nq.gz
    ├── 1acaffc303c17b5d1cd01d835b6644c6ed59b92d.nq.gz
    ├── 1af1fb7cdbf44cb1a16b00728dae5a3194ca1718.nq.gz
    ├── 1bcd82442630b3c6d4615ebf79b5f7d3f0ed9e8b.nq.gz
    ├── 1c7bd1ef5cade8542febcabc5b0398dcb145bfb2.nq.gz
    ├── 1eebefe67147abf43d1a2e484c5f244873888cec.nq.gz
    ├── 212b48d7c9faddbe24525a61b41acfbbbb614d7a.nq.gz
    ├── 22b8a593b609600178662a94ae4f328fc188ffc4.nq.gz
    ├── 2334254d381efd1d1e8b8f20d1d38bee30cbe36e.nq.gz
    ├── 2400a7f3fcdc05ec420dce6299c30ca0b3bfc0ea.nq.gz
    ├── 24eff63a341646e1c02ab304d20af8c95d78a786.nq.gz
    ├── 252d39d001ba2d5e6d628b16a1c17005dd740772.nq.gz
    ├── 259e085ddc8acc85e47b89d87b719124bba5ed65.nq.gz
    ├── 263b4d8b5af5e8b8d6a95bf4e6634f92ecf3655b.nq.gz
    ├── 27e4d7535a2f47a1159cbba75a11f3bd4485686f.nq.gz
    ├── 28630d49f22377cc0140922e236d190271ca23eb.nq.gz
    ├── 2900ae6507b0a927d51f819c3f23e5bc0598ef51.nq.gz
    ├── 2984409e030c76c4081f8c840f93fc86c8f1d037.nq.gz
    ├── 2a06aa2ed386c33de31869873947f04e7ebc1983.nq.gz
    ├── 2be6d84d161a772d2e47f9f3657a127c4d967ecd.nq.gz
    ├── 2c0e1f03ad1acb9abae58c6bb3123110bfcac5fe.nq.gz
    ├── 2c4cb7b27067737b40b3bc2f052af2ad642132f4.nq.gz
    ├── 2cad24b16e77acaa61485b87b1d9127e168c952b.nq.gz
    ├── 2d11a06b1272cc3b4ab3ae147dc66b5ab41ab62b.nq.gz
    ├── 2e052e489361060a123ee6e4d544d4488c918f6d.nq.gz
    ├── 2e8bbb292c702d25841d111ba7f9e13aca19c57d.nq.gz
    ├── 3163e55011e60e23bdfeed9a341c068486830f7a.nq.gz
    ├── 334abb8e8af8d3d380722b5d1517236c38bd2715.nq.gz
    ├── 335b4cd4577d50568e83f902d1568f0006333789.nq.gz
    ├── 3363c45c01da50f8ca1aac8ac5aadea02f531936.nq.gz
    ├── 3375401f16a6ea7af0caf694223b5efbe3ceaf90.nq.gz
    ├── 33821a7ab3d81c321d36f1ebfd2262940092c7a4.nq.gz
    ├── 339a41aedccbbb7110f31bbf0be5c094b0bb3d3e.nq.gz
    ├── 340d9eda48ffa913acf05482c8f42d201c6b3cb9.nq.gz
    ├── 36a887a51975ddb93d5323553064c722f97f0142.nq.gz
    ├── 37069bc18113ffa0171db02926d222297fa078ed.nq.gz
    ├── 374a52dcc6983b84252112cef2e5c21ecda3df98.nq.gz
    ├── 38f77ac65cd98f5101cdf6e364788c45991917db.nq.gz
    ├── 396cac6908a426e98397525734387069bd32da22.nq.gz
    ├── 3ae8f25b7c5ed7d82437c695cd658f34b0f9297f.nq.gz
    ├── 3af0bb321f9bc66407e0494f31ddf0a70c899121.nq.gz
    ├── 3ba5e12ab2ef19b58f33b898a9f0e6a577564dae.nq.gz
    ├── 3c4b346d812b8d3c91fb8bdd4e1d063289471491.nq.gz
    ├── 3d78e0cd9a7a84d661daddf0d7a9d5788d7f5bc4.nq.gz
    ├── 3d8f96511a9ca861b4ca42ee5d8ecdea3d958611.nq.gz
    ├── 3d941c0372ea8af986ac69486b9076343750c821.nq.gz
    ├── 3e86fd28efac911de5cc83e3ddd7d652f946aeec.nq.gz
    ├── 3fb2557888fd55a4d2cb9de186843deb2b3eb3cc.nq.gz
    ├── 3fe7a92d3e20eb1245e72d9c5449b34d18817986.nq.gz
    ├── 40ce2c91d73ccd0eea7c407ca9c5a93b2a7a4b2f.nq.gz
    ├── 43cc4efc2b83af70b21b1818b4ee6d29a9d9fdaf.nq.gz
    ├── 457bbf8c6a90fc33cf4259280c81598b6c6962ca.nq.gz
    ├── 476f85ae0e7ddf50aa551e99de106b36613e3445.nq.gz
    ├── 47f20e20480b37c8afb52e84694194421ab3de8e.nq.gz
    ├── 4884bc49ee6816525f6cfa703c3c90f3fa61b3d1.nq.gz
    ├── 49684a66878f09b12b196509f1e7a2e05b0034a2.nq.gz
    ├── 498070011106fb98d6e003f9551fc651a8bec879.nq.gz
    ├── 49ef7bdbc66b5c2d0039359e6765f5f74852486c.nq.gz
    ├── 4b6f8cae351605d55cee54be85019fc893816dae.nq.gz
    ├── 4c0b7ca24b8668ce62a8eb8644cceb39ba798d22.nq.gz
    ├── 4c7362abbaef548bc94026aff13e79aa2065acda.nq.gz
    ├── 4c8aaf14d23595cace191b72044aa218a9b01e85.nq.gz
    ├── 4cc60e5a7cef018a5437929587dbce1505846719.nq.gz
    ├── 4d3698c4b56c8ec15a5d3d716f1dd354b11c8f72.nq.gz
    ├── 4d616bb3eabc4368da7c6acb56707f9f63f9c74f.nq.gz
    ├── 5009a8443009802b28149fb606ac9923c04e13f8.nq.gz
    ├── 5031fd0e2e5959f4e0fc10c308b35e21f81b30f1.nq.gz
    ├── 5036329aebf60aa911e3cf51b952d4728caa19f2.nq.gz
    ├── 51666b6c7ffaaf5b2bea2db92ef2c107f3cecbc8.nq.gz
    ├── 522b82cc6bf3459f6997611e91a9818e4dc687ce.nq.gz
    ├── 5285f420ff222526f9afa7acf507362367132f9c.nq.gz
    ├── 5346668ed88f32c0985b2a8f4507d97a6fa962c3.nq.gz
    ├── 53c2cd6544ddf394c99675bb9779839edfa91100.nq.gz
    ├── 54706cee2f020d6e0e27d6bea34b950043ce2b0b.nq.gz
    ├── 547899466ffd6e77881dbde7c68f48ab4579a4d9.nq.gz
    ├── 56219c1b8d8ae09268dd3b59eb17fc3fd84e6a15.nq.gz
    ├── 5663ebf20facd5d1069a11f21efe3904695e5b33.nq.gz
    ├── 57c24841b980e36286dec92a3afc3668b4967bbc.nq.gz
    ├── 58768f9fe144f49fab298897f22950d9c5049c30.nq.gz
    ├── 58ac2ee8aa086868ac95f2f80b31f737ad44adba.nq.gz
    ├── 5ab7a7520290fe17640d57eef5ddb864eb17d4f6.nq.gz
    ├── 5abc4c7d9bb475280f892ba0a3d1c8cbe9f4c4f8.nq.gz
    ├── 5b22e69a649bbad29de2fe54db4bf2d0b5224ec4.nq.gz
    ├── 5bf1b41f6c21dbe9b6585a5450563b2ba5888ed7.nq.gz
    ├── 5cc8f06c2df212fae91f6a72c3a2b7d1e6db917a.nq.gz
    ├── 5d72ae381a24385e0492e22294355f314d7215dd.nq.gz
    ├── 5eae642fee596d8a6e94b39aba141eaaed032d39.nq.gz
    ├── 5fb8af39698b8db515fbbba8a7c44fdb2f38006c.nq.gz
    ├── 60d3544a5c03e638916345c3d8f7315f2dad9b0d.nq.gz
    ├── 61353df5d1e2a602dec2ab9ddcc1a72c97d7fa35.nq.gz
    ├── 62c58dc4a16e2bbdb4f8121c05e58f78548dbea2.nq.gz
    ├── 635d3a2341f1f507c15ac081cc114e91be1369f4.nq.gz
    ├── 64948b3cdc01f67442216e6010da792e50ae2a08.nq.gz
    ├── 67a661d1ad13debc2bf69fe9945998e8714031c4.nq.gz
    ├── 6832d0a4fcb91b998f8a771372ee629cb114f1ea.nq.gz
    ├── 68f28b836b33cfbd9266949aa4eb0724326cf4cc.nq.gz
    ├── 69cddfdeda9d5fac570e9b98a1640c921f1e5752.nq.gz
    ├── 6c0700a6709f80a344ec4ad7888d9ea04bd1c927.nq.gz
    ├── 6c48523ba85cebc97563282c5f7083d00bc5cac1.nq.gz
    ├── 6d78f31f51a2bbab29b810079e01ce5afb00c06f.nq.gz
    ├── 6db0cd9325370f24dc1127e5b7826f95895fe045.nq.gz
    ├── 6e0a64c260afdbd9b8b349bdba9d2c3e4856a4ee.nq.gz
    ├── 6f0211098f61f49bab559e7f8b9fe3390d4cb625.nq.gz
    ├── 6f45008f67249585eb122a922ef8112c242a15bc.nq.gz
    ├── 6fe5cafc0ab25b9137a6332688d8d83166b0cc3a.nq.gz
    ├── 70418401a87c79874e69ad22aa98cac49dd38228.nq.gz
    ├── 7131ffe732afe72e77775f7781c209c6ca2d2087.nq.gz
    ├── 72aba09de108485a5c8aa38d2a07ee7f76eaca99.nq.gz
    ├── 7321914389519befd18b288bcd62cce289009b56.nq.gz
    ├── 74137c1a173cac460b162fa26a2932f91484662f.nq.gz
    ├── 7560b1832e72fd6c032692adc89a6794870f07cf.nq.gz
    ├── 7578c6ff818d28d217ec56f91e13c5369af0cf63.nq.gz
    ├── 75c6b4268786ce09d71369617522d28bc0077f05.nq.gz
    ├── 777678539449add297a34dcdce01675f11a18703.nq.gz
    ├── 78a2e8811683888d113d41381b051810c0439c3a.nq.gz
    ├── 798cc6d3e2d65bcf3bbf5e861dc75ec83ee6e7f5.nq.gz
    ├── 7b3639bcf9aa0f277465971f010bbebee1acaadb.nq.gz
    ├── 7c0b0365a59aa4ed782d5f0fb0fbfbb60d55351b.nq.gz
    ├── 7cf4342e223927e3e011f60afa08b4e494c937af.nq.gz
    ├── 7cffe4d589e88e0261100803a9b101a965c45a0a.nq.gz
    ├── 7fc007563a9641021f19c6cf366b851cfb8c2ba3.nq.gz
    ├── 81cd6cfb4a82bc035b777c57d031e3e72c0c44f1.nq.gz
    ├── 83ae30a40fc05a5a3f2c496b78e7a3b998e3db82.nq.gz
    ├── 8548f375cd648770211616bf6100a4bfe17065b1.nq.gz
    ├── 866cdfb725207d74a10726cf639eaebea6acfacc.nq.gz
    ├── 870cb992d343d1b298f9b41843242b884ea242bc.nq.gz
    ├── 884e78cff0994ca1f9f39e1bf92bed76fdc8058e.nq.gz
    ├── 896b9222e052cd7e166c26fb1aaa1f6a1651ca91.nq.gz
    ├── 8990523113c575d26806e436ed8ad70f9f7cf1a7.nq.gz
    ├── 8a95db92e20d3cbc44705e44ec7d4dc5653f12cd.nq.gz
    ├── 8ff0a28685d9ff6fe9f85b9c2c8bb67b2e496f85.nq.gz
    ├── 901e59c32e598bab14ff12e46f5368dc67fa4432.nq.gz
    ├── 912db9625ae51b13740fd156d3777ec1b7e97a5f.nq.gz
    ├── 915a4a8c8fe4dcb406b7587f72ee1d3714dffca8.nq.gz
    ├── 917180a327e5f26ce406e40e4b1dfae33f2141e4.nq.gz
    ├── 91e3f300b10fc065fbde5dec9c81ee1dbb3d2ef9.nq.gz
    ├── 91eac718b1abe5feac61d87f03e38021a5a411be.nq.gz
    ├── 91efffe963bda9f3bb3fb11847ddd9bb8c712736.nq.gz
    ├── 91f29c024aa40015781ade5d2aaad5a8fd616d9c.nq.gz
    ├── 92d32b196d9ee3742cc7d532759983224e999b21.nq.gz
    ├── 92fa9d9ff7aac2ed5369fc0a237745dc4d9f84d1.nq.gz
    ├── 9468822a9961229cd7e7f7eaf4ec3264f1ce7334.nq.gz
    ├── 95036aebd051eebaab4be41fc43cc0f6c6983cb5.nq.gz
    ├── 96470830a6fa7d6dada55a914064d6e3fac35e63.nq.gz
    ├── 966cdead9d66ea4469b004aeefba8cad4e07738e.nq.gz
    ├── 9684543c3403b45c581c441c3aab1f804162e5cc.nq.gz
    ├── 96d8a3c83778f75030e3ac7d71ad32bbb060006e.nq.gz
    ├── 972b13c1d1b804f8211beca7395104a0665d137e.nq.gz
    ├── 97415415e84fbe62f2202cbc2af6892b857e48ac.nq.gz
    ├── 97a60b3cf9a892b261da39129d9795e3b441f6ad.nq.gz
    ├── 9820464af136404f47e2bb60022b01852fb113d9.nq.gz
    ├── 989e0d9a94dab1f12655f4c12fa616ac0426617d.nq.gz
    ├── 98b603dcb07c0a18ad04a3edf330e907a90f8251.nq.gz
    ├── 9a2a02156cd606bb91de9f8cf3e4945101bc3ac6.nq.gz
    ├── 9a5dd1cf3367a2b9d8b30c5c8cc37722af0292b6.nq.gz
    ├── 9ba7580d614f54cb54166416be9aacdca20b24fc.nq.gz
    ├── 9df9c545a655626dc7ea3e8a8dc39cf28247dc2e.nq.gz
    ├── 9e0b20b2397081c9ac8f266d153053b872b1040e.nq.gz
    ├── 9ebf86fafd2536cdaed3f0d98c1b95b9827498c3.nq.gz
    ├── 9f63d3dbac32fdf3ce96407bea096d13a5790bdf.nq.gz
    ├── 9fa0c8726e83bad6c4a90e4afbd92c5941c0612a.nq.gz
    ├── 9fea642b6b07b06f95d5b6c2649beb3169ac0a84.nq.gz
    ├── a1188137824d670594ae1dcec0b820e77632506a.nq.gz
    ├── a192b264e5ef40b0a0db73a1a98d2085d3d6b591.nq.gz
    ├── a3ba16e46f3ad5a6628f4091c54b35fe13847aac.nq.gz
    ├── a53221cfa0d27197fd74fdc234509f853d48cca7.nq.gz
    ├── a58470b92e9dba2c29640e69acb4f9e34c6acde9.nq.gz
    ├── a5e345a8bcfd44cd5db2611f8eecd1cc58890b8f.nq.gz
    ├── a705c02fecb40b663a1a5d4b5b387180407c0f21.nq.gz
    ├── a89a3a4dc7de081b5ed6fd9d087b4410d24f17ac.nq.gz
    ├── a8e6bcc75a67bfc3c4f7b2385e91c2baabb0b930.nq.gz
    ├── a965a70ed4edf261c693c1467610cc44af853c53.nq.gz
    └── aa99c76c1d29f935d9aeb09191905ae45591b8ee.nq.gz

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

[Delgan/loguru](https://github.com/Delgan/loguru)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
