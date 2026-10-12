# Repolex Knowledge Graph of ipython/ipykernel

RDF knowledge graph data for [ipython/ipykernel](https://github.com/ipython/ipykernel), parsed by [repolex](https://repolex.ai).

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
rlex download ipython/ipykernel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a2b7a3ebbbb77faa710663b49a427704bc00a257
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a2b7a3ebbbb77faa710663b49a427704bc00a257
│           └── chunk-001.nq.gz
├── blob
│   ├── 008f1fd6bafd2b0a3f84667e17be9d2463add551.nq.gz
│   ├── 0739d4b1ae506c88ca00fd5986071fc703cba446.nq.gz
│   ├── 09275494611f0e738951f38d3e4714a8aa49afbf.nq.gz
│   ├── 0951cdd22cfd964937e87c20f84010e99f4ba4ec.nq.gz
│   ├── 09d10666160831d52075d537efe9fe67cc27e304.nq.gz
│   ├── 10d31f939e5c56b9659ad963c710381c9871fa29.nq.gz
│   ├── 127f9502d3772d0e8d6b9501b7550a5d27abe6d8.nq.gz
│   ├── 16d572083a84b034ba01e616b6ddf432bc637aa2.nq.gz
│   ├── 1902acdc1232777197adc530d4624a440c844e18.nq.gz
│   ├── 1c36022e1d4915da633caf76468dbeeb5d0aa91d.nq.gz
│   ├── 1e8034bbb7e0b0cfb30292a2fe2d55b44f08bda2.nq.gz
│   ├── 217680a4fa8239c0f40aa5b5d1ce659a845909f0.nq.gz
│   ├── 21a58acdb8c191b0af0cd0b164939b0ab353b6f8.nq.gz
│   ├── 21d6d9962e5ae65c71a807f07d440fffe9d94b5b.nq.gz
│   ├── 221a0c4733ce325140502318118b9a2a60d827dd.nq.gz
│   ├── 24d62e7ad5367bb6e028100a2d67a357bf6aa316.nq.gz
│   ├── 254642109b3ad9089f7b636c3fba3158f97c2541.nq.gz
│   ├── 25befba350c976c4eead9997372a7e19aaf80f84.nq.gz
│   ├── 283ba9175edd1dc4f95b88734c1f2da5d5c05bd7.nq.gz
│   ├── 2a2866cb5361ced3440fcb756556b890a7f5f620.nq.gz
│   ├── 2c5b21ea984ade66449fb2b23fc1addac46fa0ec.nq.gz
│   ├── 2c6b95372f35d7a1cf611c45d942ab2336f20093.nq.gz
│   ├── 3370c6c36ecec36a999bce45c8ca0d9607fdd1de.nq.gz
│   ├── 34ebeeb802a79453ff5a8000e176d050991ad593.nq.gz
│   ├── 35d3a694d892570a4d8900b17e751a59365e8e57.nq.gz
│   ├── 3976acb1c9b13a31f75ce188cecd1f38c48f27d0.nq.gz
│   ├── 3a13b57d8ebdd1dd1d820dd5ae0186f6d3a5e3ed.nq.gz
│   ├── 3a3f92c37344c610d7836e7c546e0d2f1ffae588.nq.gz
│   ├── 3afc6b8e66b10900847697222fa8b5a068ee2de5.nq.gz
│   ├── 3b80e9a80145071fa109be3d432d6de9dda320dd.nq.gz
│   ├── 3c29919909772b898abf1fcb7360613ed20ad5fe.nq.gz
│   ├── 3f0de81f4e17a79012d1479adb177c6c26d676dd.nq.gz
│   ├── 467b07b265bd7c9ddd575a2ce7178c62a35d6f83.nq.gz
│   ├── 48addb7e420e0b4f67ef31bc7e70deb016ef7602.nq.gz
│   ├── 497027d91cae3a3be86ba31384f815dda3e1b200.nq.gz
│   ├── 4ba0d5b6a9787b28f5e8dfe333f076158393272d.nq.gz
│   ├── 4c01c5bcbc9cc15f89da93c120058b9b48313f13.nq.gz
│   ├── 4c4b1fd1e5ff177125e35a3e49f2091ce9ee5ea0.nq.gz
│   ├── 5078f8ace8b82e78db8c728d7c21efae4bd7b811.nq.gz
│   ├── 5109a31ea0bbd36ac565c4867be42ae75d349bc9.nq.gz
│   ├── 519076d6452a644d0a1a9cfe8c037f4805291908.nq.gz
│   ├── 54df0bbac6c282f569b76720ac914becbc303338.nq.gz
│   ├── 57e975c0fb6e7355e1a0e710f1d3da35e4977291.nq.gz
│   ├── 59c86440551965322ff15f99e8e5b6affffd2498.nq.gz
│   ├── 5e40d716580d72a2b42e7547bd8c0428cbeeff93.nq.gz
│   ├── 608c4e4264df65f9f9aa9e765efd452c1396ed39.nq.gz
│   ├── 613cf2ef4768f962171c617e56e596ca55ff3ae4.nq.gz
│   ├── 687b590958d71da5ce17b932a9de954850b5d639.nq.gz
│   ├── 69965ca7182df22e930ec627bfe581cc6ca8c22a.nq.gz
│   ├── 6d32bae884c326f57c0f21f81d15a515979cb326.nq.gz
│   ├── 6dcfaec35dc29dca91549fbbbb98ce6d1069cf44.nq.gz
│   ├── 6e373ccff0fd7303af7dd138612b33f80ab5fc2c.nq.gz
│   ├── 6ee6e66c818b29ca4ec1975bf59cd5b6a9269ba4.nq.gz
│   ├── 6f3b6d1666e6e73f5bf02e5eeba247c2c4b1ae3b.nq.gz
│   ├── 716c9e8f50a9bab57356cd0e15d9130e65122b62.nq.gz
│   ├── 71b387fab3b5bfde4cac7f3a35741c40bd7bdbcf.nq.gz
│   ├── 72585ef739a5b873f4a941e480913d7b29f6c985.nq.gz
│   ├── 7b5fd5195279520ab332e05214570d5eaae6a4c1.nq.gz
│   ├── 85d1f2db38752bde8404017f88c02d50940f12e8.nq.gz
│   ├── 86861d58fe600a3517715be7f510718bffb3cc4c.nq.gz
│   ├── 91b5b49428eb379f81705c873d9b74a97d215917.nq.gz
│   ├── 941e8d12be49b92b6ca5058b79c216f8a7ef7e71.nq.gz
│   ├── 95927aa3805f6471986578fdadb820d1f6199172.nq.gz
│   ├── a2d529ed01efad45251f1f689bc57bcd56de141c.nq.gz
│   ├── a2f6cc29eaec942a626274e8d1ed941d6751f241.nq.gz
│   ├── a95d6338d746ec8f4c9f49e65374017bcf34a648.nq.gz
│   ├── ab7006161dcf957188e091a21c68259abfdc5975.nq.gz
│   ├── abc8af673dd62c9e72b8bafffb1a0121d81ce4dc.nq.gz
│   ├── aca6aacedb65894621103995523cbef9b79e970e.nq.gz
│   ├── aed0ac0e971003721408d05b24fc75f7e79365c5.nq.gz
│   ├── b1069891024c14f6b5186d7f25ee8d6c36a192ad.nq.gz
│   ├── b1791c15acad7128d31a0c987971bef9f0fadfc2.nq.gz
│   ├── b36fcc3124f39aa4da8b0c4112133187acca29ae.nq.gz
│   ├── b5be8fe91c9cb2b343690322d1419dee0055e66b.nq.gz
│   ├── bbe537463569008bdb55e5411717baec0b218c74.nq.gz
│   ├── bc5fbb726fcf9459f9cba11706de01d4b44eedef.nq.gz
│   ├── bd875b0f15891baf90615e6362a7a2d80608c9b9.nq.gz
│   ├── be81330765764699553aa4fbaf0e9fc27c20c6d2.nq.gz
│   ├── c1bc4c90f54ad07bbdef7ba4d2938c482c6a9f9d.nq.gz
│   ├── c230065e8cf9e8dfd99cf21f74044a1f50099daf.nq.gz
│   ├── c4859cfa0595e60240066e7c2cdd30076d11ed60.nq.gz
│   ├── c55546fe2183bc6f9f1138f02561d25b4a9529f4.nq.gz
│   ├── c9d4df77f450a1b90b7e72e33eabe59b515834a9.nq.gz
│   ├── ce4acccea8b1d1e96a039341a0046a057172cadd.nq.gz
│   ├── d0ca7eb0cfb9c9b67c3a8e47349e0258b69a654b.nq.gz
│   ├── d56cbe3085bd3914961b1eca76c69f2919bdf596.nq.gz
│   ├── d6ad44614d819b15058e3b434957ebc9a7096152.nq.gz
│   ├── d8757e10323dcc6925a6e4d612072db0a87cfea0.nq.gz
│   ├── dd5216246b7ac5989e796eeaecd62e0818485692.nq.gz
│   ├── e093d5eb29cda2eb097d4d28e17949aecd99ed49.nq.gz
│   ├── e27629b274025298de0ccdcd542a4e43e380e24e.nq.gz
│   ├── e39230250aaf9cbe0edfe2fe6f0d8172fd58c8fc.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8e30235b2c60ca040dbfa04adafab8b53d0dba3.nq.gz
│   ├── e93ffb90e17f7e634239a5409129d38002c4e186.nq.gz
│   ├── e9ee148645e0d007587426e4f3e927d78f76c5af.nq.gz
│   ├── ebb9c77772550632dee8fa3ecd1f8be28ea2b5aa.nq.gz
│   ├── ebefd16e1a074597e9e58d4d4be38630600e6748.nq.gz
│   ├── ec1c7cc88e1c67393b72a1aa7867c0e103e2849a.nq.gz
│   ├── ee324a6fa285728f721fdd3d6d6679df6a6a6fd7.nq.gz
│   ├── ee4424288c8f00e1fcadd522db68e6d11019e240.nq.gz
│   ├── eebbff638361154ed3f262a81e915012713e7614.nq.gz
│   ├── ef133e98a24061025c566b35020a250c31845a41.nq.gz
│   ├── ef6aa19949c155078ef715d70e490208e5f56e13.nq.gz
│   ├── f256ecfed20a8751d04e6960897c9e3d0384ed37.nq.gz
│   ├── f31dd3b92ff878ebddf3935017ab6d985a5f8084.nq.gz
│   ├── f43951ec616d7372672b176d7efd739431bfaa17.nq.gz
│   ├── f5417db2406a88d78591f7e2a36f4c84caabcfbd.nq.gz
│   ├── fae2fa370b651c978833e98a5cfa30f1ee8ebf6e.nq.gz
│   ├── fefd7303400860b30bf5e6ec1217201efbbf9f02.nq.gz
│   ├── ff2cdee6e75a49d99ad66113642883940ff62519.nq.gz
│   └── ff654f06f890465690970dc5fa5ac7212b21659a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a2b7a3ebbbb77faa710663b49a427704bc00a257.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 120 files
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

[ipython/ipykernel](https://github.com/ipython/ipykernel)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
