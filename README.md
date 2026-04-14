# yama-cli (legacy)

> [!WARNING]
> **This repository is archived and no longer maintained.**
>
> This is the legacy Nunjucks-based `yama-cli` (v0.x). 
>
> **For new work, use the current CLI:**
> **<https://github.com/yamaml/yama-cli>**
>
> The current CLI is published on JSR as `@nishad/yama` and tracks the
> [YAMAML 0.2.0 specification](https://docs.yamaml.org/specs/yamaml/spec/).
> It is documented at **<https://docs.yamaml.org>**.
>
> This repository is preserved here for historical reference.

---

## Original README

A CLI utility to work with YAMA and YAMAML files.

```bash
usage :

	shex
		Generate ShEx from YAMA
		yama shex -i [path/to/yama/file] -o [path/to/output/shex/file]
	rdf
		Generate RDF from YAMAML
		yama rdf -i [path/to/yama/file] > [path/to/output/rdf/file]
```

To run use Deno runtime:

```bash
deno run --unstable --allow-all --no-check yama.js
```

Compile yama binary using Deno:

```bash
deno compile --unstable --allow-all --no-check --output yama yama.js
```

### YAMA to RDF

![YAMA to RDF](docs/images/yama-to-rdf.png)

### YAMA to ShEx
![YAMA to ShEx](docs/images/yama-to-shex.png)
