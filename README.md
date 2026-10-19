# Repolex Knowledge Graph of scrapinghub/shub

RDF knowledge graph data for [scrapinghub/shub](https://github.com/scrapinghub/shub), parsed by [repolex](https://repolex.ai).

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
rlex download scrapinghub/shub
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4facd31c84dfc1ef78fac43710a592a87753fcc5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4facd31c84dfc1ef78fac43710a592a87753fcc5
│           └── chunk-001.nq.gz
├── blob
│   ├── 0203668fe2a29d3719aba150aac3f9cc6f74de15.nq.gz
│   ├── 0315c7a629902f6970508124ab6d32299a215fb0.nq.gz
│   ├── 084aa6e218b7664120d74d4254ee437af61e63be.nq.gz
│   ├── 0bb3c2f695c982aa1856de2f86f4593240c13767.nq.gz
│   ├── 0ec0686ca1748e7b3af3210e934b5e8ee5cfc3b9.nq.gz
│   ├── 0efef16022c22e080c0ca83334f62885d0d19af5.nq.gz
│   ├── 0f09058cb42ec7abddf37b738e0d88a5c8aef611.nq.gz
│   ├── 105facd5750b0fee0fe0d884815ef5a8a75c3c6b.nq.gz
│   ├── 121627a35203ea792e603fbc65e6fd8f5ac3ff93.nq.gz
│   ├── 1271e81dcf09a121121835479c34eef134afaaa2.nq.gz
│   ├── 1a4ae3fc932acd993048ff074e0cf018b579043d.nq.gz
│   ├── 1a64efbb0b3206c82ff487dec207b99d14aeb290.nq.gz
│   ├── 1a909d050cf0a388f20a3e5354c688c9b2ace9dc.nq.gz
│   ├── 1dc089fcf5c04dc675b92d85cfbc68491a49277c.nq.gz
│   ├── 1e83d6d3059d4ea28388caf7fcde4adc3b7cb82b.nq.gz
│   ├── 22b966095d4d4c8f908dfb700b90467028d859f5.nq.gz
│   ├── 246cb5726d840e116f866efe20ce1fd7e8941db5.nq.gz
│   ├── 27689529e6224cbcbd97effe5ffbdb160bd2d053.nq.gz
│   ├── 27daa9b0546259582acc2af75aacf97cf27d4758.nq.gz
│   ├── 28c2476bdb640830f3868d4ee2ccd73bfeeb23fa.nq.gz
│   ├── 29dd1bc659837f5d92a1bfed5e8035e503de91ab.nq.gz
│   ├── 2a1ba7eb0ca0f7c1bbdb3cda86a1d83a57f2c15f.nq.gz
│   ├── 2f74c2b87fb7c95f59d1f9896cd80f0c21ad3dd2.nq.gz
│   ├── 353e2183c12e8484da35f42c1c673d6b29e5790d.nq.gz
│   ├── 358977a013ff162c830063362a59ab1d257cc10a.nq.gz
│   ├── 35e1b67dfa4a516771a5b0969faf70ebc1dc1890.nq.gz
│   ├── 3813a1f58fe2c539e96730e8d2b2f2ff754bdb6f.nq.gz
│   ├── 391c25edd559a464477e86db7b33d7055e9b5a9c.nq.gz
│   ├── 3af6cd2ec2532fee22bc8b949a1005168b4a3d3d.nq.gz
│   ├── 41ef1ef087feba087d95e87564b2ed009565d4ef.nq.gz
│   ├── 421481bf7c555c71bdf464ff74694eaf7d14b79a.nq.gz
│   ├── 4275bfeeb7b2c0010670e9fdbe8970c5338a6c98.nq.gz
│   ├── 48d21909d03864b6f04026557648a0d8151b1891.nq.gz
│   ├── 4db2832c2deaabd8f3002de47d23f746ca80df63.nq.gz
│   ├── 51e85ce31d072a8e27a775b744fcf6c6173f910b.nq.gz
│   ├── 5531e8e665787430c41b8c6212c363e6aeec48e8.nq.gz
│   ├── 561f91cf1b748ec7658b70df68600b7b095c0db6.nq.gz
│   ├── 57911be53a3707a467b69c3aa98daec8baa5d3bc.nq.gz
│   ├── 57ff52a0fd5ad1db60d28556dce259a0e6f491c7.nq.gz
│   ├── 5c39fed2242507978db20e4799c559c2b15979d2.nq.gz
│   ├── 5e0f47d65f048631f051110ce3ba1007525936ac.nq.gz
│   ├── 609c0eb772f12f8ea576333e0f53548a73d8c9c5.nq.gz
│   ├── 61e20bb7a1f4e64fc56c20aec98dfc67d75e69d3.nq.gz
│   ├── 638fc4d30f3b2b3e1208023398eafc1d1a7862fa.nq.gz
│   ├── 640bd899b07874815265d5e5b904e807cf4f0e4a.nq.gz
│   ├── 6a924a5df9b25dcf42a3d001e855918571740610.nq.gz
│   ├── 6b4600c4508d3d99184bc857d4a5e5e3b895e99b.nq.gz
│   ├── 6cf68e9749588f8d364241266d3e79e7ec83c134.nq.gz
│   ├── 6d1aeb5078edd823bfa584ef6776ec50a467ef79.nq.gz
│   ├── 6f44f92ba2f313eb7fa196c5fd8a5baf23a315a6.nq.gz
│   ├── 75728bb7530722370da27c683968a474c594ef3f.nq.gz
│   ├── 7737f215c90f56a5847a27ab9895d61581132663.nq.gz
│   ├── 7c37ec757f26ba12f5cbe7801ea366037bd8223a.nq.gz
│   ├── 7f28a81c4a1601dca957050255ae9f7cc40d62ca.nq.gz
│   ├── 80cab3ffd196b4b83a879890f9c3dce24d72f357.nq.gz
│   ├── 810d5033492f30059811ecad9a692b1705e3d497.nq.gz
│   ├── 827102cde3176eaaae3c9d6366efcdde93896a62.nq.gz
│   ├── 840cb293b17e18c4301421937a7e546c93d328bd.nq.gz
│   ├── 8544131d83da9d6e66b394b8ffea27d6dbff2621.nq.gz
│   ├── 8b14f231765353371b5a4c2afb03d4f09e06978d.nq.gz
│   ├── 8b54b96a862539ec735a2f43bbcc94d0576e03fc.nq.gz
│   ├── 8ed83007372cc118809a0ca0bf20e76bc6995e29.nq.gz
│   ├── 8f5179b010a1702504dd5d1dceebec32bd427902.nq.gz
│   ├── 95d3815b6d50d40e2b413849acf8df726ef0f47e.nq.gz
│   ├── 95ebe0efa42b02cbbd2a9ffd8536b025f0c2c225.nq.gz
│   ├── a47a007c63fa1e42b89b2592d02d6c634c71e34d.nq.gz
│   ├── a5c03b9da9dc26f46ac6613461378664eb378ab3.nq.gz
│   ├── af41ebcd5563a011ae571688585daf85b02dd0ef.nq.gz
│   ├── af68e23157024bf9cfeff4062df0a7725917b460.nq.gz
│   ├── b04e4635a56ae0a54988a5d2cfbae5f545ae22a6.nq.gz
│   ├── b4338eafcfca281f7a02372da4b3a58ae1c619b7.nq.gz
│   ├── b4b5122db7fdf3e6efbb6c1272bea388b39bb0cf.nq.gz
│   ├── b62d5b3edb2c4c816e17286de1cf1b27ca269d41.nq.gz
│   ├── b761165e56317fb5de0506e76591a91f1a7faef2.nq.gz
│   ├── b9995a5fa360e2ca835803c2b1a9168d14011254.nq.gz
│   ├── ba65b13af5ea2386f0e5a279f93bd5064181b7ed.nq.gz
│   ├── ba994dbe31253df8e962f1387d4516b477ad60d3.nq.gz
│   ├── baf62eae2b782f1fa66b51eafe1b4630c64e912d.nq.gz
│   ├── c548058f31e193bfec2142ba3c1122a118e1c012.nq.gz
│   ├── ca341cdc76f9c748aec7e07a07fb9c63bc0a4cfe.nq.gz
│   ├── ce3d40f5b28d01c22e0edb25ed9bb41b508928ad.nq.gz
│   ├── ce7af540a4960aed95db4833034eecf4c94d2117.nq.gz
│   ├── d1979e66a85111bed646b1b3107492660d3ff0e6.nq.gz
│   ├── d282b9a4b1df64bf8b02e83104de8c1ae1eeebc2.nq.gz
│   ├── d3082cd9c5460eca9c6e2077ff1f050676619ee6.nq.gz
│   ├── d36e77686ee4d16dd605ee2263530f3e4403b300.nq.gz
│   ├── d5bf4d4b376f754b108a0f23a1af4a9d21aff465.nq.gz
│   ├── d79bf544c53ab77bae8f0880bd881aac0ec8635d.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── dc6e4e2f15dd8283ef823b64bef9f9ae681fc3fd.nq.gz
│   ├── ddab7ebcf4adcf24ea107938a44332c5a5379d9f.nq.gz
│   ├── e1be9a854b18982bf3c1f71b78a2c7ba8cae27bf.nq.gz
│   ├── e372bfbb25d3aa9a2c6f3e9a01fffcaf406be9b4.nq.gz
│   ├── e439a139551295bb2645f1fe01671a68264708e7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eba14e28eda6e38e786cd58c0d1728a08049eba0.nq.gz
│   ├── ed11d6a95774d37f2b8db3f8a3b194636e85685e.nq.gz
│   ├── f08b1e121577325ee68df475749c1b108ef8d9c0.nq.gz
│   ├── f3944f29a05f56da10586365e9d03bf7bc7e54db.nq.gz
│   ├── f52438dd6f5d7f6989f5cf448681e6933b6aa041.nq.gz
│   ├── f54608234f02d2132b0a32f29831438860cf5a0b.nq.gz
│   ├── f616c5dbb5fc578ff198a62bcde520a42cb378f4.nq.gz
│   ├── f65a8161d32c60bb67c5ce19850c9763464b187f.nq.gz
│   ├── f8de8034f76fd498f25a3f628c035351e0353de0.nq.gz
│   ├── fa066dc69cbcbaf00811990f302d23cf68609007.nq.gz
│   ├── fa7adfacca2ed23f69da9af2da44c5767c271fc4.nq.gz
│   ├── fdae538c1d2041625fad5c70d382c66616cd1023.nq.gz
│   └── ff232e9c8c885e4a9ae3ea47afe2d9859a12bd6f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4facd31c84dfc1ef78fac43710a592a87753fcc5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 116 files
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

[scrapinghub/shub](https://github.com/scrapinghub/shub)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
