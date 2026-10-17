# Repolex Knowledge Graph of sebp/scikit-survival

RDF knowledge graph data for [sebp/scikit-survival](https://github.com/sebp/scikit-survival), parsed by [repolex](https://repolex.ai).

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
rlex download sebp/scikit-survival
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ca0c2bd6ed19334d9cb357e309c38d730cac8cdc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ca0c2bd6ed19334d9cb357e309c38d730cac8cdc
│           └── chunk-001.nq.gz
└── blob
    ├── 0198c864c0618a85675929a2a143b54054b8b381.nq.gz
    ├── 01f873c5cd48d4eec789d29efc76f18c81ec029b.nq.gz
    ├── 03eba0fa5d191b678021f94942ac8d8542b13a99.nq.gz
    ├── 04620d0298817cd60ca081f3d2b48c96335e4dad.nq.gz
    ├── 04efad9a9dbfb2bbbc5690aabf571dc0b61c28d9.nq.gz
    ├── 06485fb7d3ef30ff9fe8deb78ff4b7d76adcd370.nq.gz
    ├── 067cfd328ae18d30d6cf857e1a4505b1718be760.nq.gz
    ├── 0701248be8eb5d3197823c31804d1d2a41dd5858.nq.gz
    ├── 075b82ca0be8e28b56e9088eb7ab5a1fb949a802.nq.gz
    ├── 078c27fd02ecbe758e2d7669674acfe4e4eab213.nq.gz
    ├── 09952458c791f5bee4f39f1bab98160f23388854.nq.gz
    ├── 0a309a70c123240a7a919b83dc97eb73c7a16796.nq.gz
    ├── 0b7d63c6d298ca917099043ab137ddff6aa8f5b0.nq.gz
    ├── 1306c60625e99b099c249f646e5afe0c663544d9.nq.gz
    ├── 1330e392bf685ae1c02618a48ddc3933602f3836.nq.gz
    ├── 142ca2b8e037f04e324ac2d507ed7978dacad565.nq.gz
    ├── 14d798acf4509fcfc8b102d71e49fbf16b0e1319.nq.gz
    ├── 1606b990e538eb1a89463fb76693348b2cc3783e.nq.gz
    ├── 1a721bbd1a6b31690e344c665b17093a73190f32.nq.gz
    ├── 1b9210c0bb3f6bad53b5e46222ab0e8e08a5dc81.nq.gz
    ├── 1ea9e0bdff552c6cf6a51c51a9bbe12d751f729c.nq.gz
    ├── 1fa476dc7707cec50e9b08e2b11d45557c33fd62.nq.gz
    ├── 2010dceb0b4085898e493b88752f8ff6a1f81eab.nq.gz
    ├── 2054bd87fc2ea25e86a328adc188bcd2586d801e.nq.gz
    ├── 21d81543739013ad4f6f2738c939b9ee4f982777.nq.gz
    ├── 2447a3ba8c6ae46afb4e97aa08332eb6eb3f372a.nq.gz
    ├── 251108e84ddd5ca3c0b75923e9f3c2a3bf936977.nq.gz
    ├── 252626d0941746632d22140fe193bb46cbfd818d.nq.gz
    ├── 29b8d40bab226540bf8e92292cefc00574be7d22.nq.gz
    ├── 2a2047f3ef7a803d0e8d545b1db38938e8e7cad3.nq.gz
    ├── 2b606471c3f66dc7bdcfb1435ea7571a83c52916.nq.gz
    ├── 2c4d1bde92251c89464e5aa29fcfb86c1242f702.nq.gz
    ├── 2e3b6652b16988c5503eac49e9b242bf07cb6ae9.nq.gz
    ├── 3233604c1248ae9b643ffb068489fcab6f92f709.nq.gz
    ├── 326a72bf44955edba2efd080de91e2b46776b014.nq.gz
    ├── 3452efa7cca4c5bafbd1eab72ca63b5749d3bd56.nq.gz
    ├── 34718f85a535d196073e5fffb38ab85e36f25cd3.nq.gz
    ├── 34b282d3a9973a5014922f64a3efa295a204875b.nq.gz
    ├── 36f19a1d7da77bfbcadebda37ee0d9418c6e263c.nq.gz
    ├── 3831919fa1e14207e97a44ed88f3dab10d3720c2.nq.gz
    ├── 38dda363985e9cfc093a2074313a41e5334e62c9.nq.gz
    ├── 3c07eda7234adaefccc3102f4889466ad3bdfb93.nq.gz
    ├── 3d08f6b7e24401f82c7fa925182940c4256e5d87.nq.gz
    ├── 3d0f9a2cac5c8cc714effb73d80fec9de95002cc.nq.gz
    ├── 3e468c82e83e2d74871ce863b7d80e082ae4fc8c.nq.gz
    ├── 3e75cfb1167d8174afe2bebc50742838914d9757.nq.gz
    ├── 41a7cc831e8078f8affe995c18c2e2fc73b24d92.nq.gz
    ├── 4772e5b4a216612ed0cdae53ee28de0816ab5af0.nq.gz
    ├── 485ce8b5d08eff249c0ec57d9727ae6893e93fa6.nq.gz
    ├── 49eaf6034f0d012b6a12a37c393e29d9543f11e0.nq.gz
    ├── 4a75d184b0308190250bbc8276adcd6e8d0c7288.nq.gz
    ├── 4d7bb81e1e88e40b36133d91218bdca0793bbc51.nq.gz
    ├── 4d81a7fc829885d2618baf745909da55c88be082.nq.gz
    ├── 51649e965b54cdb25008cb82fd47fa32d819316c.nq.gz
    ├── 5212aea378e5b752b1647d86c9e24d55fc257c2f.nq.gz
    ├── 521518482ae48310ce510f4f1a27390227ac5b1a.nq.gz
    ├── 52e3951edc06812052744ebd6f9c8e35be2e836b.nq.gz
    ├── 5339ccb5fb7f04e9059ff06f0e100097cad877ce.nq.gz
    ├── 537fcef95f30bbbd649b3d4b0642ff9c327020d8.nq.gz
    ├── 5549821e7a9c72f318579b43c2df7f3dd10e5677.nq.gz
    ├── 558b9bbf0dbdb01d24c795e21a1bb9cc2ab3eee4.nq.gz
    ├── 57f270e249f5639665ed0a7cfaf624fdbd4a96ab.nq.gz
    ├── 584d6a814522749f7441c3f2a042bdcae59cd319.nq.gz
    ├── 5882664ed7bfa3c4c766782a0c5dcccd9181ce79.nq.gz
    ├── 59c94ed77e42ff704334de902007eae9209ad9bd.nq.gz
    ├── 5a28b399323e576dd07f5a79f0a6d74730a3555e.nq.gz
    ├── 5a2e857e1894e1576207e32a988089e6832f5381.nq.gz
    ├── 5bad211e97434d59291f575f3545142b1b82c676.nq.gz
    ├── 5bbfe61f740bfc4a81459f02a3cf1d1b15fb4d7a.nq.gz
    ├── 5cb2b2d2706966fbb11b8ccbacb71568a3533782.nq.gz
    ├── 5cea6c5eb15c050bf397b11b7921542f148807df.nq.gz
    ├── 5d2097b96a6c9f4f37b950fc8d61ab1c80c6ba3c.nq.gz
    ├── 5d54a701f87dd66e49a3bab3a5b85f6cedfa87fd.nq.gz
    ├── 5eb211ee3d49c842ab0fea906c27b22dd7d31a45.nq.gz
    ├── 6036808dcdb1350e7a7f9deee00b24151cb21303.nq.gz
    ├── 60989402a56866ae41286c5a5032b0730dbcb3f3.nq.gz
    ├── 626c93fd8a326350154ab90292a654c198aa8951.nq.gz
    ├── 629e90bb4dbc0a6a8f06032454d6078b1d52e38d.nq.gz
    ├── 634d06ab32226a87234217852c3e6df269f4e411.nq.gz
    ├── 64435dea4ad4396469bf492b8fdea596b2c527df.nq.gz
    ├── 677e12eb6cc0e0a5e9a11acc74aff8266b403f8e.nq.gz
    ├── 67c93eee2dbf3fa606fe5ce2346cb513b791aaa2.nq.gz
    ├── 6979e51fca222197e55d10c3666b90c81563296b.nq.gz
    ├── 69ba84413d3093ca65a68264ca5f8fd381265cef.nq.gz
    ├── 69c03bda14ee9ab3726ec27071a9edecae31c74a.nq.gz
    ├── 6c1e8b5511b2f4c9402faec90d1ff2a6fb73423e.nq.gz
    ├── 6c39f18ee648c10c1b106adb401a13e30a5ca281.nq.gz
    ├── 6e3122329ec2b5a3593bfed99eb3417d1cb418c6.nq.gz
    ├── 6f0476f1bc5129a276321affd84733af3cf3040a.nq.gz
    ├── 6fd9d8f415562fb83a2d59c0a509dac7bc6aed64.nq.gz
    ├── 7326101c5912e833715afa929616776cb9664239.nq.gz
    ├── 74eb1de3c9de4884695b664f4b7d2c01196f0add.nq.gz
    ├── 74eea00b270a7689849b05a698e46269084ef04e.nq.gz
    ├── 789f3b53b6bb9c089207e69129b9497528aa22c3.nq.gz
    ├── 7b82d5b824865377660f7cc87eff1dfced020e5d.nq.gz
    ├── 7d2a9c1587a31eabb6e44eb2619200f322d797de.nq.gz
    ├── 7d68dd175fc713339a07c5fb132d0b0da07770ec.nq.gz
    ├── 82106db547fa685a305b890ee2833376c883827f.nq.gz
    ├── 84333319398213c9bc601024df5fabb0c44a7fd2.nq.gz
    ├── 863e09e6592ff50f58a796c36e7fd0acb569d386.nq.gz
    ├── 87966d07a71405a2e9e94973b09b63fa973adc5b.nq.gz
    ├── 87e9261c9e98f7789ab63da534fa315b1b0d8a59.nq.gz
    ├── 88118e96882772d75ebc2e242ed41917b4b09630.nq.gz
    ├── 88ad7e3ccb6b4475ea74c20c4af27c93db5279fe.nq.gz
    ├── 8a21085df3ef0fec6aea3fd48613c4f27edf351f.nq.gz
    ├── 8a892387341a9790e928a1c6b1f982cba437c9f0.nq.gz
    ├── 8c1fd88dc7eba714f0f1a2fe75f25d02f075e7e4.nq.gz
    ├── 8c3b721e5d45e8dc2f2746538b63207d451a31fb.nq.gz
    ├── 8d6dbe49b89e76106f727eadd083728862686d98.nq.gz
    ├── 8ea18f4495660b21dbbe3e529298064c29a4310f.nq.gz
    ├── 8f0becc6fbd3c932d6223fb2b54979380cef09f4.nq.gz
    ├── 8f0f3277444cefb6304f56992755bfa1ca18f1cd.nq.gz
    ├── 8fe66d1c71c0d17caf8551199f30af57bce8446c.nq.gz
    ├── 903ce279eafe09ba19d43bb95fcabad8e751b3ff.nq.gz
    ├── 90774642b66835823d5a8cf53e07c31eace53bee.nq.gz
    ├── 91bbcda3ffbf66e49ae1dc0da4d903b542f01503.nq.gz
    ├── 9211ecbfc37de4b5ad04e6305fa8ffa455debac1.nq.gz
    ├── 92852a130415aa4f4a349278c5c71769dd5be331.nq.gz
    ├── 929678edc20386418a2237168ad1f2fa2cbf324e.nq.gz
    ├── 942ae6199fb0b926a1722471dce0b5508bd45628.nq.gz
    ├── 94a9ed024d3859793618152ea559a168bbcbb5e2.nq.gz
    ├── 96b16f9b0d1b41af328c0ef0083f922488c0724c.nq.gz
    ├── 98bfbf31082df5c90eed7621396e2bb35c3b5e8e.nq.gz
    ├── 9a8d7a7b214876363b8971925ec10a761ef96144.nq.gz
    ├── 9cdb8dddbeef08a940431ac2882223b14dffcffb.nq.gz
    ├── 9d15bba1920ba1a4c431d3a24261e437bc9e7420.nq.gz
    ├── 9d47fa88e5ecaa4556b1dc38072402ea6daf7570.nq.gz
    ├── 9f1a5b631061178a14224b834711e442425cf7e0.nq.gz
    ├── 9f369043ca26584dcd28ee28d109f16032f98f7d.nq.gz
    ├── a0d1e36095c22e62dcbcb65c1bb7067368bd08c7.nq.gz
    ├── a0d5ad9a98c909d3bdba0243b880e16ef2d4f970.nq.gz
    ├── a1c8647d34c6135a65431ec6875de3621664553d.nq.gz
    ├── a3dc24634b6bc389fb3843e8d6af0b76b81136a8.nq.gz
    ├── a4e0cd0ba354e34f18ce0bda4f46b41c99941d55.nq.gz
    ├── a53c0ca54faa9a72bdacc3fbf157b4ecdcc9eb35.nq.gz
    ├── a54dddced597ff1bcd1fddf5d8cbfbf9e2b86ca9.nq.gz
    ├── a5e5edf4ba9c1d990efe5719654fde977a33a8e0.nq.gz
    ├── a5f591a94c7c20f55fa25492ec1b4dc9739bf994.nq.gz
    ├── a6dc0f5b3c179088f20ee63a75ec522e077b08da.nq.gz
    ├── a894b6a0deaa7e73500c73285186cd5fdc7938e0.nq.gz
    ├── a9469fed392c5b357eec3fdc6c7657ce81df2b77.nq.gz
    ├── ab3b27d45bd69bbc5de501c619e6e87e8763d5b7.nq.gz
    ├── ab4eaca768d0e6aa223f072031dd53e5a8fc9f33.nq.gz
    ├── ace81eb603aa7a24f53bab9aa120b5f8fe4ef0d6.nq.gz
    ├── ad0d927ac448cc2044587a522720ef1535203c1a.nq.gz
    ├── af5992002e4583e638d65ecefad95e7f706eb4e8.nq.gz
    ├── afa1a2595bed0d72abfab6fa6796ba9a7ac8dfd5.nq.gz
    ├── afb03a6be1b830f762f877f0d08aae5f7b829a76.nq.gz
    ├── b420e00baec05809058b7d0bb42b613b1350e2ad.nq.gz
    ├── b4265750e23714db86ea4462b82c018a8194bc95.nq.gz
    ├── b493ff309166188ec775160f0bd042a82af02a41.nq.gz
    ├── b4f18e104c0f5473add3df60dfdde4bb4d6645d8.nq.gz
    ├── b680895ed5e057cc38dd1f27eb0e17dc14282d51.nq.gz
    ├── b7232f5a9654ff456fd2a6ff4084599772a99cc1.nq.gz
    ├── b7eeee27a39654c686fd5df39aefdb8622d75290.nq.gz
    ├── b98177db813d702fb77e5bdeccb42c23b3e8f8c5.nq.gz
    ├── bad824529040e52f2eacae05d1fb524e07bede7b.nq.gz
    ├── bae73e05a5b5b023c6d442eeed07f6b1bc58ef66.nq.gz
    ├── bbc64cc6c3920c5e071a733e380de9581c06e421.nq.gz
    ├── bdb29406590a178b3f3170b45f89b45a40b24ed5.nq.gz
    ├── bdb719276d829efac90a3a0897a8c338d7515395.nq.gz
    ├── bde16ee63f0e72099d56587ae1e05503daac9659.nq.gz
    ├── be0166a3dd232e0339706b11ce55a6d135cafd0d.nq.gz
    ├── bebc7c75b6380a37fde0d1b36346274455f8b722.nq.gz
    ├── bf0cd355334b8c1b85cb5dc1593682635c67919e.nq.gz
    ├── c21e61232b0182aceefdf0e6f8ef6d22e9b79031.nq.gz
    ├── c65ac44b66ceed896c505bad5f6f29767d4af2a1.nq.gz
    ├── c671523d2d5643a300e586dfaa4228a96152f4f9.nq.gz
    ├── c8d0b8d1e62aed8ac998f48ff84fa9ec4cf67ca8.nq.gz
    ├── cb5a4e0301df99724cddd3e74977191d9a768916.nq.gz
    ├── cba759807680499d6ad5790b5920f509db05dca1.nq.gz
    ├── ccfed40c3f0392321322519a069b14b7b45e9d80.nq.gz
    ├── cd0add8d635e3332bce53223a30d8674da9eea64.nq.gz
    ├── cdc8108311d68f23ccfb13e5b627fd43d65146ba.nq.gz
    ├── ce4d24799eb53de8d97736f472573cfdc27e1a5c.nq.gz
    ├── cf39f436b41ad44181c7d0c5134721f117de28db.nq.gz
    ├── cfa4b7b354c82751c21482536e3743858805e314.nq.gz
    ├── d12079f1fd49ca1cd0a2bfd08c38f98bd946d8dd.nq.gz
    ├── d13e0523fae2236ef6399009e92da98248165a15.nq.gz
    ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
    ├── d687cf898c20c2cd2f2c5c6a4c4996c3f5782826.nq.gz
    ├── d7cdd703d1c837aca241fc525153ea6450a2a70f.nq.gz
    ├── d8b3b3c67e0a5831d2516f9aa69948830f42fc2e.nq.gz
    ├── daf6791f55c248079252c6de562fab0cc63cc0c3.nq.gz
    ├── dcc49bf4a201fbc79f72d1a9ea1d98a28afc3779.nq.gz
    ├── deac32b644752a9b13343fe7a69dd99946f42de7.nq.gz
    ├── df25c847f1c298bbe2bd6a7aabe724a7a179e4ac.nq.gz
    ├── dfa57a8544552daca5b949006c8f7d6e6111cdef.nq.gz
    ├── e1e10b6dce9dd3fd321cd84be73b1a1f0d7e82bb.nq.gz
    ├── e1e54660150120a3b6bde655242fabc61a1a4591.nq.gz
    ├── e345a2d5033485c012a83eff6bf5ee57e6b83874.nq.gz
    ├── e5406984dc519821a3b50e413a3906427aeccaed.nq.gz
    ├── e763eaf0b271873b0b875e1e312e6dc665f6bcdd.nq.gz
    ├── e89163ac0d9005e4d87cdd116c71d211627d15b1.nq.gz
    ├── ea2822251b175a66f87921914e9219bcda861a90.nq.gz
    ├── ebde9e1ce4d847453b143dcb49ba7bcaee3b1f20.nq.gz
    ├── ec1337795df411ce22eb855ac214f6af455ace5a.nq.gz
    └── ec668318e0be17c8347917177952b7c1d16c9e76.nq.gz

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

[sebp/scikit-survival](https://github.com/sebp/scikit-survival)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
