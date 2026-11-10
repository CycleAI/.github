# Contributing to CycleAI

Open an issue in the relevant repository to describe a reproducible problem or
propose a change. Include the file or notebook, input assumptions, environment
and observed behaviour. For a research question, identify the paper and analysis
stage so that perception, crash severity and route-planning results stay distinct.

## Code and documentation changes

- Keep pull requests focused and explain what changed and how you checked it.
- Record package versions, random seeds and data provenance when they affect results.
- Explain which inputs are bundled, restricted or obtained from external sources.
- Preserve research attribution and upstream licences. Do not assume a code licence also covers data, imagery or model weights.
- Keep README links and filenames accurate; label historical experiments clearly.

## Data and credentials

Use synthetic examples or approved aggregate data when reporting a problem.
Do not commit participant-level perception-poll records, credentials, private
document links or local configuration. Clear notebook outputs before sharing
unless they have been reviewed for disclosure risks. Inspect ZIP archives too.

The two London paper repositories have sanitized public histories. Start from a
fresh public clone; do not merge an older private clone into the public history.
Follow each repository's `PUBLIC_RELEASE.md` where present.

Do not post a token or sensitive record in a public issue. For a sensitive
disclosure, contact [contact@cycleai.net](mailto:contact@cycleai.net) without
including the secret or raw data in the initial message.
