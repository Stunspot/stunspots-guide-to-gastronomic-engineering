# How to Use This Canon

*Stunspot's Guide to Gastronomic Engineering* is built for model-facing use first. Humans can read it, but its highest-value deployment is as project knowledge, RAG substrate, long-context reference material, or agent doctrine for culinary formulation reasoning.

The corpus is not a consumer recipe collection. It is a control-language substrate for answering formulation questions with better physical grounding: what phase state is involved, what variable is mis-set, what function was removed, and which replacement mechanism restores the target behavior.

---

## Recommended Starting Point

For most AI/RAG systems, start with the **compiled packs** in `knowledge-packs/compiled-packs/`.

| Format | Path | Best For |
|---|---|---|
| Source reports | `knowledge-packs/by-report/` | Precise retrieval, selective upload, citation, editing, and per-report inspection. |
| Compiled packs | `knowledge-packs/compiled-packs/` | Recommended default for most systems: three grouped files with coherent coverage. |
| Omnibus | `knowledge-packs/omnibus/` | One-file import, local archive, or strong long-context/RAG systems. |

The individual source reports are canonical. The compiled packs and omnibus are convenience formats generated from those reports.

---

## For Human Readers

Read by problem, not by cover-to-cover obligation.

- For the **basic operating language**, read A-C.
- For **low-carb, glycemic, high-protein, low-calorie, satiety, or macro-controlled formulation**, read D-F.
- For **whole-food, plant-based, allergen-free, low-FODMAP, gut-comfort, microbiome, or tolerance-oriented formulation**, read G-J.

A useful reading posture is to ask:

1. What is the target food's actual phase state: solid, liquid, gas, emulsion, gel, foam, suspension, or hybrid colloid?
2. What structural function is being added, removed, or degraded?
3. Which global control variable is driving success or failure: temperature, time, water activity, pH, ionic strength, shear, pressure, particle size, viscosity, or phase geometry?
4. Which dietary or ingredient constraint is active?
5. Which substitution graph or material class restores the missing function?

This is the unromantic part where the soufflé stops being a mood and becomes a weak gel with gas retention issues. Much more useful, annoyingly.

---

## For AI Projects and ChatGPT-Style Knowledge Uploads

Use the **compiled packs** unless the target system has unusually strong retrieval and file-management behavior.

Recommended upload set:

1. `knowledge-packs/compiled-packs/knowledge-gastronomic-engineering-vol-1-a-c-fundamentals-and-worldview.md`
2. `knowledge-packs/compiled-packs/knowledge-gastronomic-engineering-vol-2-d-f-constraint-layers-for-specialty-dietary-needs-1-carbs-proteins-and-caloric-density.md`
3. `knowledge-packs/compiled-packs/knowledge-gastronomic-engineering-vol-3-g-j-constraint-layers-for-specialty-dietary-needs-2-whole-foods-plant-based-allergen-free.md`

Then add an instruction similar to:

```text
Use Stunspot's Guide to Gastronomic Engineering as a formulation-physics and dietary-constraint knowledge substrate. Treat it as model-facing doctrine for phase-state analysis, control-variable diagnosis, substitution mapping, and constraint-aware culinary reasoning. Preserve report codes and source paths in citations when possible. Do not treat the canon as medical, nutrition, allergy, or food-safety authority; escalate safety-critical claims to qualified sources and verified labels.
```

---

## For RAG Pipelines

The reports are dense, table-heavy, and operational. Chunking should preserve structure.

Recommended ingestion behavior:

- Preserve report code and title in metadata: `A`, `B`, `C`, etc.
- Preserve full source path, not just filename.
- Keep section headings attached to chunks.
- Keep table rows near their header row and lead-in paragraph.
- Avoid tiny chunks that detach a substitution mapping from its constraint vector.
- Add metadata fields for dietary mode, phase state, material class, control variable, and failure mode where your pipeline supports enrichment.
- Prefer deterministic metadata filters for obvious routes: low-carb → D, high-protein → E, caloric density → F, whole-food → G, plant-based → H, allergen-free → I, digestive/microbiome → J.

Suggested metadata fields:

```json
{
  "canon": "stunspots-guide-to-gastronomic-engineering",
  "version": "1.0",
  "report_code": "D",
  "report_title": "Low-Carb and Glycemic Control",
  "source_path": "knowledge-packs/by-report/d-low-carb-and-glycemic-control.md",
  "primary_domain": "glycemic-control",
  "constraint_layer": "low-carb",
  "content_type": "source-report"
}
```

---

## For Long-Context Use

Use the omnibus only when the model can keep headings, report boundaries, and table context intact across a large file. If the model starts flattening the corpus into generic cooking advice, switch back to compiled packs or individual reports.

Good long-context tasks:

- broad synthesis across dietary constraints
- comparing substitution logic between reports
- building a domain ontology
- extracting reusable formulation primitives
- generating a structured assistant system prompt or RAG schema from the corpus

Weak long-context tasks:

- pinpoint lookup into a table-heavy section
- exact citation retrieval
- safety-critical allergen or clinical recommendations
- narrow recipe adaptation where one report would be cleaner

---

## For Recipe Adaptation

Use this sequence:

1. **State the target food** as a phase system: emulsion, foam, gel, baked matrix, frozen emulsion, particulate solid, sauce, suspension, etc.
2. **Name the constraint**: low-carb, high-protein, low-calorie, whole-food, plant-based, allergen-free, low-FODMAP, reflux-aware, and so on.
3. **Identify the lost function**: bulk, water retention, browning, sweetness curve, emulsification, foam generation, heat-set coagulation, gelation, fat-phase lubricity, aroma buffering, or digestive tolerance.
4. **Route to the report** that owns the constraint.
5. **Use the substitution graph** or material class to rebuild function.
6. **Check the control variables** before presenting the answer.

Example routing:

| User asks for... | Route first to... | Why |
|---|---|---|
| Keto caramel or sugar-free hard candy | D | Sweetener systems and amorphous glass engineering. |
| Protein pancakes or protein pudding | E | High-protein hydration, gelation, chalkiness, and macro-displacement logic. |
| Low-calorie creamy sauce | F | Energy dilution, fat replacement, water loading, and sensory compensation. |
| Paleo/Whole30 mayonnaise | G | Whole-food emulsification without industrial stabilizers. |
| Vegan cheese melt | H | Animal-function displacement and plant-fat/starch emulsion-gel design. |
| Gluten-free, egg-free, dairy-free muffin | I | Stacked allergen exclusion and binder-loss burden mapping. |
| Low-FODMAP onion/garlic replacement | J | Hidden trigger ontology and digestive substitution graphs. |

---

## Model Behavior Guidance

When an assistant uses this canon, prefer this response pattern:

1. **Classify the request** by report route and constraint layer.
2. **Translate culinary terms into physical functions.**
3. **Name likely failure modes.**
4. **Recommend replacement mechanisms with control notes.**
5. **State safety limits plainly.**
6. **Cite or reference the source report path where possible.**

Avoid presenting unsupported medical, therapeutic, allergen-safety, or food-safety claims as settled authority. The canon can guide formulation reasoning; it does not replace clinical care, regulatory review, or verified ingredient-label analysis.
