# Reproducibility and provenance

## Associated paper

**StochLOB: Heavy-Tailed Score Matching for Robust Limit Order Book Trend Prediction**

- [arXiv preprint](https://arxiv.org/abs/2610.21081)

## Scope of the replication materials

The repository contains research implementations, configuration files and scripts supporting the paper, as well as additional experimental pipelines. The manuscript defines the datasets, model variants and results included in the reported study. A configuration or model being present in the repository does not, by itself, establish that it was used for a particular paper result.

A validated, paper-specific release has not yet been designated. The commands in the main README demonstrate individual training and evaluation workflows; they are not a complete table-by-table reproduction manifest. Record the exact code revision used for each reproduction rather than relying on a moving branch name.

## Funding and computational resources

This study received no project-specific research funding. No computing resources from Virginia Tech or the authors' other affiliated universities were used in this study.

## Data sources and access

The analyses used publicly available market data. The paper's data section and data appendix describe coverage, preprocessing and chronological splits. See [the data documentation](docs/data/README.md) for the implemented pipelines.

Raw and resampled working datasets are tracked through DVC rather than stored directly in Git. Access to the project's stored DVC copies is separate from access to the original public sources and is subject to permission and applicable source-data terms. Access to this code repository does not grant access to the storage remote or permission to redistribute data.

Configure authorized storage credentials locally, as described in the main README. Credentials, private datasets and restricted outputs must not be committed or posted in issues. Recollecting a live market feed at a later date does not recreate the historical sample used in the paper.

## Software provenance and attribution

The Git history preserves the available record of code changes and their authors. GitHub's contribution graph reflects commit metadata and is not a complete account of research contributions. Preparing or uploading a replication package should not be treated as authorship of all code it contains.

Manuscript authorship and institutional affiliations are reported in the paper. Hosting the repository under the Dataism Laboratory for Quantitative Finance does not assign a laboratory or university affiliation to every contributor. Any detailed contribution statement should reflect the work actually performed and be confirmed by the contributors.

## Information to retain for each reproduced result

- Paper version and the table, figure or experiment being reproduced.
- Exact Git commit or release tag and configuration file path.
- Dataset version or DVC hash, source coverage, preprocessing and chronological splits.
- Label horizon, calibration settings and random seeds.
- Dependency lockfile, Python and framework versions, and relevant hardware details.
- Checkpoint selection rule, evaluation command and generated result files.

A future paper-specific release should map each reported result to these materials. Subsequent corrections should be documented in a separate release so the original result-to-code mapping remains identifiable.

## Licensing and reuse

The code is distributed under the repository's existing [MIT licence](LICENSE), subject to any separately identified third-party terms. That licence does not grant rights to third-party datasets, storage accounts or other external resources. Consult the relevant source terms before redistributing data or derived materials.
