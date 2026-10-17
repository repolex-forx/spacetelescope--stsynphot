# Repolex Knowledge Graph of spacetelescope/stsynphot

RDF knowledge graph data for [spacetelescope/stsynphot](https://github.com/spacetelescope/stsynphot), parsed by [repolex](https://repolex.ai).

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
rlex download spacetelescope/stsynphot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dafc63928fc849b27f01cf45f36ee74927db3bde
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dafc63928fc849b27f01cf45f36ee74927db3bde
│           └── chunk-001.nq.gz
└── blob
    ├── 0025272a5d5157c0ba7987a953e0ac6e87ef5384.nq.gz
    ├── 0291923ec94722bd386d110d07e77318e775637a.nq.gz
    ├── 04e3d4a5b39ca4b3a24ecd3cb0ebfa29da8eda52.nq.gz
    ├── 066eb8c6a260d8461d9d8b347fb4851f33af3c4e.nq.gz
    ├── 08485d0ea544a975dbf575ca532d73ebff2c2fd2.nq.gz
    ├── 0974f81c23f2c99b427aec9c45d33a0091f85e28.nq.gz
    ├── 09d84513d1bb8cb6aa5d5a6fb44e2a92f4330a5b.nq.gz
    ├── 0d28632434f921e75beef7967293d5f9ef7850d6.nq.gz
    ├── 0e80123d5edd541fcacf9a4f244299bb96e0caf1.nq.gz
    ├── 0f03d8e39598df370d2a0483dc2b2ffebab9d5b6.nq.gz
    ├── 1059e0a89e32d43b495ccdd131cf60c91e0c8f1b.nq.gz
    ├── 1210816c2be48186671662576fad977a4f4d3427.nq.gz
    ├── 1366bb5240dfc50984065c1257208d4ff7d81574.nq.gz
    ├── 14593ee9c593d9a2bec6d5fa6828127efd2cf216.nq.gz
    ├── 150e12cee54ab6bc0be6ff29bce5fff1ed846c3f.nq.gz
    ├── 1539894e73d4c212a918e35f366af6f189d824a6.nq.gz
    ├── 16dbaf53de96b214b416548fcecaaa5bf79a8d33.nq.gz
    ├── 17f46aaf98467ad6ecc3fd27ceb2473a2959b476.nq.gz
    ├── 19718dd0d8b1b795b0c3a13b4e2871c3b547ac83.nq.gz
    ├── 1b6c07b59a97ff099651cf5693c34df245397b3c.nq.gz
    ├── 1c7928ec7cc89929524b081115c31fc0e274f9a2.nq.gz
    ├── 1d54b6d52786dd058a9d68abc1f8fed44907fddf.nq.gz
    ├── 2095e63239f1a29f68675318d4cc025b73d3c3e4.nq.gz
    ├── 2112bd6a91ca911b701cf052fe991cdbc43f51f7.nq.gz
    ├── 2131b48c4fe989ffc1294deaf0d1679a5b0bf055.nq.gz
    ├── 21a7dc813cc441997c2a5a122f85874e254434c4.nq.gz
    ├── 22eaf3242478bb542474647ede4767562b5aba2d.nq.gz
    ├── 2450b35c1a2505dd16f14e562381a6c41cc6f927.nq.gz
    ├── 248fea2a3dae4d78248465f04adb079544960126.nq.gz
    ├── 2554f0f3c7972c1d1472886a13751031473b7d20.nq.gz
    ├── 2579d092a178cf968c3a87362e88363b7839376c.nq.gz
    ├── 2679699562a997a8ed0fdcb753cebc22b095de45.nq.gz
    ├── 277264830f4a1962601ae3520c0d6e0aea95ab55.nq.gz
    ├── 2797b0fb57251d76246a2c8c19efc8729d9e8a9d.nq.gz
    ├── 279a76046219173d6f748068f4f2c1a6c93cb3a7.nq.gz
    ├── 2b1a1f7645f5179d121c8209b70ad8d86cc22266.nq.gz
    ├── 2c84d9922b9dae36bda538a016253b27829b2ac0.nq.gz
    ├── 2cc2485d075f1a11fd833eb384c9ad6d807ff8f0.nq.gz
    ├── 2d327309212dbb414de50601ffc419af2037591d.nq.gz
    ├── 2d39787361cbde49a84d620d1113d774dbc4d27b.nq.gz
    ├── 2e82f71f16900779228ac4df3d4b9520aa9f3453.nq.gz
    ├── 2e9aa2bee985cf0f742f4a1485b91982ff122d36.nq.gz
    ├── 2efe5ac7c5208d2385aa97fa21f68962bbf4fb31.nq.gz
    ├── 304414b42e1266aba9a694f5fd36d215f7812ada.nq.gz
    ├── 3348fd9fcf3817af04522ebf04df16e043a2884c.nq.gz
    ├── 33d8f4b42479c974f77806b31fe00292d6f69881.nq.gz
    ├── 33ec13912f1d80888a661db1e9f721c637eba0de.nq.gz
    ├── 355b15728abed99f235a8ed2f78b8fb24a37e7c5.nq.gz
    ├── 3771cc3273b33c2e3bd01e4557e000afc88e6491.nq.gz
    ├── 384fdc756d00bf202139c5011893e9f3f419c676.nq.gz
    ├── 389891244cea326473d871786ad86141d0515646.nq.gz
    ├── 3a6938728bb4a381d53605d58bee2078ccb7883c.nq.gz
    ├── 3c652c45f0cbd0de5e0c92000fee5165bc11dd43.nq.gz
    ├── 3d0d49bc636df2842145f44dd55bfbc36f28d11f.nq.gz
    ├── 3da7eab8e8a4050961e1be2e8af6ed44064a4337.nq.gz
    ├── 3df25c0e96a0d067f29d44b4fa16147668206428.nq.gz
    ├── 3fe409d7589c9bf121937abab4dff8dadb7a72c9.nq.gz
    ├── 4094cb655c3f5c94da59b5ffb3e5d425180a95c3.nq.gz
    ├── 4197015ad33d527ec05ce87dc2b2f15a2ee36aa3.nq.gz
    ├── 423fbc98e2d3601312d133f5ddc367d92d486054.nq.gz
    ├── 42c93829da778f8006f2b6ad1d46c55433b8ecf9.nq.gz
    ├── 4374cd393dc25e164ece6c9de01faee348ea5ec9.nq.gz
    ├── 44284bf5cf3a6ef33c1b42038a163f4faca20772.nq.gz
    ├── 45d1df2509b914f09471e06b083f93b809dd2a1a.nq.gz
    ├── 45dc5bdec741ee1cb705373dda6687f71355e833.nq.gz
    ├── 45e3bb1223ece5fe02be5df2ac99b812ac80a9d0.nq.gz
    ├── 461ba2d867bd9d566da059c048794efc4b715841.nq.gz
    ├── 49147375a30084f2cc80ce9973ee3caed60a479f.nq.gz
    ├── 498abe6d3c3345a2b1f12ef96736d0e638960ecc.nq.gz
    ├── 498c98305acd7f7e156dbbac04f0fc374c815cdc.nq.gz
    ├── 4bfe3b26a51d86e4313fba7b290a4f15050ad296.nq.gz
    ├── 4c943ed37394fc64ec7ccc1d4be2d633b4e520eb.nq.gz
    ├── 4efcccaf47b9c564607ecc9e87b8c887c2bbcb89.nq.gz
    ├── 4f1a2f24c6204c2bb8d36c037bdcfbb5bac1a5d8.nq.gz
    ├── 54215123000bbcb9e2e192b31c6f0a67cbd78277.nq.gz
    ├── 5476c4626c9257653da8dae2fd30d5dcc4a548c1.nq.gz
    ├── 54d6114d493a2b080f300acb0778e9e93a77735d.nq.gz
    ├── 5500b7452f2db99edd909847e5c99cf5306d4ffc.nq.gz
    ├── 575561a429400475913902531b2d48be6e847760.nq.gz
    ├── 579643322ab23834deab20f3daabcb8fa8d20af9.nq.gz
    ├── 58fd730b617b2223bc5b037930195d1a73d86c43.nq.gz
    ├── 5a6693293c3255367bc75459a7577093ea6b5c24.nq.gz
    ├── 5a9742dddc21e03f6a0b5b1d6034a907fcb9d4cd.nq.gz
    ├── 5ac9faf8361cc4a293022e67cfbc9a276e3ace88.nq.gz
    ├── 5b3f1d4cfe4708dd4f9ad998c37ef2b0073c308a.nq.gz
    ├── 5cb35081931cf12caa36323bd04ee41b693215f6.nq.gz
    ├── 5cb8813f887c9c840aaac9f5da15c801b6f21d97.nq.gz
    ├── 5ce762cb436c300454c99d7287c563dd7f33149b.nq.gz
    ├── 5e454aa03ea2287bba3a247231059f193fac5269.nq.gz
    ├── 5e703c8f7e352bd3884f9559e638b1a96d7f2869.nq.gz
    ├── 5ec2941bb5f49b6f56a62003c13248ca5fd5b6d4.nq.gz
    ├── 5f35906c56f5cff19f6e1470aee2a075908ea258.nq.gz
    ├── 60ae3c92709e8beb90221c14c598a151d7c4b5da.nq.gz
    ├── 61732d03ef3320e5226502ccb87e1e7a6dc23946.nq.gz
    ├── 61bc842ac6e6c3154a8d4a0288b7fbfe489ecd12.nq.gz
    ├── 61c12c46d4c59d2fc4c45e5fcf10ea7b90661a74.nq.gz
    ├── 622fbcc46a32bf7afbcb3a1dfa8c247a6c09b9de.nq.gz
    ├── 626b5525e60e8ca28fb78e69263628d57a17efa5.nq.gz
    ├── 6316921f95d733cf443a29dd6982ac4b56e8ce54.nq.gz
    ├── 65128347544504d7a6215cd41082fdbfc96f2781.nq.gz
    ├── 662358a6d2d8f5010a5857c6f1b45a30b0d2298d.nq.gz
    ├── 666a1052055dd5042d07b3ed9c3beb7660df471c.nq.gz
    ├── 6771f6cfe6bc3bc370f68c76a75ba4b6e698c278.nq.gz
    ├── 67f12a2d7e6a72e3d8b99f02081dfa8a9fca80ec.nq.gz
    ├── 69bdeedcc8ec45c7ce25dc72ca03f7ece9bb9ab2.nq.gz
    ├── 6aa68e416deeadcb08617c643e7ef79f51591c65.nq.gz
    ├── 6b214a5c09d3a2ed5399a65ba6100bdfd0b070ca.nq.gz
    ├── 6bc806003b0f6f49e4963f933e51e20113533327.nq.gz
    ├── 6c04b988b69e13a000122177ea81d9f40f766263.nq.gz
    ├── 6c7fa15f4814c5589c2c001aa121063637dc2a47.nq.gz
    ├── 6cef4ae7f5a01130f7431db570879c9cac4703d2.nq.gz
    ├── 6d3b63a040306c77b0546dc2cb91705daabb2ddf.nq.gz
    ├── 6e836aed786931c29e7872b0634d4f84f53568b3.nq.gz
    ├── 6f57fab3550ba2278a22639e83e43592456da8eb.nq.gz
    ├── 6f59ad5a35e996042c6aaa27c8fb0b8b04d5b09f.nq.gz
    ├── 71aabcbde7a0eb25f0bf8364a894a22675b3dbc8.nq.gz
    ├── 728b12c0b09f9ea6b24053cceb5f5ed8b0364566.nq.gz
    ├── 736edde1c006c1bea6f9c6b5ebab5f5986e86d86.nq.gz
    ├── 7376ef6829d55ed4f45ab8273db600b25616536a.nq.gz
    ├── 7534166929d80065d213f88ef311ae27e023f4d1.nq.gz
    ├── 757fa30c2b68481acbdc8d70686d9e57388778b6.nq.gz
    ├── 797b19eb98e70013d2fda0b0e392875386b254a6.nq.gz
    ├── 7bc0916cbc967fa87ea92f718748d92fe930c681.nq.gz
    ├── 7bdde9124e5dd2534fff4846945b431dcfc6dbd6.nq.gz
    ├── 7fac3fd1bd300ae4df0e0f4e271e0cba690f6c08.nq.gz
    ├── 7fd232b81352caabff279f8c335c901885222e66.nq.gz
    ├── 809eb40972baab3ad377e0755b971b9bc6233f27.nq.gz
    ├── 83b60612d7c10444f433f25c63184e1a9336a010.nq.gz
    ├── 844704b65f93eca4eeb0b8103a9b3499e8cb7832.nq.gz
    ├── 856be5c77e6b71e2c32628bb8f5fc7db25b82bfc.nq.gz
    ├── 85732a9780676bec04e4ce73a11e9f0b66b69715.nq.gz
    ├── 85b04ff1513f235e70e29a35ec25d37b594376fe.nq.gz
    ├── 86874d30f38625e2a3bebcdd4e50c29cc3110c6d.nq.gz
    ├── 8891bf4752a0ea3361d3be27740bba651de215a2.nq.gz
    ├── 88ded4f3a3e94400b4043fa91c20a1a46e8c8ff9.nq.gz
    ├── 890eaaf1d264252626cdec8f1411486c83ccb765.nq.gz
    ├── 893cea4fa1570b7ab65edc3089f560de619bd7dc.nq.gz
    ├── 8975eba36effb0d15a71e70e51350ca0a8d683ae.nq.gz
    ├── 8a08a8976d1ab67934a17c39e6835d927385122d.nq.gz
    ├── 8a8dca4047239fa23908a16805c124f9f0aa9449.nq.gz
    ├── 8aab854e501231d9366f2e664dac24eb9a530f89.nq.gz
    ├── 8c9824fb402b4c3b71b4864f7daf84d829ad7b4b.nq.gz
    ├── 8ca4b96982136c355ff8f3ba6669576c94c8b925.nq.gz
    ├── 8fe54d075fdf1cf58ae1c20e27054334d3edbc60.nq.gz
    ├── 9034cc1f12e6d55c6534ca26b4b3f35eac37913a.nq.gz
    ├── 92b531c5b9d5d04dd7b621869686c09f6f23b993.nq.gz
    ├── 93830694d7cbac4d0a5bb0a1ad159c7d8f66e673.nq.gz
    ├── 93dfe92b9c98e009c2f75b6477817411d3a15585.nq.gz
    ├── 962aa353ee4414271f1dc608dd17f86fc16ce9d9.nq.gz
    ├── 98b54dd6d69466099df9e49d11281a0fb919658f.nq.gz
    ├── 9a2fb9e057f6a0cacfb2f383772594af3cc0b315.nq.gz
    ├── 9ba8bbd8c54785ccdcd8f9583f0d35a4a3148af5.nq.gz
    ├── 9cabaf5238d62b16f3ff3c1fd828130815f33324.nq.gz
    ├── 9d7f6caefca56c20fde48809d6b37152d85e13ae.nq.gz
    ├── 9d98cae0568eef9dec5cfcfed57b27b3476e205a.nq.gz
    ├── a09bb4171abed16d65bec602f18d59362a675b91.nq.gz
    ├── a3c88c79043012726a1497c0e0b6a57be301896b.nq.gz
    ├── a3d4406b5424c35d2ab9b45cc35f28969f61d1a5.nq.gz
    ├── a440157d9362c31ab5cadce8fa25284f534aa335.nq.gz
    ├── a4d9b9f086a1ef64f006ccb810a6bbee6b037752.nq.gz
    ├── a4ff578a670b50414862a688f5a6106e2a5f0d3e.nq.gz
    ├── a5d6d0c7eb994e5a18cdac6a1d12d293d8a221b4.nq.gz
    ├── a6551256d06c81fa136bfb73f1fa27b5e73f6d2d.nq.gz
    ├── a675edc20af5d1f81209ea780cd8e2b3c339b104.nq.gz
    ├── a69f3b8e64c657c69354ef826059504a8565b5e4.nq.gz
    ├── a6d066d34e33947a569590068e4dbb70e9d326c4.nq.gz
    ├── a76c394364d3f4393e5318b5552ed2527b073731.nq.gz
    ├── a81363e90a65da4208285343f217e465e56682b8.nq.gz
    ├── a8752e00523cf454cd912af1e356191e024e3c1d.nq.gz
    ├── a876450ca57ded076ffe3e7db8f77834c0e01377.nq.gz
    ├── a8dd0a2ef8dfa01daddc30fe69f7121e35e06075.nq.gz
    ├── a907b20e582a0dd9e54aa5d54b0be507cc033e14.nq.gz
    ├── abc6cdeb5e069b8fd0c883b945a8cf01618e7ba9.nq.gz
    ├── ac0091e19e67ab76baee690fb3b9f558b2a602cd.nq.gz
    ├── acb614442473591d31f631ff0d2bbed5e07f8f72.nq.gz
    ├── ad02fb41a3df2bba4db9f2cc94c5f41d5863edb8.nq.gz
    ├── adc3f73caafe75bb9f8a47b6b2dcc9f1459c1529.nq.gz
    ├── ae97b21ffcef920b7331887551cb47f34f84a68c.nq.gz
    ├── b2418ce7d1058756741231ea9024f42c5c396e44.nq.gz
    ├── b2c0e8a3549875a5f88bc4b71042c95b55bde089.nq.gz
    ├── b2dd0ecc6ecd6a7361b92d0dcdf5b75477aa9f12.nq.gz
    ├── b41ac9b0f16596228533a0ce3ab81a0673703c97.nq.gz
    ├── b48974f6bd102c5b1098fd99107b099b53c6c65e.nq.gz
    ├── b6a3d829894a7e30dedf3f017c4b477befc0f1ec.nq.gz
    ├── b927ed5591c2b4d1dc40c0c19db01a3a4ecf6206.nq.gz
    ├── b93ef6b16749f4d2bfcf552206f1c26da875383f.nq.gz
    ├── ba2b2c7b04579fd0fa8af66b675cb41f78725b5a.nq.gz
    ├── ba728cd265cf56967c7b0a8509b8fec7052622b8.nq.gz
    ├── bb12a91888d8c13cd7b97eb6ea2fe40951cac71e.nq.gz
    ├── bbd849400481df30da651a0cedc63ed5a1be5cf9.nq.gz
    ├── c065e5820a9d0af35b0e8b314686c2cc0cbbba36.nq.gz
    ├── c1020f21d796b98633f7acfea5c27f50e0ecdaef.nq.gz
    ├── c1b13a9d681835a6b778ef39962f2a42009682c5.nq.gz
    ├── c3005e97c6be94dc6b3a22e21b40cc9e2b47a18f.nq.gz
    ├── c3453af693a56b1cfc5b9a9021e6fd6f9b6d629b.nq.gz
    ├── c3638037ec4b60aab4df53ecc4a5b05df0285bfd.nq.gz
    ├── c3e8b94d56097a2d6741f94054ed5ba0027984e8.nq.gz
    └── c7979506d6bfcb9819fad6b4955ee871e08eb175.nq.gz

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

[spacetelescope/stsynphot](https://github.com/spacetelescope/stsynphot)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
