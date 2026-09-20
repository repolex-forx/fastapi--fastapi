# Repolex Knowledge Graph of fastapi/fastapi

RDF knowledge graph data for [fastapi/fastapi](https://github.com/fastapi/fastapi), parsed by [repolex](https://repolex.ai).

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
lexq download fastapi/fastapi
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 1f442c454f2f74c7419f83c203e6333955399528
│   │   │   └── chunk-001.nq.gz
│   │   └── 3c08b05ea6b58b3e5564c026f071cbb0979a6797
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 1f442c454f2f74c7419f83c203e6333955399528.nq.gz
│   │   └── 3c08b05ea6b58b3e5564c026f071cbb0979a6797.nq.gz
│   └── repolex
│       ├── 1f442c454f2f74c7419f83c203e6333955399528
│       │   └── chunk-001.nq.gz
│       └── 3c08b05ea6b58b3e5564c026f071cbb0979a6797
│           └── chunk-001.nq.gz
└── blob
    ├── 00031fcaad53c4a55338b909ef60795b83064a56.nq.gz
    ├── 001a02a0fde649f01ec6f87c224ac615bb4eba0a.nq.gz
    ├── 0052dbcfc4279ee1a9dd8e3a55e575ccd049028a.nq.gz
    ├── 009628453d247828a5c5e07b30626203612a4cc9.nq.gz
    ├── 00969461dc0e1f012b83906e6b4f2deddc756046.nq.gz
    ├── 00b0c52202b37de904b3fd9b5a5432c942ee171f.nq.gz
    ├── 00bbead32875c6e494cdebcdbf86448ef6b2f728.nq.gz
    ├── 00ce765884416584940b8a15dc683bbfe44b501c.nq.gz
    ├── 010e27c37e43417704d85e535ac9838ced3a7101.nq.gz
    ├── 011d5d7fc25ca3783b91a7e96f9cf6f1174db0ee.nq.gz
    ├── 01693e0a016a19df1a0a8db85b5d18c19d795c41.nq.gz
    ├── 018e4f99eb516ff61136d9857ba8d81fb50bfb8b.nq.gz
    ├── 018e6605884dec691520b455e90f7676a62f4ab2.nq.gz
    ├── 01c01d06b0575b1795f0ecbceea061a00c9632d7.nq.gz
    ├── 01d7c983a6bf2f462fab17a332edf67d9d91c04c.nq.gz
    ├── 01dc369a0b3c6b7390fb3ad6edda645e876a622b.nq.gz
    ├── 02183293ce2a631ba423efb07c2863bcb958e8bd.nq.gz
    ├── 023e988dcec7f1afb594eab2d269362ea1c9134b.nq.gz
    ├── 025715f5231aca9af893f9e20577ec8c1cdb1070.nq.gz
    ├── 026405318f8e026f730dba80789ec4c60636f08f.nq.gz
    ├── 0277d73b74ba829780a13290bdf63503762c3dab.nq.gz
    ├── 02792f1f8b97941978a82b78d54d1775b75a1b7e.nq.gz
    ├── 028d280dc7f8f1ca70ec3c54b438836afbefa92e.nq.gz
    ├── 0290b644d374739bc668f7a1f24b99ffcc4fcfe2.nq.gz
    ├── 02acef9f1d112d5f4c284388d457f7019a5762e9.nq.gz
    ├── 030db7756599f3a114c58efb248f558b3f9643bd.nq.gz
    ├── 038b672f8a2fa66bb104edf9bd7b224d2ea22752.nq.gz
    ├── 03a7be3995aaa480ee443d7d41e12ecb40fea338.nq.gz
    ├── 03a98a5f37332a5d91053ac114a9633e7b34a91f.nq.gz
    ├── 03b7d5f338377496483f269f953688a405d125d8.nq.gz
    ├── 03b9f2f76ea97055d0dad948b87aff2940a1c02c.nq.gz
    ├── 03c696a4b62b07e0e48941c9c7d7bf8af4f8e4ba.nq.gz
    ├── 03eea57e326e75ed7009a7d3a2d703ce9ec70d9e.nq.gz
    ├── 03ef75adc7cbbd3e7e29dc2fe1b7c22d22f5c040.nq.gz
    ├── 03fdc2102059306320319b1bda8d779c1d6fdaf2.nq.gz
    ├── 03fe8441e4ff3a5e1278d069dc49e29ec253cc7e.nq.gz
    ├── 040b4f756fe68d97bd66e50bee94fa008abe874a.nq.gz
    ├── 040dc5812971701a3c9a0c8d3232b85fbf3c7328.nq.gz
    ├── 040f8e3b0790c954059334c174145049611a2380.nq.gz
    ├── 042fb1dea93231e9cfd06378f1b66366008a37e6.nq.gz
    ├── 044fdf0d65d7650d2472131da501133bc076485e.nq.gz
    ├── 046c99c29187b05af67acc6e10ce29aa371f6569.nq.gz
    ├── 04773c83f96763bebac8588090b41837b46222bd.nq.gz
    ├── 04c2c2da42e77e3f724dcd5a7e1126174a7fc348.nq.gz
    ├── 04d7f9a4ebb003d0c6d112b859155570d04c59da.nq.gz
    ├── 05088be7ed6b0b7fdbcfd95bf9545a92bf830fef.nq.gz
    ├── 050f17da3e51759182efa69e7d8235c095eb40aa.nq.gz
    ├── 05158b3872caa803c000c3dee1aa3f858ad5534f.nq.gz
    ├── 051656c768b62435b608c58824f622fd0d662b0f.nq.gz
    ├── 053aeffc8a2ba624d527ab8388c6ba7280a60b32.nq.gz
    ├── 053e54b1da4fb5d97cf24fd7b3431a598f1945a3.nq.gz
    ├── 0543e7162dbfbe716951623a7f88a5d4dfab5eb8.nq.gz
    ├── 056dcbbbf355aaeb5008f26f84421c2cbde2150b.nq.gz
    ├── 05742c8e0c61168e30736f2cd0c708c14c8cd0d5.nq.gz
    ├── 05996ac2a22256c131c47af780b0a94b0560bacf.nq.gz
    ├── 05a3cffa5a8ff623dec0efa3c448438040d67877.nq.gz
    ├── 05ac62f3d0d2b09ec00580dfcd77cbcaf58ef02e.nq.gz
    ├── 060951efa47aaa8aaecc00d5971a4a4e58693257.nq.gz
    ├── 06107eb2d1e153765dfd1a79f84f403a792c8a82.nq.gz
    ├── 062c1957423f9a974a8a39916e608f0264061d36.nq.gz
    ├── 06366d5a4504f3cd65ffb8e459d9b6a2a8ffe5f6.nq.gz
    ├── 066a9d9f6b4edff5172e269baae8ca47879c50c8.nq.gz
    ├── 066d6be7a845148fb1189c45fb1d400b098b747c.nq.gz
    ├── 06744507b8e28ff4cf47c927e4a5b526deb64461.nq.gz
    ├── 06a3f2834f694ad6a5db7be35b728a725c71bac8.nq.gz
    ├── 06ac147cdc17a1aa43b04db33ebb4160e18975ec.nq.gz
    ├── 06bf865d92591901b1fe8dde7e8f07a10278d24f.nq.gz
    ├── 06c56565f66937bca6d7c83376637e7ba8a76d4d.nq.gz
    ├── 06d9d03db4f2a8eaa82c051a58592d1ee05456ef.nq.gz
    ├── 06e45ad4c63bc6eca7d610eb0c477bed723e77fe.nq.gz
    ├── 070d0b04bfd03372871989770bd0e8a14616dde7.nq.gz
    ├── 0719430ac71583bf9cdaa6f9e21ba40bcaf9fcd1.nq.gz
    ├── 072d219522185efead6021b533a6113af940d06b.nq.gz
    ├── 074b36031244e5b690e377d04ffa3ac98eea42d8.nq.gz
    ├── 0774dc4413ee0708a94077093674e7082ee7e392.nq.gz
    ├── 0777263125499ffc75f3ddbf6fbf9aa4bb3afbfc.nq.gz
    ├── 07bd74b1327d665094f184d3276ce63d3728be78.nq.gz
    ├── 07bfa83bfe5f867aaef6b99cea5319cae3c8766b.nq.gz
    ├── 07fc6fa37f9c1b32d64bc99b14fcad178c7730c3.nq.gz
    ├── 080e9e67dcb3ddb869a5c0a181598a7a42e5dcaa.nq.gz
    ├── 081259b31703aa93ac75ccc306721ef2b56e5309.nq.gz
    ├── 08246f513b9ddf3b1065788c2004d1908f6618df.nq.gz
    ├── 082bec1f03397216526eb95486e8cbc96d074691.nq.gz
    ├── 0832eedcb92b747444e4fcc406c845ed51fa21bd.nq.gz
    ├── 083a024af0d0d6047e49b75d00ad0bf940629e12.nq.gz
    ├── 084d72aa40c08876ea2d4114ae84285a66b28cbd.nq.gz
    ├── 086665c040ab4d9606986a6b0f1ded3591f8e611.nq.gz
    ├── 088ad9bef53854dd355df08840807304cdf24d2e.nq.gz
    ├── 08a54817272c2fa1e38fb9664ad691f198a93171.nq.gz
    ├── 08a5e11a54777f7a5b8bc8eea8fb67f2aa932444.nq.gz
    ├── 08ab44a941b912f06a37770a12d4dc11996a617e.nq.gz
    ├── 08d0221d3d0262a6a8fc65bd0e7fc8022d161ef0.nq.gz
    ├── 08d7e035315677856fd2cd0be2044689b57619bf.nq.gz
    ├── 08f8f88c280ac1e61428b797322b290c2eefd3fb.nq.gz
    ├── 08fb9b74f48dec50c26ff11cc5b566022cf24988.nq.gz
    ├── 09039435f1420488294da9dc03023bb24c4d0534.nq.gz
    ├── 0918d352ead3f0402aadb2fa915af9f5952d79b7.nq.gz
    ├── 09264b7e26693e898f69903ab199c61910d500db.nq.gz
    ├── 0932c8d90f2cc84ff16d7b259ed23a7e8e7d7ae8.nq.gz
    ├── 09cd48fafd0f3e535dbce4f4e5e5b51ce7668d67.nq.gz
    ├── 09d8be768ada6fcf7e7d89b7581edb478a7d5ca5.nq.gz
    ├── 09e03959e55a0725e79f1b401d6872671bce40ac.nq.gz
    ├── 0a008c0de64e2b9683e656e0ea8554290a8bdec4.nq.gz
    ├── 0a4c9c5e53111c0e0db7ade73f1c226ea62ed07c.nq.gz
    ├── 0a5aa6943603fd74e8980927e58ac552850880a5.nq.gz
    ├── 0a82004d2c2fa23f15a182f8302cb2b78b32f2a8.nq.gz
    ├── 0a8cf420ed00dd1a28a0537ba49e2831f9fcc043.nq.gz
    ├── 0a91a5967f816c7aef34d0f9cbf1524a30533e4f.nq.gz
    ├── 0aa6e180910b313629fcf4de3709c149d252944a.nq.gz
    ├── 0aafda954cdf7f2151c0567c73c06b0dd653a020.nq.gz
    ├── 0ad35cc4fc881a363080182a8677eea84e457752.nq.gz
    ├── 0b0f44869fd5fbec5a02beb102c870fb28a31fed.nq.gz
    ├── 0b16c0cb45d17fdce5118904f815d95f02bc3605.nq.gz
    ├── 0b2da213c378dd5c1cc8c25399c6454b4295c3b4.nq.gz
    ├── 0b2f39f13dbde1e60b724a4736df63abe79e3882.nq.gz
    ├── 0b4d14ff47cd37c3eee84eb995595143b3f66fa0.nq.gz
    ├── 0b5f9d95bbb158f8baf10eaf617daf2d394e8c3b.nq.gz
    ├── 0b647a438830903f981a5b47812b7168d043f69b.nq.gz
    ├── 0b7fcc1c514094c49fb74563a1faf687939ef492.nq.gz
    ├── 0b8677bfd339b8509deed87b6eb93ba1d7333519.nq.gz
    ├── 0b920c3b388e48454d329d2eaf05dbb7e18dfe4e.nq.gz
    ├── 0ba4f8af68c80acc1330c456c6f6771abcfca08e.nq.gz
    ├── 0bacbb39472316d68e5e6652d1859e7e5df6f163.nq.gz
    ├── 0bc17a00e12537909fa56f46e916a88bfeddaf8c.nq.gz
    ├── 0bd8aa543381b7fa274fa2302c17760eab0f094c.nq.gz
    ├── 0c19579f5e3b21bf5a843ee58f9fcbb55313adf3.nq.gz
    ├── 0c2f62c4f9086048dc4783837ea02de3d0a96557.nq.gz
    ├── 0c675089ca3f01ce698f0a39f0e1fa99b1d570a8.nq.gz
    ├── 0cb868486edd9dda38f90c65f314597813128cf8.nq.gz
    ├── 0cb9831a89866eec691bf823eaae8a268ddf0fa4.nq.gz
    ├── 0cddcd390218190eacb5abb0371bac7522aeaf98.nq.gz
    ├── 0cf3d03a9f9c3992670f0fb7cfcfa637a2b92898.nq.gz
    ├── 0d0c42fd540a75e0b302370c64b1e8951d33503f.nq.gz
    ├── 0d1136eb4dcab6eda0afbd5b843b12b6678966c6.nq.gz
    ├── 0d2471489a756dbbc96e73dd2904638b02541a39.nq.gz
    ├── 0d268800af659fdb25a4dd5ad5269c340137d0f7.nq.gz
    ├── 0d31a69af8395352f8bea515168e8c36c1276574.nq.gz
    ├── 0d48e28424fa2c1eab6744eabbe55e25453f7e38.nq.gz
    ├── 0d4bd8de57da331940460136db32c2f4ef359377.nq.gz
    ├── 0d4c2e46d617482936d02ef2a6048f856d64f51a.nq.gz
    ├── 0d9242f9fa6a5212114b8f4036adfaf0e518020f.nq.gz
    ├── 0da5db0cfa52c035d8b80c3ea71e297bd042ce67.nq.gz
    ├── 0dcb575176d173c162cf4161bcc09f38662ff576.nq.gz
    ├── 0dd6f25145ecc21af6f7d6962dd06edfebbc1f98.nq.gz
    ├── 0deb7e48ff79ccbb9acebf9a09b9b4f1d9a737bd.nq.gz
    ├── 0dee012cd5819327cadf0b612acb871f04ae9760.nq.gz
    ├── 0df9a46e578914bf4c1fd9434916f0efe9956baa.nq.gz
    ├── 0e021dadea27ee03e29f28bf286aff3a5359ac13.nq.gz
    ├── 0e04fa086405056103e5f696a0ae7862c23551a1.nq.gz
    ├── 0e0a3bdbdf14e5dbcfc6fc4bd26f07797cb84287.nq.gz
    ├── 0e328cdd95691bb1d063f6aa45be35ac96edd29d.nq.gz
    ├── 0e5941a8d6c8d2d931221a0c6fd62dd1ea9990d7.nq.gz
    ├── 0e7321ee7ced6c7ac94daee5dc09c14660217237.nq.gz
    ├── 0e78cf02903a1a0e22da3d9c9597a552fcccd066.nq.gz
    ├── 0e8ae2ba644b73371d3b09b6fd1df9a6f70145f4.nq.gz
    ├── 0e8da4dcefa52518c93dab49a4fc35cf0e211782.nq.gz
    ├── 0e90f20126431224d087a4a8d06fdf7c4fe325f5.nq.gz
    ├── 0e9a100ea4e8bac7a85e54915286a602e0d9c5e2.nq.gz
    ├── 0ea1d0df4eb904c608b5a263f40c1479bd4bb562.nq.gz
    ├── 0eb55fb73a8648729cb78de5047cb3d159ee86a3.nq.gz
    ├── 0eb6c3c7967f8c66c3723fc14979d4cfcf8b2523.nq.gz
    ├── 0ef706a4d176919cfce180dd89b09c23102b1a2f.nq.gz
    ├── 0f076399227a1aab49828cfe009c91372a123e1a.nq.gz
    ├── 0f09bdf77fdb865b6dea4b9f87e3a868ade995bf.nq.gz
    ├── 0f0e94fdaacae33bc82c58f8e1b43b3905cd13aa.nq.gz
    ├── 0f12b9d529aaf6b594ebf0e5bba05020300eecd1.nq.gz
    ├── 0f1e6dcfd178bb4a7fdc4d4978875c5cb3160b56.nq.gz
    ├── 0f46890d9b31199bdf687c799bdc005d767fcce5.nq.gz
    ├── 0f55ae6516ebf0c3fccfc2080c5d2818db0c061c.nq.gz
    ├── 0f6136f4fdd19611ded9215efa7c3fa35884ec87.nq.gz
    ├── 0f81f4c46a7665aca3edc3976543afea29fc4ee4.nq.gz
    ├── 0f97909c22730fe65d47eac496c23547a122de0e.nq.gz
    ├── 0f99c1d32c6448dd020f4252a96529420841cbcf.nq.gz
    ├── 0fa399c6ae126cc173fffcc8e4e5da7feaf8d50d.nq.gz
    ├── 0fdf697b6ce66fead92a6673ba0f4aace6085dca.nq.gz
    ├── 0ffa28dbfa33917a09eb209c64860a59b9a10237.nq.gz
    ├── 0ffc101a3f23548392499fe5104f3f8cf4d4e91b.nq.gz
    ├── 1020b890cf8ba5d86882197b68a710db4f66874f.nq.gz
    ├── 106607fd2d3ace29c56fb0f493d90806684b62ff.nq.gz
    ├── 1068983395493188ba8c468b78893c6e953970c3.nq.gz
    ├── 108c4377096bcd36e9810d3d4e681f897c54c6e0.nq.gz
    ├── 10be4c865c64f54a1a44d71779830b8f3857249c.nq.gz
    ├── 10d3771c1ab406db89192037433156c9d6a83c33.nq.gz
    ├── 10d6716c649e74732c5afd120710981b8b30f16f.nq.gz
    ├── 10e7be50cb9a1293bf94459ff3bfa57dcf8ff4b5.nq.gz
    ├── 110821c2d1ceed674afd02c8f2af5947079f56e1.nq.gz
    ├── 110bba05380ae36c4c67b8f727f894fdcd140282.nq.gz
    ├── 111c714946131a0003b65da35f5d2a4faf9cf329.nq.gz
    ├── 113ca478582b24b0010f20ad21270d590df55da6.nq.gz
    ├── 114c3c6cb2b13cf83b96c3c2b1fc8ee5aa6c951c.nq.gz
    ├── 1165fd7a05642f8d59353787bc0afb2e0539f07e.nq.gz
    ├── 1183c08c0fd43d16b40e0bf1e81e0dd94d018fe6.nq.gz
    ├── 118c65e044bf7eb376ba93f03b082e9079560119.nq.gz
    └── 118d5181495ab7613ee3ecc2f864e4ae689ad440.nq.gz

10 directories, 200 files
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

[fastapi/fastapi](https://github.com/fastapi/fastapi)

---
*Parsed on 2026-09-20 by [repolex](https://repolex.ai)*
