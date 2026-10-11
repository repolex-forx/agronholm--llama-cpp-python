# Repolex Knowledge Graph of agronholm/llama-cpp-python

RDF knowledge graph data for [agronholm/llama-cpp-python](https://github.com/agronholm/llama-cpp-python), parsed by [repolex](https://repolex.ai).

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
rlex download agronholm/llama-cpp-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 803924b02cc8ca7531b70e6497d1ff7b83f75737
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 803924b02cc8ca7531b70e6497d1ff7b83f75737
│           └── chunk-001.nq.gz
├── blob
│   ├── 047bc14424303575f73af90611fec827334f54e8.nq.gz
│   ├── 057ac389eb460a75e772fcdec37b04a7707ce6fb.nq.gz
│   ├── 0b36746f9121d03407ce687f1dc608908adc89b9.nq.gz
│   ├── 0bbf20ffe9affde296ab9a746917891e977bc4e9.nq.gz
│   ├── 13128be044b82279b6c072ad800bd043b1b8e131.nq.gz
│   ├── 1375e1392d2b1752b9c1d3416717b99a11f2b07a.nq.gz
│   ├── 13c5b6b0df5f67e80cbe584909b83777901265a1.nq.gz
│   ├── 13c9512419bb39423b13c3063d25b8142abd7b6d.nq.gz
│   ├── 17575c700865ac97c39293a601625aeeb967664d.nq.gz
│   ├── 199bd4ffbf88c68c98b52c05f388dfa92716f6b7.nq.gz
│   ├── 1f2c59017718bbc1b662866327b713389c7a7bf7.nq.gz
│   ├── 1f413816599a944e591e9a3948dbeba15a351d22.nq.gz
│   ├── 2325dd303b261034fb053f202156eeb2706be76a.nq.gz
│   ├── 255ee67d6f0541febdc00acc632f441491a51bde.nq.gz
│   ├── 26ddf2c7a15bc12d0a9276fda1b87f56d630d46e.nq.gz
│   ├── 282333e5a8f850bdd0056c1c4629e7c4f3523d4e.nq.gz
│   ├── 29628193bb0601d24b09d867663287f99bc0db70.nq.gz
│   ├── 2fd7ff19390daec1d99348c385a9ae260b161de4.nq.gz
│   ├── 335033bba651209435142e5e14b4ffef9efba68f.nq.gz
│   ├── 34ef2874dfc7b9babb3b5e949087400a5020b539.nq.gz
│   ├── 3594df1a50bd3e73a3886c9562d188e1d39189b1.nq.gz
│   ├── 39081be17aa5d415462793208022160c2613a8e3.nq.gz
│   ├── 39dfb903ba43d89c83c7b5b2f7d93502716bb16a.nq.gz
│   ├── 3a1d7180d508818fe957923e00dcd8950938632d.nq.gz
│   ├── 3a6457dcdfd47e764654bacae0ba8347976b645a.nq.gz
│   ├── 3d410148f20edbc1f89329711c6b9a33152ade59.nq.gz
│   ├── 3dd00767671c5e9dac5a2ab8f4f1331531294b60.nq.gz
│   ├── 44a1461db7a0d524ecab003157cea63e393adbb7.nq.gz
│   ├── 474503fdfc554d8caabee4f321a80427f8c7d696.nq.gz
│   ├── 4c904da78cd1ecd9bc35dafed43490df1f0c6735.nq.gz
│   ├── 52061bea6742b46760ec8c227f714932551887d8.nq.gz
│   ├── 5bee8a93b57636729369f43e8f00b48b3af26fbe.nq.gz
│   ├── 5ee667dc0d40a7c35431021c9d83de625cc721e3.nq.gz
│   ├── 5f350ffe99abe7297b2839f36fd0eaeb98887805.nq.gz
│   ├── 60bc7aef42aac0409cfdca666ad2ff6f516d7b5b.nq.gz
│   ├── 64a0304a1621df4718d5d8b6ec8cc4bcda5bfae7.nq.gz
│   ├── 6bf90273accd8f1a0cdfcb2c740d96c1d7629edf.nq.gz
│   ├── 6e338ba17ef1ff9b2ad294d0e46121569a407bd9.nq.gz
│   ├── 6f6355893381929c3ce335768e3205b90777c7a5.nq.gz
│   ├── 71910efcbfd30ec36a7e2c1bbd37dfe41c1aceae.nq.gz
│   ├── 7307c85ab625d75ca9b64b32e68149667492c8a7.nq.gz
│   ├── 747c6130e3cb1479d20e2013b1dd3db3379c2266.nq.gz
│   ├── 787b3f108e1cf61d21c6f954e52567ba32659906.nq.gz
│   ├── 79a9e67a1aee09c6d182f240ba5eef32feabcbce.nq.gz
│   ├── 7edf0975dc12ccc95ad14de085f07efe6d65c620.nq.gz
│   ├── 7ee8f748eab47180cea09c0ad8e75c3b991b4af4.nq.gz
│   ├── 8448ac1f7f3cad79a75e9d6ff821621d3c806548.nq.gz
│   ├── 95f6e5a272ed2d2a32ad632e069d2965ba8e4786.nq.gz
│   ├── 994d5f14972fb81738ca4cae085c6603ee1e5de9.nq.gz
│   ├── 9983ef777dcabbcab1c8fb9eb1439f4c731395d9.nq.gz
│   ├── 9b97bf2f56d7cb3e4f0f61abacfb2e99110fe3a8.nq.gz
│   ├── 9d68dbcd9d94bcd8c4fb1fb90891cd0003d07c32.nq.gz
│   ├── 9f2d087539728c9a30890909039b8424a4df65b8.nq.gz
│   ├── a0212ff0d2c9f9baf55936c291f968c7e04cdfc1.nq.gz
│   ├── a409fb882dfa2d461b1cd055e905d41475dd5bd5.nq.gz
│   ├── a755089b2a0f4da1ba4638eda646d8067f7f2f23.nq.gz
│   ├── ab51ef754e969bcaff26f004b63bcd7251e97c4b.nq.gz
│   ├── b5c7346db4fc4869da1cdad7df1b4ad9005233c4.nq.gz
│   ├── b5d450567b052dcb5a687b21fcc5d67d2229cca7.nq.gz
│   ├── b6db453b88a5e0e700087167008c9f57d1a401cf.nq.gz
│   ├── b91632f5bc787c1404600c894a6a4126359747d8.nq.gz
│   ├── b95c77ab5ec081feebb6fbf506af84ae07088f7b.nq.gz
│   ├── ba3545771d99fd38e4ec05933ad4a62f382e0583.nq.gz
│   ├── ba74e4a41faa179cae094576dbcbc409357b34d7.nq.gz
│   ├── bb76f53941d733b30ccd5962cda3998a1fa5934e.nq.gz
│   ├── bbac4957e92e98b400452ec776264ff53caf25f3.nq.gz
│   ├── bbcbbe7d61558adde3cbfd0c7a63a67c27ed6d30.nq.gz
│   ├── be7fe9b522c4c1a8882f5d6c06366291a928ddfa.nq.gz
│   ├── c525598530365f1e6d687d649907f0c2f116ab8e.nq.gz
│   ├── c6716f9196d80eeca92ea4ba3d62d679cb1a825a.nq.gz
│   ├── c85e73d2b657bb05ed99309615d67bac93d9f86e.nq.gz
│   ├── cd6f86c51337046ef7d1a5258646d399806ac63d.nq.gz
│   ├── d0eda5664ba583d053205e1e01c2f4365648c7f2.nq.gz
│   ├── d3329eec3bac6ce7e54c76b77ac9bf99fab0fe3f.nq.gz
│   ├── d7d9be881a60f00c81c4e02f9b7fe868690ad211.nq.gz
│   ├── d9dfaf5fd0a0a6ed9804870f8948d6c53474aa30.nq.gz
│   ├── de3ae42aae056e9e8e9ce9b016f685823d373e7f.nq.gz
│   ├── dfed17516dec892be7ef7d4c3218aa5469c9148e.nq.gz
│   ├── e004565809cfd14fdd2f4fe7b6f06c43ef9cc21c.nq.gz
│   ├── e006fc0a3c23c2a6599ab1a0213db971dddf88ff.nq.gz
│   ├── e059e98e1ba9f89b51a33c3052c5e746e96e67ed.nq.gz
│   ├── e072ab1b10a8db83e59bd1e764c8d5cd93727c70.nq.gz
│   ├── e16bf234abdd301dfa484d2d07c0ac67efd7395e.nq.gz
│   ├── e41f375774e6945e445bfb179502b128fe22dda7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e88ed387df342b8a16325ecc2ed1dfe8324a516a.nq.gz
│   ├── eb0fb9662e690d0f9de4632cddd321b3f872a725.nq.gz
│   ├── ee59767d651ac114bb580919eb578ddac16cca2a.nq.gz
│   ├── ef8b1c1eeaaa849caf3b908ff17f866d7bcacea2.nq.gz
│   ├── f031bf72b7439a96c40cfe2ad3b46824b9a2e9b8.nq.gz
│   ├── f05e66ef2a031ba8ff2c75f5a1074178b2af332c.nq.gz
│   ├── f647822ff55a53965ef3c8a1fa51fbcb84ee3278.nq.gz
│   ├── fab82673e5fa1d38f07fe7467c372e13fd7cabaf.nq.gz
│   ├── fc182ae20f472a200e4067e9d30f33b622c9d9b6.nq.gz
│   ├── fd64c09b37947c97e58903ce570785c657d56722.nq.gz
│   ├── fdd16445685f425c9fd4092128bda65c32f55ce7.nq.gz
│   ├── feb0ed68d94eac48b844fd587ddfb808649716a1.nq.gz
│   └── ff3e950cd1110fe552912cea4c268c4023d2b737.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 803924b02cc8ca7531b70e6497d1ff7b83f75737.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 104 files
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

[agronholm/llama-cpp-python](https://github.com/agronholm/llama-cpp-python)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
