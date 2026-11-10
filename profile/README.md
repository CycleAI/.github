# CycleAI

**Research and software for safer cycling.**

We study perceived street safety, cyclist crash severity and route planning using
street-view imagery, geospatial data and machine learning.

[Website](https://www.cycleai.net) · [Research and code](https://github.com/orgs/CycleAI/repositories?type=public)

## London cycling-safety research

| Project | Research question | What you can explore |
| --- | --- | --- |
| **[Paper 1 · Cycling safety perception with vision-language models](https://github.com/CycleAI/Cycle-Safety-Perception-VLM)** | Can a vision-language model approximate human judgements of cycling safety? | Pairwise comparisons, aggregate TrueSkill rankings, nine analysis notebooks and paper figures. |
| **[Paper 2 · Cyclist crash severity in Greater London](https://github.com/CycleAI/London-Cyclist-Crash-Severity-Prediction)** | Which pre-crash contextual features help distinguish serious/fatal from slight injuries? | The 41,606-crash study, chronological evaluation, fitted models, held-out predictions and figures. |

**For a quick review:** start with each paper's README, inspect the saved figures
and results, then follow the notebook and data guides. Each repository explains
which inputs are available and what is required to reproduce the analysis.

Perceived safety and injury severity answer different questions. The severity
study is conditional on a recorded crash; it does not estimate crash occurrence
or risk per journey.

## Other public projects

| Repository | Scope |
| --- | --- |
| [Lisbon-Hub](https://github.com/CycleAI/Lisbon-Hub) | CycleAI's fork of the VoxPop Lisbon collaboration: route comparisons, analysis notebooks and streetscape heatmaps. |
| [LisbonHUB](https://github.com/CycleAI/LisbonHUB) | Earlier standalone Lisbon snapshot. Its README explains the relationship to the collaboration fork. |
| [accidents-map](https://github.com/CycleAI/accidents-map) | Standalone exploratory London collision viewer. For the paper analysis, use Paper 2 above. |
| [CycleAI](https://github.com/CycleAI/CycleAI) | Original project overview, early training prototype and historical materials. |

## Using and contributing to the research

Raw perception-poll participant records and credentials are not included in the
two public London paper releases. Aggregate rankings, synthetic votes and the
available research outputs are documented in their data guides.

Check each repository's data availability, environment instructions and licence
before reuse. Some analyses require additional inputs or your own API access;
the public packages are not claimed to be complete automatic rebuilds.

For a code or documentation question, open an issue in the relevant repository.
See the [contribution guide](https://github.com/CycleAI/.github/blob/main/CONTRIBUTING.md)
before sharing files. For research enquiries: [contact@cycleai.net](mailto:contact@cycleai.net).
