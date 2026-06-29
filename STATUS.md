# Status

*Stunspot's Guide to Gastronomic Engineering* is a v1.0 public release package built from an existing model-authored gastronomic engineering knowledge corpus.

The repository is stable enough for AI/RAG ingestion, citation by repository metadata, and use as project knowledge. It should be treated as a structured knowledge substrate rather than a consumer-facing cookbook or clinical authority.

## Release Metadata

- Version: 1.0
- Release date: 2026-06-28
- Source reports: 10
- Compiled packs: 3
- Omnibus files: 1
- License notice: CC BY-NC-SA 4.0
- Citation metadata: `CITATION.cff`
- Zenodo metadata: not included in this release

## Corpus Maturity

The source reports are the canonical individual units. Compiled packs and the omnibus are generated convenience formats for model upload, RAG ingestion, long-context use, and archival workflows.

The public documentation now reflects the actual directory policy:

- `docs/` contains navigation and usage guidance only.
- `knowledge-packs/by-report/` contains canonical individual source reports.
- `knowledge-packs/compiled-packs/` contains grouped upload packs.
- `knowledge-packs/omnibus/` contains the whole-corpus bundle.

No `docs/reports/` directory is used or expected.

## Use Boundary

This canon supports culinary formulation reasoning, dietary-constraint mapping, substitution design, and food-system analysis. It is not medical, nutrition, allergen-safety, regulatory, or food-safety advice. Safety-critical uses require qualified validation against authoritative sources and verified ingredient data.
