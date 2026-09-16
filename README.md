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
│   │   └── 3c08b05ea6b58b3e5564c026f071cbb0979a6797
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 3c08b05ea6b58b3e5564c026f071cbb0979a6797.nq.gz
│   └── repolex
│       └── 3c08b05ea6b58b3e5564c026f071cbb0979a6797
│           └── chunk-001.nq.gz
└── blob
    ├── 00bbead32875c6e494cdebcdbf86448ef6b2f728.nq.gz
    ├── 018e4f99eb516ff61136d9857ba8d81fb50bfb8b.nq.gz
    ├── 02183293ce2a631ba423efb07c2863bcb958e8bd.nq.gz
    ├── 0290b644d374739bc668f7a1f24b99ffcc4fcfe2.nq.gz
    ├── 03a98a5f37332a5d91053ac114a9633e7b34a91f.nq.gz
    ├── 050f17da3e51759182efa69e7d8235c095eb40aa.nq.gz
    ├── 051656c768b62435b608c58824f622fd0d662b0f.nq.gz
    ├── 056dcbbbf355aaeb5008f26f84421c2cbde2150b.nq.gz
    ├── 06e45ad4c63bc6eca7d610eb0c477bed723e77fe.nq.gz
    ├── 088ad9bef53854dd355df08840807304cdf24d2e.nq.gz
    ├── 08ab44a941b912f06a37770a12d4dc11996a617e.nq.gz
    ├── 09039435f1420488294da9dc03023bb24c4d0534.nq.gz
    ├── 09d8be768ada6fcf7e7d89b7581edb478a7d5ca5.nq.gz
    ├── 0c19579f5e3b21bf5a843ee58f9fcbb55313adf3.nq.gz
    ├── 0d1136eb4dcab6eda0afbd5b843b12b6678966c6.nq.gz
    ├── 0d268800af659fdb25a4dd5ad5269c340137d0f7.nq.gz
    ├── 0d4c2e46d617482936d02ef2a6048f856d64f51a.nq.gz
    ├── 0f076399227a1aab49828cfe009c91372a123e1a.nq.gz
    ├── 106607fd2d3ace29c56fb0f493d90806684b62ff.nq.gz
    ├── 1165fd7a05642f8d59353787bc0afb2e0539f07e.nq.gz
    ├── 11ef51eaa9a61fb83b201a924a3a7e6c49df70e8.nq.gz
    ├── 1301aafa8835bca38f384f341bac8f5dc6245cc0.nq.gz
    ├── 1477ea10f83ac866eff40c2b1dc371d035134ba8.nq.gz
    ├── 15f10653ab381c537e24f3da1a6e337e27008836.nq.gz
    ├── 16bab8a0c0c6b8c19b3b4f6e500c6b7514bac4ca.nq.gz
    ├── 17756468b1475ef11b93a0d4122a47fc3cb0d4ea.nq.gz
    ├── 183180cd742b03fa1152ab5bf207f85d01051eaf.nq.gz
    ├── 1882a6397a9542ee181e31119b3c55f33de3237c.nq.gz
    ├── 1b4040fde609d19db9f1a4726cc775a418bf3b7b.nq.gz
    ├── 1bea246cdc68bbb854773a460c6fdcd1efea5de3.nq.gz
    ├── 1c4b523411bd95d8300e8a37d56c43b058e60374.nq.gz
    ├── 1d3e902400d103bf399ac71492f05668ae170bd9.nq.gz
    ├── 1f0d9d5d360e623ed79f88d166980d7c6c161e6b.nq.gz
    ├── 1fb5b16c23394ee27bbaa518e15f70f935a83618.nq.gz
    ├── 214e6426365b3b4e0fc23b5267eee673028c17f0.nq.gz
    ├── 218fbb0ace13b9b70304bdcb0935ade97adb4366.nq.gz
    ├── 22eb3acba16c9ff9a543adba1f6879838490d4f9.nq.gz
    ├── 23ad4fad5765319e422e956b4b9d697dd5277662.nq.gz
    ├── 254f8f999b8b893a50638c12ce947b49f6134ae9.nq.gz
    ├── 257928ef39b3783388ea591f6c93b1d12521ec06.nq.gz
    ├── 27a683fce7a3a3f15df0a6d42a0a13ef32d09090.nq.gz
    ├── 2809f37b27ed3520be0e3d41392d6d8482d68757.nq.gz
    ├── 281746b26599a709e3980fb2aefad76b62c68a70.nq.gz
    ├── 28cafd63d3931fdb0474a146aef6b716a5660447.nq.gz
    ├── 29387f8c13d53144e846577567260cbc8ff18356.nq.gz
    ├── 296c34272c3f5ad5f819f256980e6a82dc3c5a71.nq.gz
    ├── 2aa61ebfbf8d9790565c19a30741ab5affa8067a.nq.gz
    ├── 2b6d2f7b9943277ca8cc109ad6f9126120458da6.nq.gz
    ├── 2d5a0b8627e46feb03e9cbcd9d2bf6ecc26f38c5.nq.gz
    ├── 2d6114d3e0a8c5794020c02f67969cb06b779fae.nq.gz
    ├── 2da0dd20f30a6efe30c1e44b65e690577ee45acb.nq.gz
    ├── 2dce3a863ba2af4bf56043ce75fd02fcdc5a4893.nq.gz
    ├── 2ddfcddb4f14fc7c34ec4a2068b65dcf14166d43.nq.gz
    ├── 2e2416ce6558a4459a85d452a11c6f9f708ce4e0.nq.gz
    ├── 2ec70828013e56faa8ae5df7caf4a358ebc69fd7.nq.gz
    ├── 2fad25ef7ed89354c6c9dcaf12a6bf7a270405ef.nq.gz
    ├── 2faead19d3fb595aa20863836b55f14205132f48.nq.gz
    ├── 2fe93810eef27deb1caeb941d8924abef9ffd5a4.nq.gz
    ├── 301f1a86214ede899d78357cbaff8dff54d82812.nq.gz
    ├── 30637a5285dbdbdf5947c79e574a7076db63ba03.nq.gz
    ├── 311ece816a59bc45a89ee3c3e2d9c66ff31c4089.nq.gz
    ├── 32db02a074b02510210f377ac979691ce0be596f.nq.gz
    ├── 32ef351dab7c9e65d3094e6cb6f0f0aed156b14d.nq.gz
    ├── 339f80e933fc7734eb159f467a583a29d9240895.nq.gz
    ├── 34563b28c06baceb6c2e354aad975fc7573f085b.nq.gz
    ├── 34b868563bd904e5dc906849748389576cf69855.nq.gz
    ├── 359b33cccb1e81181dd10172cc26b8699b3359b5.nq.gz
    ├── 36b312352d93b84680acb4d599a470fc4b137034.nq.gz
    ├── 37e3fbc4a361338b668f753b895475a0c708e3d3.nq.gz
    ├── 39f5311c27ea42f0b5de0aa9671cfa96de3cbf36.nq.gz
    ├── 3a1d3fb520f9bf096057f02f6c642c0f33fbd74b.nq.gz
    ├── 3b50b05bd963bfbce1eb5a0950a1fe61426a10fd.nq.gz
    ├── 3d5a1a546e309912295d0a5f06fc68d66bdd1310.nq.gz
    ├── 3d9afec786c57b92990f11fffd890e0374565c0d.nq.gz
    ├── 3e4aeb67cf03e359e3b24e4cf6cc1919e29a5c3d.nq.gz
    ├── 3e92463e6bd522a2a21e5f0a80d8089d6c4be20d.nq.gz
    ├── 3e99fcdde799d25f2d35590ae02105ff87991bfb.nq.gz
    ├── 3f73619682dea9e10515f9b6753563575c654860.nq.gz
    ├── 3fb475b9d9cc74862f2f14756156497aa6fd5662.nq.gz
    ├── 404c4f5205ef628a08461c5b2e81c6418ce1bd49.nq.gz
    ├── 4102cfc7d98dc00169107ec1829d623b682bc409.nq.gz
    ├── 4407baf9aa8fea20c6b86a44f968043718d7e64d.nq.gz
    ├── 468cffc2dcfe0f59758b43219b61c881ae80312a.nq.gz
    ├── 46a241902ba9cf451a15238355389bd10f65bbec.nq.gz
    ├── 47800ebf188484eb4e3d6b482f8f750b8de4ee32.nq.gz
    ├── 47c88e523cf71dc5f3ec825871be4c2551e51aa1.nq.gz
    ├── 4a9eb997436a3d394f5e0e83a796563957ef79da.nq.gz
    ├── 4c2a348db3e7a5b2f6f7e3fb97e8c76163c77021.nq.gz
    ├── 4c71d1dcd4be2eadb3736bca8ce95287ae274a46.nq.gz
    ├── 4cb97da92c1aee90f8dde2a4561bb3d3f7ff128d.nq.gz
    ├── 4cfb64991fd1e2e8549c4473ca790ebc9f14c42a.nq.gz
    ├── 4ea24382eeb4a712221d7fb7cac5f2429f284284.nq.gz
    ├── 4edc4b6fda6433f2cc3733279838a2ad9b77a3da.nq.gz
    ├── 4f4ae2f74e4034638161f7c5da452f25e2601e29.nq.gz
    ├── 4f5f52cd3ab4aca15b6c0fc24193cbbf546c9206.nq.gz
    ├── 52d54f913da4cf97783fa6b1a593f0e264abaf7e.nq.gz
    ├── 5610ade9720eb2426218123cbb291fa8d3e6a954.nq.gz
    ├── 577e9829cd83c22ec6e468b5088aaa89a2193919.nq.gz
    ├── 57ca50ece01794693dfe8e5190595ff983b14c79.nq.gz
    ├── 599b2540c637355b04cc95fd7546bb7fbf673c8d.nq.gz
    ├── 5a6fd30fe60d266ac9feda44a5b469c1ba89ca1a.nq.gz
    ├── 5a9099613e02dd9b2a25d369a4ba8e02b86d7884.nq.gz
    ├── 5b26eea7fb3693f4808a6fff87a901839a9580f5.nq.gz
    ├── 5b591a6a73a26368774bc5338453d53f8fd48a14.nq.gz
    ├── 5bbfd950df7c7f1a63fbfa40581f9d41eff91f04.nq.gz
    ├── 5c9e8344d834292b2110c24d405058ce939ddbf9.nq.gz
    ├── 5d22f6823785c058849176f4c1de29a5382ab166.nq.gz
    ├── 5e344482c8db6b45299509bb044be022c19a6714.nq.gz
    ├── 5f2b38c2d116d800d6e4dc9ff810117084f2f84b.nq.gz
    ├── 605baf91f05e95c5763730b6a5983edd036847cf.nq.gz
    ├── 6147c3414b13efb4d5843bb2a5107f4d843197ac.nq.gz
    ├── 61f1b29170f0c3e68d3f501f3a1bf152cb225030.nq.gz
    ├── 6315a2e0fb4ae3d28ae8f39ab7f1892a07b247f3.nq.gz
    ├── 64cc76293cd43bc65cd043e14b4fba6443e9d392.nq.gz
    ├── 6572c7c07239939e414561ff6e1859410d3f123f.nq.gz
    ├── 67e116e4f8eaa17cdfad037bcb980b012da3ca93.nq.gz
    ├── 680bc8efea9b0b4176925a408076575aa52a0049.nq.gz
    ├── 69f3dc7125333770b45934773710483770de9966.nq.gz
    ├── 6b0b10466e3b77c769150aeae443131b95a6edb4.nq.gz
    ├── 6b6e5d0f7f278a847e56e90e64d50e6769ef6d61.nq.gz
    ├── 6c7ca482109f649f6db88cad15f584cf18fd79ad.nq.gz
    ├── 6c8b101ba220a5fca81d045aacc3bdcdcce4411d.nq.gz
    ├── 6cd204cd42d8b2af6730f352f3a74b27820f486c.nq.gz
    ├── 6e934881768f79401e5471ea771483f3f5df98cf.nq.gz
    ├── 70796310233f6e7b31f46756df2a943fb9a68b23.nq.gz
    ├── 71e6a1f243162ca3dadc0e285cc081d39e1967b9.nq.gz
    ├── 720bf07f1a9dfd6e3ec9fb2724dcc00cd991bc5b.nq.gz
    ├── 73ccde6726fee2093d71b84ef2d450c30a87be2f.nq.gz
    ├── 748fe4a9eb990ae2657f3097cd36a876633607fc.nq.gz
    ├── 76b9ea811da824f473ac3d77b9f2ec442e900e89.nq.gz
    ├── 7818a0b966e6a9077927a9deccd75b03132817b6.nq.gz
    ├── 785db44c0d6307629dead7f1a21116b469837599.nq.gz
    ├── 79f66c3218c8971ea939b1bb87045fada4c709cf.nq.gz
    ├── 7baa0f7e3acfe771ea14a9ee134ec401eb3eaf3c.nq.gz
    ├── 7bbf70e6c8275d7436a73d0e1d2e0631fe7d65dc.nq.gz
    ├── 7c1aa9b206054df7a543d3b0b74621120ec8e3e1.nq.gz
    ├── 7d181952c133e2fa910cb6195ca7005a59685508.nq.gz
    ├── 7d1b8e7349758922465c469dffd254de58595f36.nq.gz
    ├── 7d8fdfc4df544af42ff6ff7bae1f28f99a9d57f1.nq.gz
    ├── 7dcb9cdf1e7a54ad71ce1507e35fe82db5d28e52.nq.gz
    ├── 7dddae3c293e4bd2739229fae5f4fc9f5760e1e3.nq.gz
    ├── 7f1ead67b6e112c306a6379c259f6a7988875aff.nq.gz
    ├── 7f5010014432f1d59807acb84c0e088a624599ab.nq.gz
    ├── 7f96674f3ab886f7e64b80b7678898249383ef72.nq.gz
    ├── 819bf9c78c060ea2372cc0ee8c300b8786f16d93.nq.gz
    ├── 82684669f468dc98c274f387c2ca7ec50d2974aa.nq.gz
    ├── 8272ad70d4f065ba13824e3f4c9cd2529ae5c781.nq.gz
    ├── 835468ca4c8ec309c9204d9051d198b0fee67cbc.nq.gz
    ├── 84c49e56088a3751d2703c31a4d8cac694e69a3e.nq.gz
    ├── 86dadcbda4c67ee8f35ac981e1516ee27598442e.nq.gz
    ├── 872fd6b411911e81a427e85aced9ea4458ff6519.nq.gz
    ├── 87394ecb0c8fb09602b6b978f75fd1a6466c4f73.nq.gz
    ├── 88099fb27f9daf9e873c1a6fcd49ba3096d1ebd0.nq.gz
    ├── 88b3eef01194afe4a671633c6e6339b98a08687e.nq.gz
    ├── 8a3d62589e0e2a550cf967fb45d410f04bc23fcc.nq.gz
    ├── 8af86f693b21ec4f61c425edbbe829da57a881b6.nq.gz
    ├── 8f769279b1fc49601e8581a18cc13a68bc71e120.nq.gz
    ├── 901341f89dcb096de0351a09dc08c64d8015c5aa.nq.gz
    ├── 902de529750f15e27e8560d59960e4e1561e3df0.nq.gz
    ├── 9108df9d88a8686994cc3bbdea7a6492813124c0.nq.gz
    ├── 92cff2bb5a2487f648e61814ef5987ff8d6c8628.nq.gz
    ├── 9400269e260438949e091c27cd1091aa04a4dc12.nq.gz
    ├── 94729cf8d96c3f8a8f86800f9ca56e973a4d389a.nq.gz
    ├── 9483d92a268f1212ded68de48fafcd99803ad4fe.nq.gz
    ├── 94c164f4edb91430da0194e26b720a7595553700.nq.gz
    ├── 963dcf4d80b21620c49f00a1868c1b02301cc46c.nq.gz
    ├── 9733c60c8bbcbbdb9cae8103520e690827cc4bc5.nq.gz
    ├── 976ba0294638950e865be3934cbeee3b6305ffd6.nq.gz
    ├── 9e0fa4494e8cbcef8e5ea695197769d4b2e3591f.nq.gz
    ├── 9e724086937924d3ae1067d934fb683338085779.nq.gz
    ├── 9fb1043bb88b55290ed103929f9974bede98562a.nq.gz
    ├── a3b0e53b08c0666892f41ecf16895b103c21f641.nq.gz
    ├── a3c283dcf8540a3e61bc3bad142e4c8ef6eabbf8.nq.gz
    ├── a4151a8cd0422c322d472fd11c5b5b85945427aa.nq.gz
    ├── a44099aeaa60c6087f5f6441ac2181bd885dd42d.nq.gz
    ├── a6dc5a67559ccaa2a4f134bc8e1f3ae567b5594a.nq.gz
    ├── a847c5c7b9829580cbfa3cc1c25bea7ed9e52133.nq.gz
    ├── a91489e52c6fcfc3a2453beae9362bd1f718a284.nq.gz
    ├── aa8e7dad456b1b7cf7ae944a955f647af6c551a7.nq.gz
    ├── ab0b186072933eb2bb4c770b4e78183c7b4d3b29.nq.gz
    ├── ad1bef38961b1575e7870e9bfce3fc7aabc2e00f.nq.gz
    ├── ad35ffeefd35bc512b99110143533c64241a2269.nq.gz
    ├── af2023a1835e71a1f62fba7c569c42ce95eb48d1.nq.gz
    ├── b06c33c3eebfe5aa53bb263df86bd9a2cc5f91d8.nq.gz
    ├── b1132fef133a5f11c679fedf7593f08306253d96.nq.gz
    ├── b134db1182f1705b0855483632c7d3bacf9110f2.nq.gz
    ├── b19783c05b2a505dc9c6dcf2bc42f4bbbafc0ed9.nq.gz
    ├── b20921922509f86ec6168dcfa0b3adebb7216546.nq.gz
    ├── b29295ef763d0d2b59074d9ad4140c8b185150ab.nq.gz
    ├── b3dcdd3090e52a3d94affb00a40df2fe8a56d4ba.nq.gz
    ├── b486018672ada8c2c170f662c452bc7c23e64e0b.nq.gz
    ├── b5187c6c0fc026945b19236df7ac5b743684c431.nq.gz
    ├── b55e780ee1999887a19d1f4a62faff19eefda787.nq.gz
    ├── b5d0f12ca64ae8b67ce4a2c6863ece6b6cca1f78.nq.gz
    ├── b6b5a19869b0da5391166068ee875aee23d32048.nq.gz
    ├── b86cf495b1514f24f906ba8743d8b5440798f663.nq.gz
    └── ba0819cecd5388ed4c84bec0184fbbab93d7d04f.nq.gz

8 directories, 200 files
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
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
