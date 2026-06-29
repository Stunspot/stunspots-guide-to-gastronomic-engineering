# Knowledge Packs — Stunspot's Guide to Gastronomic Engineering

The repository contains three operational corpus formats. They all represent the same canon, but they are optimized for different upload, retrieval, and reading conditions.

The canonical individual reports live in `knowledge-packs/by-report/`. The compiled packs and omnibus are convenience formats generated from those reports.

---

## Recommended Default

Use the **compiled packs** unless you have a specific reason not to.

They are the best default for AI Projects, RAG workspaces, NotebookLM-style tools, and long-context systems with file-count limits. Three files are usually easier for a model to route than ten separate reports, while still preserving the major canon arcs better than one giant omnibus.

---

## Format Selection Matrix

| Pack Type | Files | Path | Best Use | Trade-Off |
|---|---:|---|---|---|
| Source reports | 10 | `knowledge-packs/by-report/` | Precise retrieval, selective upload, exact citation, editing, and inspection. | More files to manage; requires better routing. |
| Compiled packs | 3 | `knowledge-packs/compiled-packs/` | Recommended default: grouped coverage with manageable file count. | Less granular than source reports. |
| Omnibus | 1 | `knowledge-packs/omnibus/` | One-file import, local archive, whole-corpus search, strong long-context systems. | Large single file; weaker for pinpoint retrieval in some tools. |

---

## Use Source Reports When...

Choose `knowledge-packs/by-report/` when the task requires precision.

Good use cases:

- building a vector database with per-report metadata
- citing exact source-report paths
- editing or auditing one report at a time
- testing retrieval quality against specific dietary domains
- uploading only one domain, such as allergen-free or low-FODMAP formulation

Source reports:

- [A. Strategic Formulation Modules in Food Physics](https://github.com/Stunspot/stunspots-guide-to-gastronomic-engineering/blob/main/knowledge-packs/by-report/a-strategic-formulation-modules-in-food-physics.md)
- [B. A Closed-Loop Architecture for Culinary Formulation](https://github.com/Stunspot/stunspots-guide-to-gastronomic-engineering/blob/main/knowledge-packs/by-report/b-a-closed-loop-architecture-for-culinary-formulation.md)
- [C. Experimental Protocols and the Closed-Loop Architecture](https://github.com/Stunspot/stunspots-guide-to-gastronomic-engineering/blob/main/knowledge-packs/by-report/c-experimental-protocols-and-the-closed-loop-architecture.md)
- [D. Low-Carb and Glycemic Control](https://github.com/Stunspot/stunspots-guide-to-gastronomic-engineering/blob/main/knowledge-packs/by-report/d-low-carb-and-glycemic-control.md)
- [E. High-Protein Systems Constraint Layer](https://github.com/Stunspot/stunspots-guide-to-gastronomic-engineering/blob/main/knowledge-packs/by-report/e-high-protein-systems-constraint-layer.md)
- [F. Caloric Density Control and Energy-Diluted Matrix Engineering](https://github.com/Stunspot/stunspots-guide-to-gastronomic-engineering/blob/main/knowledge-packs/by-report/f-caloric-density-control-and-energy-diluted-matrix-engineering.md)
- [G. Whole-Food and Processing-Constrained Formulation — A Physics-First Constraint Layer](https://github.com/Stunspot/stunspots-guide-to-gastronomic-engineering/blob/main/knowledge-packs/by-report/g-whole-food-and-processing-constrained-formulation.md)
- [H. Plant-Based Systems and Animal-Function Displacement](https://github.com/Stunspot/stunspots-guide-to-gastronomic-engineering/blob/main/knowledge-packs/by-report/h-plant-based-systems-and-animal-function-displacement.md)
- [I. Allergen-Free Substitution Systems and Physics-First Constraint Architecture](https://github.com/Stunspot/stunspots-guide-to-gastronomic-engineering/blob/main/knowledge-packs/by-report/i-allergen-free-substitution-systems-and-physics-first-constraint-architecture.md)
- [J. Digestive and Microbiome Modulation Systems](https://github.com/Stunspot/stunspots-guide-to-gastronomic-engineering/blob/main/knowledge-packs/by-report/j-digestive-and-microbiome-modulation-systems.md)

---

## Use Compiled Packs When...

Choose `knowledge-packs/compiled-packs/` for most model-facing workflows.

Good use cases:

- ChatGPT Project knowledge
- Claude Project knowledge
- NotebookLM-style study and synthesis
- compact RAG corpora where file count matters
- assistants that need the whole canon but benefit from major section boundaries

Compiled packs:

1. [Gastronomic Engineering — Vol. 1 A-C — Fundamentals and Worldview](https://github.com/Stunspot/stunspots-guide-to-gastronomic-engineering/blob/main/knowledge-packs/compiled-packs/knowledge-gastronomic-engineering-vol-1-a-c-fundamentals-and-worldview.md)
2. [Gastronomic Engineering — Vol. 2 D-F — Constraint Layers for Specialty Dietary Needs I](https://github.com/Stunspot/stunspots-guide-to-gastronomic-engineering/blob/main/knowledge-packs/compiled-packs/knowledge-gastronomic-engineering-vol-2-d-f-constraint-layers-for-specialty-dietary-needs-1-carbs-proteins-and-caloric-density.md)
3. [Gastronomic Engineering — Vol. 3 G-J — Constraint Layers for Specialty Dietary Needs II](https://github.com/Stunspot/stunspots-guide-to-gastronomic-engineering/blob/main/knowledge-packs/compiled-packs/knowledge-gastronomic-engineering-vol-3-g-j-constraint-layers-for-specialty-dietary-needs-2-whole-foods-plant-based-allergen-free.md)

Recommended model instruction:

```text
Use these compiled packs as the active gastronomic engineering knowledge substrate. Preserve report letters and source paths where possible. Route formulation questions through phase-state analysis, lost-function mapping, constraint identification, and control-variable diagnosis before recommending substitutions or process changes.
```

---

## Use the Omnibus When...

Choose `knowledge-packs/omnibus/` when you need the entire corpus in one file.

Good use cases:

- local archive
- whole-corpus grep/search
- one-file import tools
- long-context models with strong document navigation
- corpus-level synthesis, ontology extraction, or doctrine compression

Omnibus:

- [Gastronomic Engineering — Omnibus](https://github.com/Stunspot/stunspots-guide-to-gastronomic-engineering/blob/main/knowledge-packs/omnibus/knowledge-gastronomic-engineering-omnibus.md)

Use the omnibus with caution in weaker long-context environments. If the model starts answering generically or loses report boundaries, switch back to compiled packs.

---

## RAG Ingestion Recommendations

For retrieval systems, treat the corpus as a structured doctrine set, not a flat pile of Markdown.

Minimum metadata to preserve:

- canon title
- canon version
- report code
- report title
- source path
- heading path
- pack type
- dietary or formulation domain, when obvious

Recommended routing hints:

| Domain | First Report Route |
|---|---|
| food physics, phase states, control variables | A |
| closed-loop formulation, predictive control | B |
| experimental protocols, practicums | C |
| low-carb, keto, glycemic control, sugar-free | D |
| high-protein, satiety, protein fortification | E |
| low-calorie, volumetric, energy density | F |
| whole-food, paleo, Whole30, clean-label | G |
| vegan, vegetarian, dairy-free, egg-free | H |
| allergen-free, gluten-free, multi-allergen | I |
| low-FODMAP, microbiome, reflux, digestive tolerance | J |

Chunking guidance:

- Keep section headers attached to body chunks.
- Keep tables with their explanatory text.
- Avoid splitting substitution graphs into orphaned rows.
- Preserve report-code metadata even when ingesting compiled packs or the omnibus.
- Treat dietary, allergen, and digestive content as formulation support, not clinical authority.

---

## Directory Boundary

`docs/` is only for navigation and usage guidance. Do not create `docs/reports/` or mirror the corpus into the docs tree. The corpus belongs under `knowledge-packs/`.
