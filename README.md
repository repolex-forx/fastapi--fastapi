# Repolex Knowledge Graph of fastapi/fastapi

RDF knowledge graph data for [fastapi/fastapi](https://github.com/fastapi/fastapi), parsed by [repolex](https://repolex.ai).

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
rlex download fastapi/fastapi
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 12ea7be0bed9dc13a4dd859a7c96970355140333
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1f442c454f2f74c7419f83c203e6333955399528
│   │   │   └── chunk-001.nq.gz
│   │   ├── 25a3697cedc6e7dfb84e93c8ff965801486f00f4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3c08b05ea6b58b3e5564c026f071cbb0979a6797
│   │   │   └── chunk-001.nq.gz
│   │   └── ca5f60ee72f35fb2134d8b5d26bbb75965bcff66
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 12ea7be0bed9dc13a4dd859a7c96970355140333.nq.gz
│   │   ├── 1f442c454f2f74c7419f83c203e6333955399528.nq.gz
│   │   ├── 25a3697cedc6e7dfb84e93c8ff965801486f00f4.nq.gz
│   │   ├── 3c08b05ea6b58b3e5564c026f071cbb0979a6797.nq.gz
│   │   └── ca5f60ee72f35fb2134d8b5d26bbb75965bcff66.nq.gz
│   └── repolex
│       ├── 12ea7be0bed9dc13a4dd859a7c96970355140333
│       │   └── chunk-001.nq.gz
│       ├── 1f442c454f2f74c7419f83c203e6333955399528
│       │   └── chunk-001.nq.gz
│       ├── 25a3697cedc6e7dfb84e93c8ff965801486f00f4
│       │   └── chunk-001.nq.gz
│       ├── 3c08b05ea6b58b3e5564c026f071cbb0979a6797
│       │   └── chunk-001.nq.gz
│       └── ca5f60ee72f35fb2134d8b5d26bbb75965bcff66
│           └── chunk-001.nq.gz
└── blob
    ├── 000201de9981a3b19dc360e373a562db16b55376.nq.gz
    ├── 00031fcaad53c4a55338b909ef60795b83064a56.nq.gz
    ├── 001a02a0fde649f01ec6f87c224ac615bb4eba0a.nq.gz
    ├── 0045eab749e8acff4249114f45120dcad734bb19.nq.gz
    ├── 0052dbcfc4279ee1a9dd8e3a55e575ccd049028a.nq.gz
    ├── 00945eab5933c93b12412b9e18a0b210a40e5918.nq.gz
    ├── 009628453d247828a5c5e07b30626203612a4cc9.nq.gz
    ├── 00969461dc0e1f012b83906e6b4f2deddc756046.nq.gz
    ├── 00b0c52202b37de904b3fd9b5a5432c942ee171f.nq.gz
    ├── 00bbead32875c6e494cdebcdbf86448ef6b2f728.nq.gz
    ├── 00ce765884416584940b8a15dc683bbfe44b501c.nq.gz
    ├── 010e27c37e43417704d85e535ac9838ced3a7101.nq.gz
    ├── 011d5d7fc25ca3783b91a7e96f9cf6f1174db0ee.nq.gz
    ├── 01540ad17ca1f3e7c15f59632f92c10b04b5ca3d.nq.gz
    ├── 01693e0a016a19df1a0a8db85b5d18c19d795c41.nq.gz
    ├── 017de20967b7279a91ca8c0c801322adaf6c7ba3.nq.gz
    ├── 018e4f99eb516ff61136d9857ba8d81fb50bfb8b.nq.gz
    ├── 018e6605884dec691520b455e90f7676a62f4ab2.nq.gz
    ├── 01a0b72eb91fe1fabf30567ffcd3e9a99e3f9a7b.nq.gz
    ├── 01bde56d2a0ab1dc17f2e0e6da77d1f0d0981d37.nq.gz
    ├── 01c01d06b0575b1795f0ecbceea061a00c9632d7.nq.gz
    ├── 01d7c983a6bf2f462fab17a332edf67d9d91c04c.nq.gz
    ├── 01dc369a0b3c6b7390fb3ad6edda645e876a622b.nq.gz
    ├── 01f71ac2fc61d8bbb2610c814fc5cadb8d94e2e5.nq.gz
    ├── 0210812b6eb442626e441d933c21666da6bdeb98.nq.gz
    ├── 0217f42768e10c91355811c162cdf25eec8dd7be.nq.gz
    ├── 02183293ce2a631ba423efb07c2863bcb958e8bd.nq.gz
    ├── 0235d83c7f80a8afc2a2f9191d7ebcfb2d01b61e.nq.gz
    ├── 0239a15128150879f8abb881f6da57aec8e71a93.nq.gz
    ├── 023e988dcec7f1afb594eab2d269362ea1c9134b.nq.gz
    ├── 0251b9b4b267f9caf608e12da2f569dc6c205aa1.nq.gz
    ├── 025715f5231aca9af893f9e20577ec8c1cdb1070.nq.gz
    ├── 026405318f8e026f730dba80789ec4c60636f08f.nq.gz
    ├── 0277d73b74ba829780a13290bdf63503762c3dab.nq.gz
    ├── 02792f1f8b97941978a82b78d54d1775b75a1b7e.nq.gz
    ├── 027975ec564a14d9f2d82a8bbd16dcd53398c3fb.nq.gz
    ├── 028d280dc7f8f1ca70ec3c54b438836afbefa92e.nq.gz
    ├── 0290b644d374739bc668f7a1f24b99ffcc4fcfe2.nq.gz
    ├── 029572d4337e48971099c68cdef946821c865673.nq.gz
    ├── 029ea1d274ea7fd138a5c2d090da1f53a5d4c532.nq.gz
    ├── 02acef9f1d112d5f4c284388d457f7019a5762e9.nq.gz
    ├── 030db7756599f3a114c58efb248f558b3f9643bd.nq.gz
    ├── 030f8dcc5af95bc420e2a2041ec4268372374982.nq.gz
    ├── 0351e8b5e556441e54c2469663d6f1a06c729ba6.nq.gz
    ├── 03736fa43fee331a45be40390a2fdb0a62f98f29.nq.gz
    ├── 038b672f8a2fa66bb104edf9bd7b224d2ea22752.nq.gz
    ├── 03a7be3995aaa480ee443d7d41e12ecb40fea338.nq.gz
    ├── 03a7c083c431be99317c4d9d03c29c2be6ad4399.nq.gz
    ├── 03a98a5f37332a5d91053ac114a9633e7b34a91f.nq.gz
    ├── 03b7d5f338377496483f269f953688a405d125d8.nq.gz
    ├── 03b7db63940b54037807f591b7e7ae35daae8653.nq.gz
    ├── 03b9f2f76ea97055d0dad948b87aff2940a1c02c.nq.gz
    ├── 03c696a4b62b07e0e48941c9c7d7bf8af4f8e4ba.nq.gz
    ├── 03d3bd03be69afbcd175c71f9b19f1c1c64aab81.nq.gz
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
    ├── 0479ac41d15d1f2eb11fd68d4ea5d78c48ca7efa.nq.gz
    ├── 04c2c2da42e77e3f724dcd5a7e1126174a7fc348.nq.gz
    ├── 04d7f9a4ebb003d0c6d112b859155570d04c59da.nq.gz
    ├── 05088be7ed6b0b7fdbcfd95bf9545a92bf830fef.nq.gz
    ├── 050f17da3e51759182efa69e7d8235c095eb40aa.nq.gz
    ├── 05158b3872caa803c000c3dee1aa3f858ad5534f.nq.gz
    ├── 051656c768b62435b608c58824f622fd0d662b0f.nq.gz
    ├── 05299323cbb1613f1e41b0ea3e2d46e21c3cee0a.nq.gz
    ├── 05322a4d1e613068352b2c3a75ad5311393a7d59.nq.gz
    ├── 053aeffc8a2ba624d527ab8388c6ba7280a60b32.nq.gz
    ├── 053e54b1da4fb5d97cf24fd7b3431a598f1945a3.nq.gz
    ├── 0543e7162dbfbe716951623a7f88a5d4dfab5eb8.nq.gz
    ├── 0544eb9ba4f90f7e4b941da8a1686dbefd1ee971.nq.gz
    ├── 055cfeacadee7e7f396961a9a9ce8100aa92828e.nq.gz
    ├── 056dcbbbf355aaeb5008f26f84421c2cbde2150b.nq.gz
    ├── 05742c8e0c61168e30736f2cd0c708c14c8cd0d5.nq.gz
    ├── 0589e479bf4599eccf74b0a9f4844b82ce471b27.nq.gz
    ├── 05996ac2a22256c131c47af780b0a94b0560bacf.nq.gz
    ├── 05a3cffa5a8ff623dec0efa3c448438040d67877.nq.gz
    ├── 05ac62f3d0d2b09ec00580dfcd77cbcaf58ef02e.nq.gz
    ├── 05c512e99b0fdec3729c024298d2e0522f32c5d8.nq.gz
    ├── 05f949738df76e743f2a8f20d784a547b6744f8b.nq.gz
    ├── 060951efa47aaa8aaecc00d5971a4a4e58693257.nq.gz
    ├── 06107eb2d1e153765dfd1a79f84f403a792c8a82.nq.gz
    ├── 062c1957423f9a974a8a39916e608f0264061d36.nq.gz
    ├── 06366d5a4504f3cd65ffb8e459d9b6a2a8ffe5f6.nq.gz
    ├── 06596223666a728eae9b8abdf419d71635641a83.nq.gz
    ├── 066a9d9f6b4edff5172e269baae8ca47879c50c8.nq.gz
    ├── 066d6be7a845148fb1189c45fb1d400b098b747c.nq.gz
    ├── 06744507b8e28ff4cf47c927e4a5b526deb64461.nq.gz
    ├── 067e9cc9a22ef7e2fdc48cd9fde4668596ae5495.nq.gz
    ├── 069e2686cb1b47fb702e0e7854d89f959896baaa.nq.gz
    ├── 06a3f2834f694ad6a5db7be35b728a725c71bac8.nq.gz
    ├── 06a9f1b4421a1218541ff4cb57e1db2282482293.nq.gz
    ├── 06ac147cdc17a1aa43b04db33ebb4160e18975ec.nq.gz
    ├── 06b6176760419a0155044a3247d158c3291c46b2.nq.gz
    ├── 06bea4794d12f57b08a25ff4f8383041316daa19.nq.gz
    ├── 06bf865d92591901b1fe8dde7e8f07a10278d24f.nq.gz
    ├── 06c56565f66937bca6d7c83376637e7ba8a76d4d.nq.gz
    ├── 06d9d03db4f2a8eaa82c051a58592d1ee05456ef.nq.gz
    ├── 06dacbd9dcffea2bf3ba1ca1d3946a8f55850eb2.nq.gz
    ├── 06e45ad4c63bc6eca7d610eb0c477bed723e77fe.nq.gz
    ├── 0705e120c4c12695fdaee2601aea1f197abdf98b.nq.gz
    ├── 07094b9cbdab63e4544c8ee9ca2b0ebdd59125b1.nq.gz
    ├── 070d0b04bfd03372871989770bd0e8a14616dde7.nq.gz
    ├── 0717ea5ff78add78602b43cc2d846aaf9e219cae.nq.gz
    ├── 071867964b744ee3577ab12cc8d152514ac25f3b.nq.gz
    ├── 0719430ac71583bf9cdaa6f9e21ba40bcaf9fcd1.nq.gz
    ├── 072d219522185efead6021b533a6113af940d06b.nq.gz
    ├── 074b36031244e5b690e377d04ffa3ac98eea42d8.nq.gz
    ├── 07573f01f9099c26afdaf0811900633b5cebfe94.nq.gz
    ├── 0774dc4413ee0708a94077093674e7082ee7e392.nq.gz
    ├── 0777263125499ffc75f3ddbf6fbf9aa4bb3afbfc.nq.gz
    ├── 07ad31440595f8111eb5450e9c89764681c6e95d.nq.gz
    ├── 07bd74b1327d665094f184d3276ce63d3728be78.nq.gz
    ├── 07bfa83bfe5f867aaef6b99cea5319cae3c8766b.nq.gz
    ├── 07dc2012332001a93231548f1944c8ad70485d84.nq.gz
    ├── 07fc6fa37f9c1b32d64bc99b14fcad178c7730c3.nq.gz
    ├── 080e9e67dcb3ddb869a5c0a181598a7a42e5dcaa.nq.gz
    ├── 081259b31703aa93ac75ccc306721ef2b56e5309.nq.gz
    ├── 08246f513b9ddf3b1065788c2004d1908f6618df.nq.gz
    ├── 082bec1f03397216526eb95486e8cbc96d074691.nq.gz
    ├── 0832eedcb92b747444e4fcc406c845ed51fa21bd.nq.gz
    ├── 083a024af0d0d6047e49b75d00ad0bf940629e12.nq.gz
    ├── 084d72aa40c08876ea2d4114ae84285a66b28cbd.nq.gz
    ├── 085a1756f8b5f0b72333fcab4e0427aa8e824dfe.nq.gz
    ├── 086665c040ab4d9606986a6b0f1ded3591f8e611.nq.gz
    ├── 088ad9bef53854dd355df08840807304cdf24d2e.nq.gz
    ├── 08963306fba37bd5184ed3ebf9fb4f0f2fe462a5.nq.gz
    ├── 089967a51ae3d6b011b23418c6c040584f304390.nq.gz
    ├── 08a54817272c2fa1e38fb9664ad691f198a93171.nq.gz
    ├── 08a554b8d6bc0ad6b0c604e89f81edc815ddd8c9.nq.gz
    ├── 08a5e11a54777f7a5b8bc8eea8fb67f2aa932444.nq.gz
    ├── 08ab44a941b912f06a37770a12d4dc11996a617e.nq.gz
    ├── 08d0221d3d0262a6a8fc65bd0e7fc8022d161ef0.nq.gz
    ├── 08d7e035315677856fd2cd0be2044689b57619bf.nq.gz
    ├── 08d9a7a723c8c0dc1051e6ae2b91a50c940c66df.nq.gz
    ├── 08f8f88c280ac1e61428b797322b290c2eefd3fb.nq.gz
    ├── 08fb9b74f48dec50c26ff11cc5b566022cf24988.nq.gz
    ├── 09039435f1420488294da9dc03023bb24c4d0534.nq.gz
    ├── 0918d352ead3f0402aadb2fa915af9f5952d79b7.nq.gz
    ├── 09264b7e26693e898f69903ab199c61910d500db.nq.gz
    ├── 092c310011ca73c10197674d883af875914fb4d8.nq.gz
    ├── 0932c8d90f2cc84ff16d7b259ed23a7e8e7d7ae8.nq.gz
    ├── 0934b0283146aa39784fce46e92515ccf40a0acd.nq.gz
    ├── 0995e102859175399c1f532910798e6d2cd4f336.nq.gz
    ├── 09baa473193adf5475319820899f391c97948ffb.nq.gz
    ├── 09cd48fafd0f3e535dbce4f4e5e5b51ce7668d67.nq.gz
    ├── 09d4498aca7935f062785a7cad029a1cb1d2b18d.nq.gz
    ├── 09d8be768ada6fcf7e7d89b7581edb478a7d5ca5.nq.gz
    ├── 09e03959e55a0725e79f1b401d6872671bce40ac.nq.gz
    ├── 0a008c0de64e2b9683e656e0ea8554290a8bdec4.nq.gz
    ├── 0a02b47aecf4975eefacfaf422753721d900fa38.nq.gz
    ├── 0a0c785a015589d2d9e947b93fb28a6643fc32b4.nq.gz
    ├── 0a4bed26603f1823b55c9c8d7b4a358c5497f7a1.nq.gz
    ├── 0a4c9c5e53111c0e0db7ade73f1c226ea62ed07c.nq.gz
    ├── 0a5aa6943603fd74e8980927e58ac552850880a5.nq.gz
    ├── 0a6788502a90b65bcad173c4d50974054e96fbb1.nq.gz
    ├── 0a6b1f922cde554e515aaf4cf993c62b0b8b7344.nq.gz
    ├── 0a82004d2c2fa23f15a182f8302cb2b78b32f2a8.nq.gz
    ├── 0a8cf420ed00dd1a28a0537ba49e2831f9fcc043.nq.gz
    ├── 0a91a5967f816c7aef34d0f9cbf1524a30533e4f.nq.gz
    ├── 0aa6e180910b313629fcf4de3709c149d252944a.nq.gz
    ├── 0aafda954cdf7f2151c0567c73c06b0dd653a020.nq.gz
    ├── 0ad35cc4fc881a363080182a8677eea84e457752.nq.gz
    ├── 0b004bf4e532bb4e461497f1afa06ed9e28fb380.nq.gz
    ├── 0b0f44869fd5fbec5a02beb102c870fb28a31fed.nq.gz
    ├── 0b16c0cb45d17fdce5118904f815d95f02bc3605.nq.gz
    ├── 0b2d0718f2873c26c53b352bb0d3002c1e8e6d19.nq.gz
    ├── 0b2da213c378dd5c1cc8c25399c6454b4295c3b4.nq.gz
    ├── 0b2f39f13dbde1e60b724a4736df63abe79e3882.nq.gz
    ├── 0b4d14ff47cd37c3eee84eb995595143b3f66fa0.nq.gz
    ├── 0b5f9d95bbb158f8baf10eaf617daf2d394e8c3b.nq.gz
    ├── 0b647a438830903f981a5b47812b7168d043f69b.nq.gz
    ├── 0b7fcc1c514094c49fb74563a1faf687939ef492.nq.gz
    ├── 0b8677bfd339b8509deed87b6eb93ba1d7333519.nq.gz
    ├── 0b920c3b388e48454d329d2eaf05dbb7e18dfe4e.nq.gz
    ├── 0ba4f8af68c80acc1330c456c6f6771abcfca08e.nq.gz
    ├── 0ba586c1c1ff419b5a9422af9b1d43e784de9709.nq.gz
    └── 0ba5cca752b7c727f8c6da8aaac80d919ca29f78.nq.gz

16 directories, 200 files
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

[fastapi/fastapi](https://github.com/fastapi/fastapi)

---
*Parsed on 2026-09-25 by [repolex](https://repolex.ai)*
