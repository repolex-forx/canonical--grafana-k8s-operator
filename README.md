# Repolex Knowledge Graph of canonical/grafana-k8s-operator

RDF knowledge graph data for [canonical/grafana-k8s-operator](https://github.com/canonical/grafana-k8s-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/grafana-k8s-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4a94c6df122302aa0375e75a0ea414f508ade3c6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4a94c6df122302aa0375e75a0ea414f508ade3c6
│           └── chunk-001.nq.gz
├── blob
│   ├── 000d0e05125f0261275fccbe9289e905e1218023.nq.gz
│   ├── 00a02f6550ab3884d004a451230036df6dd8a8bc.nq.gz
│   ├── 01512eef50a4d63e4ba86ee935a7a443285e1e9b.nq.gz
│   ├── 073fb35de07166b63f6d044f4dee6139f0cc089a.nq.gz
│   ├── 08444f81c3bc866709fef8190ff4d8d7b23483d9.nq.gz
│   ├── 08512ee4ef52d4a5d5d1cb187501c7c18458cc89.nq.gz
│   ├── 0bf6589cbe253cb80c2aae7664639e480d3c3056.nq.gz
│   ├── 0d4d23dc6c947414835940400e04214291190969.nq.gz
│   ├── 14cd592e0466bfdd79dcf2003f3bf9310308a98a.nq.gz
│   ├── 1527248b125dabe30867ea3750b2a727c6797536.nq.gz
│   ├── 169da982099be9a6f21e3603ff134913b68e2fb6.nq.gz
│   ├── 16b90088e60f2af0a8aaeb8621b31ade3025be9a.nq.gz
│   ├── 18070eb696bfacfae6088224c341d64b35adc130.nq.gz
│   ├── 18a10cef396dc1eaecde3c2175308031e8e21b7a.nq.gz
│   ├── 19d337e0dc6593cadad94f8db7df333d5dad1e50.nq.gz
│   ├── 1a5f0e77f4c103012fb323e34faeae62c1132c58.nq.gz
│   ├── 1bb45e9085b56696c3b53307f0da6268b4b3d16a.nq.gz
│   ├── 1e6510088a56bbc2b980595eedfd6706c8dbe847.nq.gz
│   ├── 2046b982e1a97c247884ed0d6a917b36f774f174.nq.gz
│   ├── 219793a0aa948e6766e7ef5ea130682b05755c83.nq.gz
│   ├── 249b49b942b9d88c958451f257550b75d154e8d8.nq.gz
│   ├── 265973df80bf1475f32f1a4afab5789627b2d89d.nq.gz
│   ├── 266e39a30e738c96822bd0bc69ba487d766140b9.nq.gz
│   ├── 26b21e2e0f54a04455791b19591d8e06bf5853b8.nq.gz
│   ├── 2ad84eebbd3188fa28bb7f2379b78ce1a0a1933f.nq.gz
│   ├── 32fafc7a5f03ef3ca1517d72c9312bf03adfd979.nq.gz
│   ├── 3328ec7ecfdeaba87d6becc8b5d32dbbff82ddb8.nq.gz
│   ├── 3430e146c7a417780b0eb3f16a9feab7bbd063fc.nq.gz
│   ├── 34afc21da97437f51dae90ac27d7cb1c3dadb61f.nq.gz
│   ├── 3544a1d3146e0e12716782edb6e30734d8d35b30.nq.gz
│   ├── 387ac6a47738bcce3f686ea6d43178ab2197e414.nq.gz
│   ├── 3978a7f7816cd2428002a92028ef6e6cc997a7bb.nq.gz
│   ├── 3b9f97d9322896836db35da8115c76c933b5d075.nq.gz
│   ├── 3f70c4536a766d2acdfe9901d845f7da8526b843.nq.gz
│   ├── 3fb1b683d34553f8c93d95392d6700a804c219da.nq.gz
│   ├── 46d95eb817cb987b46d568772073bc92d271f9e1.nq.gz
│   ├── 47f0965f58c9dbc933bd76144e12f4bcdce22469.nq.gz
│   ├── 49f99e01b7650c77fba0afba930f8fa0e2aaa8cf.nq.gz
│   ├── 4afbc359c9f94e787571102948544febb952102e.nq.gz
│   ├── 4b24c0a34c832d53ebec38676a906776634008d6.nq.gz
│   ├── 4c16fa4b6b7e97f4b3ac783ecbfbbf7ecaaee6de.nq.gz
│   ├── 4ef9d2d199747aa5ec272a592e20436adfcd39f5.nq.gz
│   ├── 56422e753c08340de9ca5f5ce67d228992767ca7.nq.gz
│   ├── 5b0f7f2f18278d6cfde9d236fa7c6fcb322d89c8.nq.gz
│   ├── 5e07505478d4294ad0b2dd0f72c78c43b8914e9e.nq.gz
│   ├── 5ecd9b9ae57ec1f60b9333bc1a333508eeca5ab7.nq.gz
│   ├── 5f3b615ae0de34a9c0292f81be882c37cf8de71e.nq.gz
│   ├── 6162695c03a5084d37d528dc6db85b264639c570.nq.gz
│   ├── 632c382b2df8e80a3b52e0042201cda1b9ecc0b7.nq.gz
│   ├── 6529018230d905782e567630986cf15c86cf441b.nq.gz
│   ├── 652c7d218edf2dc1dcf39f46f745b352c2172801.nq.gz
│   ├── 65622db63e14ad878169ce926770a93c6ff7ea72.nq.gz
│   ├── 66c7074e793635fd49917b5e051113447af330b3.nq.gz
│   ├── 67ed786af9583b52e64b93eef0c58054dcce91a6.nq.gz
│   ├── 681bc6cd9e5a02289508470e23c391f333a42c2f.nq.gz
│   ├── 6a65c2d04a864f2e02fcdaaada42035ed987686f.nq.gz
│   ├── 6bda8c4b222cb68dae7ac5979c38f34d9cdf6db0.nq.gz
│   ├── 6c2877d302fd96ffda4e14ca7137dc7db51b7c63.nq.gz
│   ├── 6f94cded4fec60283aa42d48789f2f779e32bb9a.nq.gz
│   ├── 712cf30e3cae020ac3a68858b8021848cdca67da.nq.gz
│   ├── 75116120b69fb28ef4f609490067e5a555571475.nq.gz
│   ├── 78986612646c670aa0d5c3a4e690af8e54a511e0.nq.gz
│   ├── 79557393bd4c8ddbf306d87275dcc620b269ddf5.nq.gz
│   ├── 7a43c0f42fcf1514f592942227938a5907529761.nq.gz
│   ├── 7a4a3ea2424c09fbe48d455aed1eaa94d9124835.nq.gz
│   ├── 7e38b4ea2d557f525e5fae8516bdd12e11c18a0f.nq.gz
│   ├── 80279fff03a044542a19f87b118268d1fdd7209a.nq.gz
│   ├── 85bff2f0a5bcf44d361d90f38ab873b9b20e1fa3.nq.gz
│   ├── 8648677a130da4008f8f5da28f915098cab8b0c0.nq.gz
│   ├── 86a6551abcb8da5b600e8c67888c91d994937a61.nq.gz
│   ├── 888c85583f72dc67ed997c9868566452e70cf898.nq.gz
│   ├── 88ff1492be46a0699eeca8676d36750066c2ac8c.nq.gz
│   ├── 8a256792f51df2994dea56312dc8f7474c366983.nq.gz
│   ├── 8a49c45453a41dad4e52d7bd2d22f852fbba40b2.nq.gz
│   ├── 8c554ae04b905a644e17797ce1c676f55de710b1.nq.gz
│   ├── 901f14351bdce339c3fcc6c3b3112c94e4fecb2f.nq.gz
│   ├── 905ced0e68b39faac34954c2ab61fd2f3ddd29b6.nq.gz
│   ├── 90f86bf93192cb7d3c1da017b9043a57d8ce279a.nq.gz
│   ├── 970bde4eeb5fff81c96294f187f638526e0fc79e.nq.gz
│   ├── 98a4261f7a7824e9045e1b19c1bea7b0227ece9b.nq.gz
│   ├── 9a62a2e686b1e3e0069fb968fa424511561f7acf.nq.gz
│   ├── 9a839dfa65a77ad33e370898d1d1ceffb5581b47.nq.gz
│   ├── 9b8fbb44d5ec6429d71f67ad6232c35c72954172.nq.gz
│   ├── 9c2a78df1855236691dffafb9cae1f422d0fe93a.nq.gz
│   ├── a65b41774ad52b3cc7b60496d35eaafc5da4bb16.nq.gz
│   ├── a8c23c32ae7d8a5063df25fce3d70f4bebf3eb09.nq.gz
│   ├── ad54ea45083f3e014d6073c4e66f2689e1bdbfa6.nq.gz
│   ├── ad60b546623c02340f4e7eb19bf83031a47b2ea1.nq.gz
│   ├── ad9ce827bdc5285a8a48bfd5fed1a71cad82ca25.nq.gz
│   ├── add877ba39ca6df007f45cd4865cd0bdde4183f0.nq.gz
│   ├── aed260f9838d5b0dddd181ba994f2ef272750df8.nq.gz
│   ├── afbb3138e14b8ede66fe54d25ba762c3651f2698.nq.gz
│   ├── aff29f890a081dacb874528f6aa2e9edde9c581c.nq.gz
│   ├── b05c65425cb4a9030c95ebbb3f5dce12c3a5a4a5.nq.gz
│   ├── b2348b9fbfdc4eb154566c80f844510446be1d02.nq.gz
│   ├── b35cdd6950fa058752ce4f2c831f07598723c389.nq.gz
│   ├── b9ead78ea839c7ffe24f6b05976796dd5858c19e.nq.gz
│   ├── bab369510233369152c1bd556ca8ca4a3b38aab7.nq.gz
│   ├── c102a8cd59c8841e9587509ddf3758dc825b988d.nq.gz
│   ├── c56c9cb021bc2cf6a0a1eb27d3fc7863d9f367e4.nq.gz
│   ├── c7f7558b7f5cda06804923010dcde901538ba656.nq.gz
│   ├── cb342e7e35a534886b3808368838fcf09c859250.nq.gz
│   ├── cccecf625cea561e53def7b5e93fec5afde68f1b.nq.gz
│   ├── cda816b063fd97d28a5246050876fccddc2d9acf.nq.gz
│   ├── cf4f12c4a564f49dd2ed334b2f360720b92b2e5d.nq.gz
│   ├── d25729588b7ddd229cb0756c0b098ea3709a7a6e.nq.gz
│   ├── d408d464d637f17efe8724e3f36cfeebbb07da43.nq.gz
│   ├── d4c0e5516b298439b7c5a6ba4b8747bf4299c338.nq.gz
│   ├── d5bd23d7c592934adbe356e37f9a8283da844dd9.nq.gz
│   ├── dda5f94f4774b0d55511170f893b41bfae55393c.nq.gz
│   ├── de535d0f97c5fd103dfccb173b400b7e71461bd6.nq.gz
│   ├── de6e6ae556dd4803f92154b812ab87f2fee79d19.nq.gz
│   ├── e0dcac5a0ab35eac2146a38794a570f8ff5b54a9.nq.gz
│   ├── e0e688b574dbd35b8222a56cb16ee947ca10a72d.nq.gz
│   ├── e2aaf0bf17f6d978d4b4302ccacf01e7413c00f1.nq.gz
│   ├── e362fed29552f003a4e880fc98fb5180c8c0abe7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9dcc570fed2df31932da1298d9838e2beabdebf.nq.gz
│   ├── ed1aa815b902e23e946cbb376773de328676cdbc.nq.gz
│   ├── f30a4b64556df5d4d075cd1a9eca84c5aefbb5ea.nq.gz
│   ├── f35143eb2ace2ec8c395b78e06459ca40e03caad.nq.gz
│   ├── f4a65fdd7c0714cb6e6d8696295f9c0110a5e870.nq.gz
│   ├── f4aa9e929f7e6bdca6242a2545014480968600ec.nq.gz
│   ├── f59ffe9dc91c48fc14674fb5d9bef26378410a4c.nq.gz
│   ├── f93b8632edcddcb5e23f05b83117b0b4d9d3e924.nq.gz
│   ├── fd2f972b27d2bda00a358150ce5046123484fce9.nq.gz
│   └── fe04b8196876f6a2dc8b101bff232270c603f40d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4a94c6df122302aa0375e75a0ea414f508ade3c6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 135 files
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

[canonical/grafana-k8s-operator](https://github.com/canonical/grafana-k8s-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
