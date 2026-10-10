# Repolex Knowledge Graph of pypa/flit

RDF knowledge graph data for [pypa/flit](https://github.com/pypa/flit), parsed by [repolex](https://repolex.ai).

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
rlex download pypa/flit
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 75b1c909d587c1ff5e0fd5f3df1046f74ee249d4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 75b1c909d587c1ff5e0fd5f3df1046f74ee249d4
│           └── chunk-001.nq.gz
├── blob
│   ├── 00c36f2b7cd877001c81b809de9d4849ed6a4b10.nq.gz
│   ├── 019de1229ed1ac54b899ae47060bd98cd8981324.nq.gz
│   ├── 0460354a13eaa5e11a1d5f24cb47d7afc3d9ccd4.nq.gz
│   ├── 06378409fd0be7e844d225948fcf97569b6869cc.nq.gz
│   ├── 07978d8bcd5a0c001c6d87266df93ac4a3aa7a6d.nq.gz
│   ├── 09853f39b87e4a90f1da58313d970ebc50192fbd.nq.gz
│   ├── 0ade0456fd24fa13b572e50e28cd6886a76f318d.nq.gz
│   ├── 0b579f352c67fb351b206e37fe240998e93f2fd2.nq.gz
│   ├── 0c57d80128964086f4205f3a816ae39693814401.nq.gz
│   ├── 0d5e81c19dc435114d166d76f647058f82283e2f.nq.gz
│   ├── 0e8fc311b0ddc032ce139b2c15b65755a8f2ed34.nq.gz
│   ├── 0f36679f86bf62467d0219a30fd1e85f8b3f1695.nq.gz
│   ├── 1068675f3652f70bf028e05c5fa80ac19e83c260.nq.gz
│   ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
│   ├── 1337a530cbc1bd7d20aee2d80f1f174a9182417d.nq.gz
│   ├── 147d26ed6804ce1d5ba92df2c2cc4d6848f779fb.nq.gz
│   ├── 165fb1d655276e44e7d02f45fb868e16ed18e6f7.nq.gz
│   ├── 1709d1719198666e7c1e4d54506f0e4c83a9bdd0.nq.gz
│   ├── 1882615a15e22e07600bfa25bd0f0e2c679f7bc1.nq.gz
│   ├── 1a897d6a2e3e7db79f4e8fe6f3a8ca7c0bb1c629.nq.gz
│   ├── 1aed3a71063a7f39f1db012d44be00c4acd43c6e.nq.gz
│   ├── 1bd2e2d8ce78725593eb78ec00658203a4830b5e.nq.gz
│   ├── 1cb066e2bb9780310523499de1ade65d0ef88d70.nq.gz
│   ├── 1cec17da41267b45abf74999d707a5362884bb0b.nq.gz
│   ├── 1d1d39b9ae997674512d268351e6e986f13b41e5.nq.gz
│   ├── 201c1089f5c716c9ea98d040c65cd02e03a75a78.nq.gz
│   ├── 214cd17e60b4cc20b40bc0d7d4df2db2f4c0bdd8.nq.gz
│   ├── 215732a4938dc01373902376ba6aa9c3a3eb3102.nq.gz
│   ├── 27dd4ec3c544fd701abc4d70b0dae0e5ca42326b.nq.gz
│   ├── 2894fc890087675ad1841e74a6b9a8b261d044f4.nq.gz
│   ├── 2918743482cdc35a8161bdd0d9322307e16bedfa.nq.gz
│   ├── 29524eba32ce958b76992d5746891d5398071984.nq.gz
│   ├── 2a4401cbbacde938ec0302adaaa256396d7fb9a7.nq.gz
│   ├── 2c72d509f7d03241ef769f8fbf264e32732fefeb.nq.gz
│   ├── 2c97eebfb48d9cdeb31930ff66c4d2d64a033313.nq.gz
│   ├── 2fd829600da53075ea6b77152e1da92fe20bfda8.nq.gz
│   ├── 300ff01a943ca2151a29016061ee0ab8d1ab008c.nq.gz
│   ├── 304360caba487e6f7b707b5aa96774f85bf17b77.nq.gz
│   ├── 315902cb059d4c482c53344cea41688df9ba5878.nq.gz
│   ├── 31d1b5d38f2bccf2cf4d58729b9ac128494df9ee.nq.gz
│   ├── 31dc06ac728253ed0b8e14b03fb254dfdb02a35a.nq.gz
│   ├── 36b49196fb71caf019ec11dbf21cd0a95680135a.nq.gz
│   ├── 379b74799533376da7b4c6dadccc30464ba2831f.nq.gz
│   ├── 38375b5394c655105b9de1c322de36eb35be6d31.nq.gz
│   ├── 38b32befb2412c62a2a91d20aead6fd54f0b520a.nq.gz
│   ├── 3a84af2c0fc60f1958c7f1a8eb6420ade50a4630.nq.gz
│   ├── 3b0864d146d28bdc54009a1ae02d1de293acd9e6.nq.gz
│   ├── 3e621e69bde43e22a6c5c3c004404a6838499ab7.nq.gz
│   ├── 3eeb3c36a170482bec53c4b7f105fcc3bce719f2.nq.gz
│   ├── 40e8ed3f106cbad5a15181ee6a68ddd4a869f6a2.nq.gz
│   ├── 424d4dfa97ccdc1fe2eb9dc9aa257d745121dace.nq.gz
│   ├── 42d51f37757341203791a9e6561b993d643dd810.nq.gz
│   ├── 433c1a6f37a1397ce3334a68c839e97751df55a0.nq.gz
│   ├── 43c85ce4c3d655890614f80200f1f414c084bc48.nq.gz
│   ├── 44cc97d1e26ffd9d4493ac695e1495d90e1fb2ba.nq.gz
│   ├── 45d3449b1fa2b3b8f9a13888c2f2f2fdd500dde2.nq.gz
│   ├── 47bfb950da3b7c7908d683efc56fbbdc58fcef87.nq.gz
│   ├── 49441bdd352672d2c1c6d62aed7d585e9852e139.nq.gz
│   ├── 4a03c82a8a4bde85fa2f6eefb4557ca6be534c3c.nq.gz
│   ├── 4c2e61136fbb8d6811f6d99754be26fb5c8cfa34.nq.gz
│   ├── 4c5ecef158d13d16079671bb1e1b0a59c91cfdfe.nq.gz
│   ├── 4d11be92bde21b0d54de5c8a49e3624c05b62ba8.nq.gz
│   ├── 4d67f7f3343d4cd2470c7ccc97683519bf4531a0.nq.gz
│   ├── 4f64adff3769b2cdbf41d538f2ce79086ebd9ba4.nq.gz
│   ├── 508463ab6f1f7cb8abf6782de87d5127927b57dd.nq.gz
│   ├── 513a29b91b189233a4498d93159da00a5bc0980c.nq.gz
│   ├── 53855566c3f7d2e2d39d83b3c7eaa984e6cec4aa.nq.gz
│   ├── 539c71f5e97a154e3f7bf1893733e44260177246.nq.gz
│   ├── 558c0b55270d99c4331846776b123d1b028f8bfe.nq.gz
│   ├── 56a64f37f6a9615f29bfcb4f85cdf218ba347b24.nq.gz
│   ├── 59439f668ff3cbb10698e40ea0af630c7368cd46.nq.gz
│   ├── 59dd90e7d4f61e5b10a2b6c26d93fdfa570458ff.nq.gz
│   ├── 5d9ec93b204796214080f3e0c2fdba3d0748d611.nq.gz
│   ├── 5f3ab1219de8bcc2955bed7d0f62d3f4f885507c.nq.gz
│   ├── 5f852b1ee7c8811cd6ff6c607c9e79912530b811.nq.gz
│   ├── 600f1ee3e2694c93a0fb9fb434e6331cd39c5617.nq.gz
│   ├── 623cb1decc3b195fc3e116978af389d18f08af58.nq.gz
│   ├── 63de8568fe3fd8d0f3d383fad939b20ce6b1c1ce.nq.gz
│   ├── 66b40b13f4f040f99a6acda8601cd187d5a48ae9.nq.gz
│   ├── 6a7c7617c4b2540fe8fb65ea8770e096ac001e22.nq.gz
│   ├── 6d3e1c1c8c4e918006d307335837fde4c07ceaa3.nq.gz
│   ├── 70001f1cae14481aed311240c930b514f0217a06.nq.gz
│   ├── 72a3e7d2331d7c2cfb21ac47e331d25db3d84f4e.nq.gz
│   ├── 72a85d0d21568f76da892d5ac056dc8b2803c47f.nq.gz
│   ├── 780697e87260003b2c48f363e4e509b1f221dde1.nq.gz
│   ├── 7908f5381d176bdfa5efd7acf606ce36499ff930.nq.gz
│   ├── 794104c3dbe16c89588f18998a47b41693a1aa04.nq.gz
│   ├── 79c117dd7c458b169286d5dc4c12ed5c37feb311.nq.gz
│   ├── 7c7acac876dea4ac54d213cd3408ccfb575b8673.nq.gz
│   ├── 7dc391c67a96bbf5566efaa35d72c85fac651811.nq.gz
│   ├── 7e0d3cbd23e515ec5b9a19508e13af921767c6f4.nq.gz
│   ├── 7f5c1948456aa76c983498210e3ae929d0c66d0b.nq.gz
│   ├── 802e4977f52ae04d94a9d2343fa105ca98690f89.nq.gz
│   ├── 810fce6e9bf2aa10265b85614db5ac65941ecf81.nq.gz
│   ├── 8273c4ff5d6ae6e736bf6ec93e0a66f3ab0699bc.nq.gz
│   ├── 8460f9be941ce85531f85af39013c653d4b6dbb4.nq.gz
│   ├── 84d165e3274230f4e9f4e97f8dc92796eaec13a3.nq.gz
│   ├── 862ed302df5e06c539e3ae798171449e94fc2c60.nq.gz
│   ├── 87f0370d28ed117c4475ec4df56811b67d1ae233.nq.gz
│   ├── 8ba0a8390bbae097082feba8881f399900697682.nq.gz
│   ├── 8ca73c7afb4e5412ba9c3a767388e90179f0d32c.nq.gz
│   ├── 8eee317857e79b493b07333f5ebb9c375275ff19.nq.gz
│   ├── 9071c129c649668db0cd4e76d935583ea14124fc.nq.gz
│   ├── 9186e0acbb1503fbe1169a88200cc8c7edd74efe.nq.gz
│   ├── 92abcfb08566e3b2d8841b58b3e5458206610d72.nq.gz
│   ├── 95b13a0188ab950dff3960bb33a4798ea056d440.nq.gz
│   ├── 96a916f2b3e6911ec2addf850e6bab1ba882ed04.nq.gz
│   ├── 98078ac90472dc0c8298db6399ac9f471bd16d0a.nq.gz
│   ├── 981da736aac196c003d9af943b068029a87304e6.nq.gz
│   ├── 9a80e63a78f00ff82fc8d5ac0e0b2efb54ba63b4.nq.gz
│   ├── 9bbfc4e5ead8a67799966c2278407a8efb5818e1.nq.gz
│   ├── 9e9f77b28e4f9e552786f45c437a4a40fe6ec641.nq.gz
│   ├── 9ffa2752c827067aa24eb2d1c07a52e170c1a5e0.nq.gz
│   ├── a241bf80b021cf2c3d9c2fdcbd79abb080d337ec.nq.gz
│   ├── a2620d2ef644d30f97e88e0fea536a91c56a33ab.nq.gz
│   ├── a742974e3d0b99516530c5319827d11e94d04ac0.nq.gz
│   ├── a86d6359c1776cc67988344d9aa5eb4de389565c.nq.gz
│   ├── ad16a217b84a9e3a779b57fdafa8f1c9eb513828.nq.gz
│   ├── ad234b71b911d01e15a45a30b922734a80e434c8.nq.gz
│   ├── ad8bc616671f6a19eab7f49031ff297931eede77.nq.gz
│   ├── ae3b62ba9f431523ca54cec18bf8654f5f482560.nq.gz
│   ├── ae77564bc6fa47604e7f33977ef47dfc39f618a7.nq.gz
│   ├── b02792b02c8236cc65aca48706d7909a87e126ee.nq.gz
│   ├── b6a403a15a86c69a40cbf29476aac78cc068d1cc.nq.gz
│   ├── b6d44e121a068999dcd8fcf4ace968b5dab93db2.nq.gz
│   ├── b7f15712035b8cd39ce4cb6d042e3458082ae11f.nq.gz
│   ├── bf46bf082ce4f87e7f402f0f61e5b40b4463a546.nq.gz
│   ├── c10af1faf98355da310ff1af03ed49222a8407c5.nq.gz
│   ├── c12128d8deb17cf10e1b27647c799288844862c9.nq.gz
│   ├── c2af4ce91257664a4d6a696660546bd67a7130d5.nq.gz
│   ├── c2f64fb2704050f3e39b60816d32c6da3f5bc738.nq.gz
│   ├── c77a5558de5b099ea5f77d79ee92739fdd79cf21.nq.gz
│   ├── c7f640f40560ce296025bc9c1bad8b27f7bab939.nq.gz
│   ├── c93bab726d20fbc2fe138dfe3294d6992b3e2171.nq.gz
│   ├── c982efc8af1963fb9f89f1927acf55c53cdfe111.nq.gz
│   ├── cb8890c728353110c965eb54f1e991e6df9765f3.nq.gz
│   ├── cc83e39f0ed470592fc2a6ac31fc966389339b30.nq.gz
│   ├── cdcd03f1b86dbe9d92450dfc2ddc2831f9e02c6c.nq.gz
│   ├── d00548ac24f1f3d1445e56addb5aa76bb16c58d2.nq.gz
│   ├── d04a06fd4d3baa6ad50364f3fe0e444d93dd96cf.nq.gz
│   ├── d28f78e50b8a95b0548d59c34a1b505e266a92fe.nq.gz
│   ├── d4465c9d78aca1494c273f45e0b2858ff8b8fc58.nq.gz
│   ├── d45429f13c66c87bf934e01b0cd646d9a0bddc4b.nq.gz
│   ├── db2472009c60acc72ca2f6f065bb4b674dc66746.nq.gz
│   ├── dc0eb9f57b016a98b71d329ab7ddbd2850896fcf.nq.gz
│   ├── dee7dfccfd07fa046880c7aac5d00857df776d16.nq.gz
│   ├── dfd033fb0d58fa1bb725cb93f90dfd78e65bfbe7.nq.gz
│   ├── e379c26829a7696a99b74afc980a9029c8cba5f4.nq.gz
│   ├── e3cc791e0affff09fbc487c7147813379fd1105e.nq.gz
│   ├── e4b1f93af5c4a2203c064f705a1ded639f831f78.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7cf3e1426c9f7a860e55b49dbcbc58200861921.nq.gz
│   ├── e857cc75b153d94e0dce199a0e98208513a00520.nq.gz
│   ├── eafcd9b107caf92f39596a5e0b984c875f07a2ba.nq.gz
│   ├── eb96380438f106aa3531f2b35773dc6d81c131ab.nq.gz
│   ├── ebe0e6baed9624976f3c9c7cea4574d2b00c6435.nq.gz
│   ├── ed04e347ea9022e9d7e9c460fad784cff0490d74.nq.gz
│   ├── ef7b7c19bfe909c4e370ee7cc9dee83743710bd0.nq.gz
│   ├── efbce596ef35ccf1267b1b7dc89adbd0e9cff91e.nq.gz
│   ├── f37ea74dadcd92f6dd2e38c61f1a19132b531012.nq.gz
│   ├── f433b1a53f5b830a205fd2df78e2b34974656c7b.nq.gz
│   ├── f4e7b74ce31a28ec470222bc3163ce28b4bc93ae.nq.gz
│   ├── f558a4e720528fb0010751dcc896be62634f6613.nq.gz
│   ├── f62f474e6b425fe078ab04ec40547ad07d2f7a93.nq.gz
│   ├── f764094ebd0a00faf837b90327af4d6ed92a633e.nq.gz
│   ├── f77d03c0dbe874a5cdb04b3cee8dbd3e628c9a0b.nq.gz
│   ├── ff1c52ea5897525ec01f06f235ddf7594592fdab.nq.gz
│   └── ff247fa190639b6be95184e8cc47669850f854cd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 75b1c909d587c1ff5e0fd5f3df1046f74ee249d4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 176 files
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

[pypa/flit](https://github.com/pypa/flit)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
