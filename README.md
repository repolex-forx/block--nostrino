# Repolex Knowledge Graph of block/nostrino

RDF knowledge graph data for [block/nostrino](https://github.com/block/nostrino), parsed by [repolex](https://repolex.ai).

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
rlex download block/nostrino
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fbd28f7195de63c283cfb57807884559cca81a4a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── fbd28f7195de63c283cfb57807884559cca81a4a.nq.gz
│   └── repolex
│       └── fbd28f7195de63c283cfb57807884559cca81a4a
│           └── chunk-001.nq.gz
├── blob
│   ├── 00b6b2d32f4d0f6ab30a182ee57e63f1fe8a7950.nq.gz
│   ├── 02eea889a981dad6bf0dca09f13682f6ee5f820b.nq.gz
│   ├── 04fe012ef624d0e51e75e9023d3063a5cfde8abc.nq.gz
│   ├── 0541ff0a640c6e0da11ff06246736004749b4a75.nq.gz
│   ├── 07ad7d83216fc3893ac6eb5eaac7671d21481c6a.nq.gz
│   ├── 08838994e4956fca6f80c8663108afcc1a66736d.nq.gz
│   ├── 0887a63de867361977f4bbea2dcfd616d3f03d21.nq.gz
│   ├── 08f42e793b57ed543d27f1bfdad3d0c4809336b5.nq.gz
│   ├── 0cfd26aff6809fd163c875625b61cc4d2b944ce5.nq.gz
│   ├── 0f5bb1fe7da7a3118a6ed0033765a75e305e1dee.nq.gz
│   ├── 13420286581a07280a7f674a36559981bd713781.nq.gz
│   ├── 176ffa9146816e3c0e400f3f09d9c03cf2229a57.nq.gz
│   ├── 1890d36671813fcc428436cc204dc63a067f193b.nq.gz
│   ├── 18d6f70c8bd47bff1073041d700cec755f63b905.nq.gz
│   ├── 1a6f7fc8aa834daecc554d421b88ecf10cca1ff5.nq.gz
│   ├── 1c2f4294192446b4d882afd8308e2e7f0fea63a3.nq.gz
│   ├── 1cef34401be0e8832317c5d71cef2c07e4c76e98.nq.gz
│   ├── 1d86be019a0d0e9f84420441f793f53ca733a439.nq.gz
│   ├── 1e750ca852aec49e6b983d3b1a8d2f56485ac483.nq.gz
│   ├── 2407d58ad15bddd3aa7b0b6b7565bdc2f6751bb3.nq.gz
│   ├── 250a42a5c5715b2436f270ccef915646c531e373.nq.gz
│   ├── 25d229d7d40633cd431645b9a50f865a9325f1a3.nq.gz
│   ├── 268caaa7b0b6710a3dfa9172c1fbfda1a7f8fc87.nq.gz
│   ├── 28ee7d6be95f3a1bee5d7147fdeb62d12e64f24f.nq.gz
│   ├── 2a31c82fe332b3c2f55a143cc4233361cd03c62d.nq.gz
│   ├── 2d81087bcf895469fe0d2ef9f5e8059dc55aabc4.nq.gz
│   ├── 30953e46bc4d65532553ad9f5bda19f078dfb077.nq.gz
│   ├── 32d63a58ab2e8b6e3f45a0499f4de467db818e73.nq.gz
│   ├── 33b73350ec9463f074164d13a02e5bb9006630d2.nq.gz
│   ├── 369aa9b817dc6a19971f8148b4b4af24a590b1a4.nq.gz
│   ├── 371a1419e9183d50ba83f377eef4d1ee456e6633.nq.gz
│   ├── 378cd58bb2d6c048d9196facdd836b514b562cb2.nq.gz
│   ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
│   ├── 3847ee044fecb0433347110e5558a186b3b75d11.nq.gz
│   ├── 3dac2bf9906b6fff0a384128356880d87c25710b.nq.gz
│   ├── 407285171ba8fd1df0385ff598c548409714bb82.nq.gz
│   ├── 409b1d20023f3cd7b5d9b385cd602b1a03d0ed72.nq.gz
│   ├── 40b138d67db6034197dfb3d71e89661fef29c46a.nq.gz
│   ├── 43ac940f9fafb152e608e43b6874ea1282d8c36e.nq.gz
│   ├── 461a1855ce2fe3a21daa577a988f9c1f5bc1b124.nq.gz
│   ├── 465dff106707b67becd69951443160ce49ee4956.nq.gz
│   ├── 4f1d177726a13d74a3f447d9aaaddd91ec4d3c23.nq.gz
│   ├── 52104b339267391805e70d7c5821d654a3878a15.nq.gz
│   ├── 5450678c6b695ef6a9df5d49fb315721d18f7439.nq.gz
│   ├── 5a0cdf8feb4fc3da67ff63ae4f8a72572acbc824.nq.gz
│   ├── 5e1b533fb8bc0541f59b9602b17afab6860d32ca.nq.gz
│   ├── 60068ed2e4423731e87300b0eadb6e098ca3f589.nq.gz
│   ├── 60111f4d8000b728e1dd2a04260b5bc12e030132.nq.gz
│   ├── 622b256edd97fb4c961728afa4a7da02806045a9.nq.gz
│   ├── 638fc7ba2a45d6c7d63cb3d4e74b531bd4d83ec0.nq.gz
│   ├── 6857cb02b96bf203447f21c765194fcd2ffcbb44.nq.gz
│   ├── 6b10a02b0218bb1fbfeadcbeb4ddff3ae4b68fdd.nq.gz
│   ├── 6bbf2b831bd5b50c9edac8bf9a9dca328969b538.nq.gz
│   ├── 6be86bc9aff5ab1003594e48f040f5cdfeab3304.nq.gz
│   ├── 6c366e84f7cc53f174a805b2b0738d53fc0ae2df.nq.gz
│   ├── 6ea5ace7cb346ac786bf7aff053a8a89796c2581.nq.gz
│   ├── 6f2bc8c4cea3596921fa84bd6039bf94760fd68c.nq.gz
│   ├── 702f044fe86d34d4b747f4503dd273e2f759a6c6.nq.gz
│   ├── 704bec819e4f23ead1ff965a6144e1391551762e.nq.gz
│   ├── 724750fc11c12313babcf73aece0bc877fcee4ce.nq.gz
│   ├── 79b7e5e6adddec692ac5b21fdc68036c4e62fd64.nq.gz
│   ├── 79eb5fdf9aeb128188ddfb6ded8bf3ab18a48170.nq.gz
│   ├── 79f856e06bb8f8bba4d9e8ea27c73b42c7ca3c2c.nq.gz
│   ├── 7b002d7c985184515a0d38207b51a54963a0f76f.nq.gz
│   ├── 7b29cb9040e09fc0e2f6f36449b11e24a364cb4d.nq.gz
│   ├── 7fb6c443050a6ea0262713d193a8c70ae935a43a.nq.gz
│   ├── 7fef769248e85eab6c828b9f2f7b802296cddadc.nq.gz
│   ├── 7ffba196f712b41adf50bad4f5d2604d2de37830.nq.gz
│   ├── 834e388a2bab8884e4d00f633335eaa705a75afc.nq.gz
│   ├── 851960f0b3da77eba339cc9e2066a4af8cb82a1f.nq.gz
│   ├── 85958c0167957652795f258a7cd9982b9610c83a.nq.gz
│   ├── 862d3464278de1f131c58913fbe966cbfebe6f2b.nq.gz
│   ├── 8c9894ee2c5b9d57c051168afb18467432ba10c6.nq.gz
│   ├── 90f40ed15dafb47e938b14fdef0f3218aa70b060.nq.gz
│   ├── 9105312c0a5940e6d0d2b9d8deff42804eb8c921.nq.gz
│   ├── 9668afa2e98ff367a581e0294141637fb8f58e93.nq.gz
│   ├── 98389b88cf2e2a300015364edcbfde23738d92bd.nq.gz
│   ├── 99ad03344554dc16e62cfd5728c73626b53a70d6.nq.gz
│   ├── 9b32251497bfe050221ddb5a8fcffa94b1375d56.nq.gz
│   ├── 9c45e22cff3a88421919ae42f49c5abed705534c.nq.gz
│   ├── 9dda8567785b562a9f9dcabbdc8e69d8054af65f.nq.gz
│   ├── a3bcb3af6844e7a4601a32e62eea9aaa73bb327f.nq.gz
│   ├── a4a00765f5ce361f2316e6b21aafa4035b6f9f73.nq.gz
│   ├── a99d42fab6547f4004fc1b0684a4565b20297099.nq.gz
│   ├── b190ab39ed183405e35285622726343b168912b3.nq.gz
│   ├── b1b4b1863bca4591b2e4fe5258e5dca7a3981e44.nq.gz
│   ├── b2259b55d2316d13bf36fa91adc59f1ade0d61e6.nq.gz
│   ├── b232841734fd7cf13dd42dbe6e623dac4b20b9d5.nq.gz
│   ├── b4025f2936a1c4c52f5890c02b313dca41ab3838.nq.gz
│   ├── b81f108e91148d0cb556911a1d4bf61f1889ec6c.nq.gz
│   ├── bf67a9fb0480911643efc9e9af8dc7070d13c316.nq.gz
│   ├── bfeb5c2b65aa216b071cf2d88608d5d44a63e37b.nq.gz
│   ├── c179d697b05066a94180beafe8934a705fb65257.nq.gz
│   ├── c50e7fb35c98a5fab391432d6a54ff4ad201deda.nq.gz
│   ├── c718a732e84c0763d582407d503b24f93d548549.nq.gz
│   ├── c7961a85b2e7684f20cfb9c3caed6125a01b2475.nq.gz
│   ├── c7e9bb7db53fec9621b5063106c21e96c3ebc364.nq.gz
│   ├── c8e710282b7c00b2353a16d64da7b8f85881b044.nq.gz
│   ├── cd4326054372abea8251f659cc894fbbf75fc291.nq.gz
│   ├── d03f08235f3bbe8850509027776f278e76b7a936.nq.gz
│   ├── d36b5e03262669e76bee314f7031048804828974.nq.gz
│   ├── d410df67dfd811b66b7f9fff2d14811db7aa0994.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── da082846910bf98c7e6f527d4fdcf64ce4435233.nq.gz
│   ├── dac5e3dbae9782169252f2c1d95d160a53ee8a97.nq.gz
│   ├── db515acd54dd06d4fe9e2aac1688ddbd7ff6d544.nq.gz
│   ├── dbba01f43e072ddebc5bdf9570bbc47648fec088.nq.gz
│   ├── deeb5198a69f66c34d2e000a760044caf23537c8.nq.gz
│   ├── e2caa299471df703584a9782a1bbe57c1ffb41c5.nq.gz
│   ├── e5e4cb2c83f487e5851cea43a6cef1b58396195a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e889550ba4cbc92a720527042e5f6e7a303bfcbc.nq.gz
│   ├── ec2dfd82923cc7f07c379945ca3be65f20ee989b.nq.gz
│   ├── ee84beab95f74c66cb4921061da626d6ad0d279c.nq.gz
│   ├── f2278332e28c51dc2fefc258881c1afb8f87fde0.nq.gz
│   ├── f3bc1afe085d4d7671a5af521f27d6cd95bc6b02.nq.gz
│   ├── f5fdfee4963d78a5bfebe4ac1d56c995b4b8eba7.nq.gz
│   ├── f7a75b07a1ee724442a1eaff83c36656d582b0a3.nq.gz
│   ├── f8deccb967ef19dc394503f4a0fe42f4e638dbbc.nq.gz
│   ├── f92e81abd5ce99e2f09783395065b2b5b37a80d2.nq.gz
│   ├── f9597689eada238ea3a854f8c0b6321846c21153.nq.gz
│   ├── fa7ffe29b16792d69b48e40c65db7c3fbd0ab235.nq.gz
│   ├── fd26157234f3b2338b05409da53162ea52f57f09.nq.gz
│   ├── fe28214d3352b0ed40820a4999317694c8b1ef57.nq.gz
│   └── ffac59bffc27c22f95d74d932f2d02fddb38e561.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fbd28f7195de63c283cfb57807884559cca81a4a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 134 files
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

[block/nostrino](https://github.com/block/nostrino)

---
*Parsed on 2026-10-02 by [repolex](https://repolex.ai)*
