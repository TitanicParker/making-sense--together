# Short-Form Recognition Experiment

This note records the internal model experiments used to test the role of the 54 canonical ultra-short expressions.

The purpose was not to prove that the 54 forms are universal, nor to substitute model behavior for human validation. The purpose was narrower: to test whether the present linguistic cues contain enough recoverable structure to lead a reasoner back to the canonical coordinate, and to determine how the different cue layers contribute.

## Three linguistic layers

For each of the 54 coordinates, the experiment used three differently compressed linguistic indicators:

1. **Ultra-short expression** — the canonical phrase used in the manuscript and ledger.
2. **X→Y sentence** — a schematic prose rendering inherited from earlier work.
3. **House-rule sentence** — an ordinary-language sentence selected from a larger set for its portability and recognizability.

These are not definitions. The coordinate and the 15 canonical definitions remain the formal structure.

The working hypothesis is that the three linguistic layers act as complementary recognition cues. Each may underdetermine the coordinate alone while jointly drawing attention toward the same invariant structure.

## Blind triplet recovery

In the first blind recovery test, the classifier saw only the three linguistic indicators. The canonical coordinate labels were withheld until after all classifications were locked.

Result:

| Measure | Recovery |
|---|---:|
| Transformation Pattern | 54 / 54 |
| Completion Topology | 54 / 54 |
| Persistence Mode | 54 / 54 |
| Exact three-axis coordinate | 54 / 54 |

This showed that the complete triplet contained enough recoverable structure for every canonical coordinate to be reconstructed in that experiment.

## Six-condition cue ablation

A second test removed one or more cue layers and classified all 54 cases separately under six conditions.

| Condition | Transformation | Completion | Persistence | Exact coordinate |
|---|---:|---:|---:|---:|
| Ultra-short only | 50/54 (92.6%) | 30/54 (55.6%) | 28/54 (51.9%) | 16/54 (29.6%) |
| X→Y only | 48/54 (88.9%) | 36/54 (66.7%) | 20/54 (37.0%) | 13/54 (24.1%) |
| House-rule only | 43/54 (79.6%) | 50/54 (92.6%) | 45/54 (83.3%) | 31/54 (57.4%) |
| Ultra-short + X→Y | 53/54 (98.1%) | 38/54 (70.4%) | 28/54 (51.9%) | 21/54 (38.9%) |
| Ultra-short + house rule | 52/54 (96.3%) | 52/54 (96.3%) | 47/54 (87.0%) | 43/54 (79.6%) |
| X→Y + house rule | 52/54 (96.3%) | 53/54 (98.1%) | 45/54 (83.3%) | 42/54 (77.8%) |
| **All three cues** | **54/54 (100%)** | **54/54 (100%)** | **54/54 (100%)** | **54/54 (100%)** |

## Interpretation

The ablation pattern matters because it shows that the three cue layers are not simply redundant paraphrases.

The ultra-short expression is especially strong at indicating **Transformation Pattern**.

The X→Y sentence also strongly carries transformation and some completion structure, but is comparatively weak at determining **Persistence Mode** by itself.

The house-rule sentence is the strongest single cue for **Completion Topology** and **Persistence Mode**.

The two strongest pairs are:

- ultra-short + house rule;
- X→Y + house rule.

Neither pair reaches full recovery.

Full recovery occurs when all three layers are available together.

The useful conclusion is therefore:

> **The linguistic indicators can remain individually underdetermining while becoming jointly determinate enough for recognition.**

This is the intended sense in which they function as **attractors**. The openness belongs to the language, not to the canonical distinctions themselves.

## What this does not establish

These are internal semantic robustness experiments, not external validation of a universal taxonomy.

They do not establish that:

- every human reader will recover the same coordinate;
- every formally generated coordinate occurs in ordinary life;
- model recovery proves the ontology of the 54 forms;
- any one cue is sufficient as a definition.

They do establish, within this experimental setup, that:

- the current canonical short expressions are not arbitrary labels;
- the three linguistic layers contribute different information;
- the full triplet supports exact recovery of the canonical field;
- earlier editorial objections that judged an ultra-short expression as though it had to encode all three axes by itself use the wrong standard.

## Editorial consequence

The 54 canonical ultra-short expressions are frozen for the present edition.

They should be assessed as compact recognition cues inside a larger system, not as miniature logical definitions.

A subsequent semantic-field exercise generated ten alternative 3–5 word attractors for each coordinate. The result reinforced a compositional pattern: Transformation supplies the kind of change, Completion supplies the shape of enoughness, and Persistence supplies the mode in which the result remains available.

The full raw generation is not published as part of the site. Five readable, structurally useful, meaningfully varied attractors per coordinate are curated in `semantic-fields.html`. They are presented as a semantic field around the invariant, not as replacements for the canonical expressions.

The public-facing account of the experiments and their limits is available in `method.html`.
