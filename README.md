# Repolex Knowledge Graph of stanfordnlp/dspy

RDF knowledge graph data for [stanfordnlp/dspy](https://github.com/stanfordnlp/dspy), parsed by [repolex](https://repolex.ai).

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
rlex download stanfordnlp/dspy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c7e9752debcce5715fee62cd5f1ae538c14d5ce4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c7e9752debcce5715fee62cd5f1ae538c14d5ce4
│           └── chunk-001.nq.gz
└── blob
    ├── 00d0239579b4505ed28243fd924d249e8b710cbe.nq.gz
    ├── 01135cbbf7336def35881070fb0c702af1cb34e6.nq.gz
    ├── 01883d6ffdf139a08ba938bc2c2ec80656389a98.nq.gz
    ├── 01bfc1e6416506836774e4bbde3f2667f819f94c.nq.gz
    ├── 020f21d50dd07d4e60da1be3cebbafc7eae02d4d.nq.gz
    ├── 024f5f4258a2907991fce3e4a08e8a366733e3ed.nq.gz
    ├── 0301513578e6beb5c8327afbadf93253c6c455d4.nq.gz
    ├── 044204156e56cd171072a0ba78f7ea9a18c1c1f0.nq.gz
    ├── 0545a50184ea89895fd50f1afd742539af54cba1.nq.gz
    ├── 066dad72982338021d94a622d6eac8342a26ec43.nq.gz
    ├── 06f30f042d8ccb883401de2f94d7d89e4f7146fe.nq.gz
    ├── 06f3b0a0054c110ea7dd89ee7f5b34ab92c4c3fe.nq.gz
    ├── 070e6ca185fd73cc9276f78528b1da9efc7fd3fb.nq.gz
    ├── 072451b859fb79d99927e856d5dcd0d9e6c7c406.nq.gz
    ├── 081978c41596e06b5f24543ba405e98ecb6850b9.nq.gz
    ├── 0865d5f3ff498c97f7458e967aabd5e082751970.nq.gz
    ├── 09c4e916aba899dee0780d1c69ba39bcd5b21fe2.nq.gz
    ├── 0a36260069b86b3b47a98f5543adc6edb9df2670.nq.gz
    ├── 0b5201ea90da2b2490b98835c7124ef0e1978e15.nq.gz
    ├── 0be5e9a73225305e81d97477278d631b1e168500.nq.gz
    ├── 0d0601fc0e0e5c275ee4d40d2cfed101fb504530.nq.gz
    ├── 0d25a3be630f9ec26dad51897ad6db8311a72c9e.nq.gz
    ├── 0d2eec91a0bb9ea941ca61bc9d8e75ec05aef1e5.nq.gz
    ├── 0d7c6f6883a6f9c1b8c95cecadc3e0e118637c4d.nq.gz
    ├── 0d88459b672cb50e48aa41e5bdf550b74d67d6e6.nq.gz
    ├── 0e4cfefa90f1356941b37c7dd14d54d793aa0219.nq.gz
    ├── 0fe432edfcc0407d3802538480ea73614253d456.nq.gz
    ├── 113ad66b6089feba6a986c6d2d0c663d8a4f3db7.nq.gz
    ├── 11eef53e50d11476fa7306794b1cf379e9eeb92a.nq.gz
    ├── 13a55727f22fddb15ad0d81174b42d7462ecf9ea.nq.gz
    ├── 13ac0cca9ed0f7867b0873dfba0ba4c7aacc7fc6.nq.gz
    ├── 14cb00e1c2dd2c6bdca016bbdd34ecc5a7caf993.nq.gz
    ├── 15007314090a02e526e3656a1f46249ffe3f656e.nq.gz
    ├── 1529d7e6a8f6732271db872bf73b034c48864dd7.nq.gz
    ├── 161ff372029c591ddeee027973cfec43986f71b6.nq.gz
    ├── 16a096ca2477b823fcfb12d97f66acd2bfb47dc3.nq.gz
    ├── 16e6951409ac3c93667ded3d5047f3599596046a.nq.gz
    ├── 1771b360f1fceaadb9e9d5d9f3aa9e004bf993d6.nq.gz
    ├── 17d369d724807da7e5205b92cb32738fbd42ba79.nq.gz
    ├── 195fc31e3bd6cc4bde96c0bef0d4b1ce7f234fbe.nq.gz
    ├── 1a18428e86c349f105db10e0ff74e2eb6b54e5f6.nq.gz
    ├── 1aede5ef2028631af009d1973cd724d369035dd5.nq.gz
    ├── 1b1f6fbbb9e5dabb06b831e346c796b7616376bf.nq.gz
    ├── 1c6a2f3185be73792f0ecbbb6747702ea4ae2b93.nq.gz
    ├── 1cfecea07f22b7fd82913668273824eb51cab990.nq.gz
    ├── 1d2cdfd008f0ebc6d6c841011d975d4f85f9b70c.nq.gz
    ├── 1d30800f8a25066f93f5bb674d5201dda7adff22.nq.gz
    ├── 1e0e6aaa79309e67e01475e627d90ae7c94e267a.nq.gz
    ├── 1e102dc8b5464d9ab374be47d5e3b58b07d8a80a.nq.gz
    ├── 1e18cdfec8d82889a1211026c21c6de7bc3eb94e.nq.gz
    ├── 1e8b93172a182f30828e683c3a6f7b82b877c4ac.nq.gz
    ├── 1f527004b7109a6fcc6c2da41bdc81416b37c6a3.nq.gz
    ├── 1f7aa15df88bf63b709cfd1391384b086bda5f54.nq.gz
    ├── 1fa22e161e8c48b840bb9b59e6f2424da036485a.nq.gz
    ├── 1ff44d2651136e301b9e144f3977f050cdaeab16.nq.gz
    ├── 2003f7ab6c4afb488f8739e99a81eaf535584cb1.nq.gz
    ├── 20124afef59d3312e0727733c29f24d0a4285fd6.nq.gz
    ├── 207b5efc3d2711ad906a8ad58039207575b4df32.nq.gz
    ├── 20ad053944cc3985c31f4de170140694d551cf6b.nq.gz
    ├── 215a1259c4cc0c9d269077d311d64bc5cd060d69.nq.gz
    ├── 218d77bebb74c9f1049f591b4ef0a4adb6dbfc62.nq.gz
    ├── 225efff90f1bdd2ff260b291db7d5e01878ceaa2.nq.gz
    ├── 22d5c034807da59b116a6e45766d124ee3ac39e8.nq.gz
    ├── 230133c8b704c22a71dcc8a240a25ac7fe034438.nq.gz
    ├── 236869104f0845f2a91d75b9c35f59e13732df88.nq.gz
    ├── 238500021af7fe31a804b62e29b77e74eb5818fd.nq.gz
    ├── 23aa42d28d0adfb83c0cf4e835686e34437021f6.nq.gz
    ├── 23d88d44695a88b5c3fc50b13fe3a9fdc6787664.nq.gz
    ├── 24e8647b55534ebb158f29a5f7f4e5c17073d711.nq.gz
    ├── 259464a28a724b0081e4785f44b5f252945f76d4.nq.gz
    ├── 25a46241c1546a7ae885f2c594c8a470ef04be28.nq.gz
    ├── 274e806350d426f40c4c214fdaec3701d22f7c36.nq.gz
    ├── 27707cc0c5a414d9d7825f58a13146d5d7711b4e.nq.gz
    ├── 27a70306737fa0a04b9197d95aae87ed3d737b8f.nq.gz
    ├── 288364964a91a29c1e28f9d63e3924aca8cb1aa5.nq.gz
    ├── 2888e4dbd2c7c5903501cffe5a9ae0f88f32be34.nq.gz
    ├── 289c1c1f4f8b3b0dbdbdf35f94124181b20c6a44.nq.gz
    ├── 28b7597806f22ee9681b9c781b52c8bfc5e69e8d.nq.gz
    ├── 28c70db668ed1ab5e9ad1375b5883f3bdd1dfecd.nq.gz
    ├── 2908c1435ffa20ba169595d530b922ea79fa9199.nq.gz
    ├── 29a0a3e2a4c5e4e7300fdb8af62422390d392f44.nq.gz
    ├── 2a039354a447058224730cf9ab67b347f9622fc1.nq.gz
    ├── 2a1508dd17d78ae1782c51651678f114480358a9.nq.gz
    ├── 2aa63c9d592d8fc8873ec4d4b185b0227af0c26c.nq.gz
    ├── 2b3d468072cc20f933e6eda2eccdcaeab5cb9fe3.nq.gz
    ├── 2b3f891e9a883a14cd736ff1b17640cad1271cbd.nq.gz
    ├── 2b85a55db8f592dd7074b0834749fb2af39abd58.nq.gz
    ├── 2c0786b1b8514e0f1ada6582e56686d676a0e7b0.nq.gz
    ├── 2cb85c438a9e0b1c1bf469186fec00c816425342.nq.gz
    ├── 2d400e1f5655df013745727a54bc2cb2a4710b6d.nq.gz
    ├── 2dc45bab839e7c1af5c85b7f877dce42aeef6668.nq.gz
    ├── 2ea2d7b68fef5bccf35aa3bf3babee57a3ff4926.nq.gz
    ├── 2ec8ae5bc732896fc00440c91c6ccd3d18c16830.nq.gz
    ├── 2f4af4649dc2e525ae6eaa0dbad028a391626769.nq.gz
    ├── 2fcbaf5240673d66baf0e9750695cba1df86c9bc.nq.gz
    ├── 30668c38bbb6633b5d8d3d01b0f911cc828bd85d.nq.gz
    ├── 30cc3cdc7f5e05657311c3e69e3f256a2ab2d794.nq.gz
    ├── 31a876c59439bbab5f104008c511495757168450.nq.gz
    ├── 31c491fcb98a6e0ff3594c60aff9cd5b754f21a2.nq.gz
    ├── 31d808695fcc31c9e4b8d9571bd4cf9327d90875.nq.gz
    ├── 338b1ac52b05a9b8fc67bad3a4c362fa919d59a2.nq.gz
    ├── 350bf0a9c8c8a907ba8163d8014a47e35d95e206.nq.gz
    ├── 355ba25a328d14f6d2227f4a371dcb39c697ad53.nq.gz
    ├── 36b9652ad155b4b368963330fa5123f084f193d9.nq.gz
    ├── 36e5ed963caa45d574dec11ce2af397120b70ac9.nq.gz
    ├── 3738fd8922f177f4b1190c1afc5f2a6448d2b730.nq.gz
    ├── 37c569d458836314ead2ef7d0238729ee37878c9.nq.gz
    ├── 37eb96c4277a3e9ef77443984cf33029b2444d8e.nq.gz
    ├── 387876a823b2a7e7daeb4719249b6424fd483062.nq.gz
    ├── 3919fa14591e59f2feef4c4f47fb0b4f4ca5b42e.nq.gz
    ├── 3afe4029bdc53a631d41eff98e4416b1f2f26794.nq.gz
    ├── 3b5b717d0961c42468617cda7ecf44cb853bcec4.nq.gz
    ├── 3c0041993ea68b80739b098d3a3f87972bdbd985.nq.gz
    ├── 3c2a7f75e63641a5feb405c88854130105acc2e1.nq.gz
    ├── 3c3144c53ca5a90e9ddecf11e59fbcb38c681b7f.nq.gz
    ├── 3cdfb63d3fb92c34db6fceadb014992f0a0fc91c.nq.gz
    ├── 3dace8195f21cddac19fc05b389ee2804a5728d4.nq.gz
    ├── 3dde1852dabf63bf11e7edf6fc939b301f5e85a3.nq.gz
    ├── 3f04bb3c1db5fbf32626b14b1d0f6712d0ce0963.nq.gz
    ├── 3f93f0167d87c77e0246148a1440765df3bc5f5e.nq.gz
    ├── 3fb1f8edef842ba7bf377faed680925a72bb63d4.nq.gz
    ├── 40e4518e07e26550a0050c35402131e4e7a979a0.nq.gz
    ├── 40ef22ecf3f134e80b9281778ff29f7829c83043.nq.gz
    ├── 41ca3f177c52ab81db6ac82714166124c01019c7.nq.gz
    ├── 4257c7c9592c5e143c1b00a79bd3ad36bbd3c501.nq.gz
    ├── 431c593bba34da4c5348c3e1fdda99bfea7da635.nq.gz
    ├── 435a47aea89eacde096283a1abddc97f009d44e3.nq.gz
    ├── 44392eb86f284bd68f8af07d21599ee60e6d7adc.nq.gz
    ├── 44461c22a28708f20430027dc7bb947a5f93e2d8.nq.gz
    ├── 449bb742d3c3cdb00899a4a2aff06ec22fb60d8e.nq.gz
    ├── 44d18f6aabfcde8d3d9422da5be5d03770f869a4.nq.gz
    ├── 44e74f5d6f93931fc3d22f3d4c17a2b7391223e8.nq.gz
    ├── 450726ebef458f24fe3f31d17bf1c1fddb1fbea4.nq.gz
    ├── 45113617a2148051b4524482c5e4ffcdcd42f3f9.nq.gz
    ├── 45f3236b2d5e132b36c143cb081316b2552fe62e.nq.gz
    ├── 45f447e50cbc44b648feb92e88c5900272ed1309.nq.gz
    ├── 464090415c47109523e91779d4f40e19495c9cf1.nq.gz
    ├── 46e934a8cf24f31faf0e504b1ca3d1573739bfcb.nq.gz
    ├── 47d278851f13b4240ed275f1c82a9256d6d25e00.nq.gz
    ├── 48bd6f6322abace825979f536b90a02431a2c99c.nq.gz
    ├── 49332a8038e08813c14fb1d2f577ab991a5248fe.nq.gz
    ├── 49e9c45aa4aff9c2a56f054b38582db849085e6f.nq.gz
    ├── 4a67b268aeaa2c925c58c32eb20057506ee8afef.nq.gz
    ├── 4acf9e9f1a3ef9e3059e61fb3335ab65023e92cc.nq.gz
    ├── 4af802f6e3fb3ddb099aa7727491ca1482e2bfe9.nq.gz
    ├── 4b12c142ddcb24a025f833291b8e94f76bae8350.nq.gz
    ├── 4bdf4f1a52c0dc5a13a95f3239f4b1527113bf94.nq.gz
    ├── 4c5c4db8f34297603dfec9577c2d833b3da4cffe.nq.gz
    ├── 4c5d5798911addbbedaba73c77d25dc4a7b88984.nq.gz
    ├── 4c8227a1aae3cbac3b388c8c91f9ef7cbe527b04.nq.gz
    ├── 4cee3eb49cd8236e7d7326c3f35791ea7f8ea2e1.nq.gz
    ├── 4d3c424789515b8fdd8b5150ccd67bfa7719406b.nq.gz
    ├── 4e12cdb21caf1493cca4bf8e005b22143b548fa4.nq.gz
    ├── 4ea156459c164d322544631704133ea751436c5c.nq.gz
    ├── 4f32fe9fce6fda406f183033975b24017c6fb7a3.nq.gz
    ├── 4fe7a8c22509312dbfd34c4218142123c3b99324.nq.gz
    ├── 50433a0f2eadd7a3991728acaa8ca35c188e8357.nq.gz
    ├── 5057cd92fca1313ffb2cb3aea79cd08e53c39f2b.nq.gz
    ├── 509d5c6c2f2882b9d369bd39b1f37079390f6ed0.nq.gz
    ├── 5105675efc2de7dd3cd65ba9f06106739ae6073d.nq.gz
    ├── 514f4acb264607eaae35043ee4290d3d47882e1d.nq.gz
    ├── 5302d259d2f86c4e9b6331b046831fc9c4de1644.nq.gz
    ├── 543c28323dc716d6dcdff71b72b31539fb44dbd1.nq.gz
    ├── 55ae12b029776345ad5375b960142bcb20dee83c.nq.gz
    ├── 56b0825be25f18abf4050cb943b9bcbffae49bea.nq.gz
    ├── 56d9790f845ada304c384a35d435b0ad6d377968.nq.gz
    ├── 57e1f7ede3224ad8cd2d4760c6fed51a4152b79b.nq.gz
    ├── 57eb2f4d0f65dcbdde4a84b62d2114b76fed6ba0.nq.gz
    ├── 58aef770fdc375b3080a5dd1c4096d0584fa918c.nq.gz
    ├── 58f45b41202f548f3249c96c1c3ee00f9f5517c9.nq.gz
    ├── 599764822fc47a112f158ce1d8d4346d4ba3bfd0.nq.gz
    ├── 5a1ea97e6071ca54cfda07cd49aedd6577e2397d.nq.gz
    ├── 5b07e462ef9b4777aad3022d10fd25bbbcd84c7a.nq.gz
    ├── 5b0c0c470ae9a80d6d8e5737c084001a26dfa29b.nq.gz
    ├── 5b6fb6d6432e4df6a0cf7eea59241edcbcd0519f.nq.gz
    ├── 5c519913b6e376e06cab96c14bb91d18221af92b.nq.gz
    ├── 5d247b43575bb3da213f070fd383900f811fee65.nq.gz
    ├── 5d53765376b9f068d9e0401ac9d60157d6609413.nq.gz
    ├── 5dd889dd9f4b853ea594d04105b08bed32260476.nq.gz
    ├── 5e97bb0dd7bc557d0ccff005b705bde09035dfa2.nq.gz
    ├── 5ece39728e0dc3befd4ff2231003616cd5816d04.nq.gz
    ├── 5fb4e4325e2ff59ca7f9ad9fa3115a95d0d883cc.nq.gz
    ├── 6035501a1218416a8aa5d6e45d03816a79249348.nq.gz
    ├── 60f14f6109445c903207065a3ddc17a72042abfa.nq.gz
    ├── 613e20b2441b6d4c0af08a6a489cc9cebf61b56c.nq.gz
    ├── 619b779a93f62c6ada709bf20964107e59fd664d.nq.gz
    ├── 61fc2e01092fbec19cb96a45c09f775b0312947d.nq.gz
    ├── 63044a25102155ed17a4e621ccd5d692dfab046a.nq.gz
    ├── 63987fd0ca7b4612178114f2fe13e2b690981fce.nq.gz
    ├── 63d24afae2ddf361d88e9d85dfef1bea633bcc68.nq.gz
    ├── 64ccd15656f1c9b752d053509b7340eacb5b6c4a.nq.gz
    ├── 64fc2ca196556474ef2d0284bbda523390085003.nq.gz
    ├── 65bfed154a2c56c9f875bdb2e2193f1f5700d764.nq.gz
    ├── 67432fdf2ae916838d721f44a49cedee139d5382.nq.gz
    ├── 679192ef7f447f05dcf55cf38ea02d042e1ff906.nq.gz
    ├── 67af084a2f0f31742488fa4eee2fc21f597dcb5a.nq.gz
    ├── 67daf685d5690b50fae91ef50f9c3663f21decb3.nq.gz
    └── 684bc0629da9be9759a94d59b7cf89300523ea9f.nq.gz

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

[stanfordnlp/dspy](https://github.com/stanfordnlp/dspy)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
