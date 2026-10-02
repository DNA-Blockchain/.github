# RabbitSoftware

**Local-first biomedical literature research, source-linked answers, and interoperable research data—alongside experimental systems software.**

RabbitSoftware is open-source research software by Chase Allen Ringquist. Its Python research tools query public biomedical sources and produce citation-linked records and answers. The project also includes signed peer-to-peer provenance and audit tooling, plus a separate experimental Rust x86_64 kernel tested in QEMU.

| | |
|---|---|
| Main repository | [DNA-Blockchain/Helloworld](https://github.com/DNA-Blockchain/Helloworld) |
| Latest release | [RabbitSoftware 0.10.1](https://github.com/DNA-Blockchain/Helloworld/releases/tag/v0.10.1) |
| License | [UPL-1.0](https://github.com/DNA-Blockchain/Helloworld/blob/master/LICENSE) |
| Authorship | [NOTICE.md](https://github.com/DNA-Blockchain/Helloworld/blob/master/NOTICE.md) |
| Privacy | [PRIVACY.md](https://github.com/DNA-Blockchain/Helloworld/blob/master/PRIVACY.md) |

## Use and integrate the research data

RabbitSoftware offers portable exports and a documented provenance format that does not require adopting its blockchain:

- **Integration guide:** formats, tested versions, and ways to propose integrations.
- **Source adapters:** worked requests, responses, attribution, and failure behavior for public biomedical sources.
- **Provenance format:** portable JSON describing source, identifier, capture time, and terms.
- **Tutorial:** take public literature records into Zotero or another reference manager and a notebook.
- **Example dataset:** 15 public records with BibTeX, RIS, CSV and JSONL exports, checksums, and an offline verification/regeneration script.

See the [integration guide](https://github.com/DNA-Blockchain/Helloworld/blob/master/docs/integration.md), [source adapters](https://github.com/DNA-Blockchain/Helloworld/blob/master/docs/sources/README.md), [provenance format](https://github.com/DNA-Blockchain/Helloworld/blob/master/docs/api/provenance.md), [Zotero tutorial](https://github.com/DNA-Blockchain/Helloworld/blob/master/docs/tutorials/literature-to-reference-manager.md), and [example dataset](https://github.com/DNA-Blockchain/Helloworld/tree/master/examples/research).

## Collaborate

For a new source adapter, export format, reproducibility improvement, or integration idea, open an [issue](https://github.com/DNA-Blockchain/Helloworld/issues) describing the use case and source/API involved. Please do not post private or personal records in issues or example datasets.

## Get started and project boundaries

The [main README](https://github.com/DNA-Blockchain/Helloworld#readme) has Windows, Linux, and WSL installation instructions and documents the project's components and limitations. RabbitSoftware is research software, not a clinical or diagnostic tool. Experimental components are labeled in the repository; hosted model assets and cloud sync remain private until launch.
