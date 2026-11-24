# Frictional: Measuring the Struggle

## Executive summary

- **What this is:** the paper repo for the Frictional preprint, *Measuring the Struggle: Process Friction Traces as Independent Evidence of Genuine Learning in the Age of Generative AI*, by Nik Bear Brown. Private.
- **What the paper argues:** generative AI lets a student produce the artifact without the learning, so the artifact alone no longer proves learning. The paper proposes a second evidence stream, the Genuine Learning Probability (GLP) framework, built from seven observable friction components.
- **Where it stands (2026-11-24):** published as a preprint on nikbearbrown.com on 2026-07-15. It has not been submitted to a venue. This repo holds the preprint text with its wording unchanged.

## Contents

- [paper/preprint.md](paper/preprint.md): the preprint in Markdown. The wording matches the published page; only the formatting was changed in the conversion.

## Known problems in the preprint

These were recorded on 2026-11-22 and are not fixed in this text:

- The neuroscience figures in Section 3 (BDNF and dendritic spines) trace to a single review whose cited studies do not measure them.
- "Tier" terminology, which is to become "facet".
- Y₄_dir is undefined.
- The "credible interval" wording.
- The validation design in Section 7 builds its labels from the same evidence the model scores.

## This repo is one of four separate things

| Thing | Where | What it is |
|---|---|---|
| The Frictional preprint | this repo | The original paper and its GLP framework |
| The Frictional skill | [nikbearbrown/frictional](https://github.com/nikbearbrown/frictional) (public) | An audit tool that reports evidence of how student work was made. It is not this paper and computes no GLP score. |
| Auditing the Making | [nikbearbrown/auditing-the-making](https://github.com/nikbearbrown/auditing-the-making) (private) | Follow-on paper 1: the auditor tested on a synthetic benchmark. Its `source/` folder holds a working copy of this preprint for revision. |
| Process Evidence in Practice | [nikbearbrown/process-evidence-in-practice](https://github.com/nikbearbrown/process-evidence-in-practice) (private) | Follow-on paper 2: the classroom study |

The book version is separate again, in `nikbearbrown/frictional-book` (private).
