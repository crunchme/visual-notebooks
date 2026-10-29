# CrunchME visual notebooks

This repository contains the public, reproducible Python notebooks behind selected CrunchME
visuals. Each notebook is available in [`notebooks/`](notebooks/) and can be opened directly in
Google Colab from this repository.

## Using a notebook

1. Open a notebook through its Google Colab link on the corresponding CrunchME visual.
2. Replace `your.email@example.org` with a valid contact email before making PubMed Entrez API
   requests.
3. Run the notebook. Its output is an analysis snapshot; source records can change over time.

The notebooks intentionally contain no personal contact details, access tokens, API keys, or
private Drive paths. The separate CrunchME website repository is the canonical working source;
this is its public notebook release.

## Licensing

- Executable code in notebook code cells is licensed under the [MIT License](LICENSE-CODE).
- Notebook prose, methodology, and generated visual content are licensed under
  [CC BY 4.0](LICENSE-CONTENT.md). Attribute content to CrunchME and link to the applicable
  visual or this repository.
- Data obtained from external sources remains subject to the terms of those sources.

## Contents

[`notebook-manifest.json`](notebook-manifest.json) maps each published CrunchME visual ID to its
notebook file. The public repository deliberately excludes notebooks that do not yet underpin a
published visual.

### UK clinical trials: 2026-10-29-01

The UK trial-registration notebook downloads current records from ClinicalTrials.gov, ISRCTN
and the EU Clinical Trials Register when run. It contains no bundled registry extract or quoted
source passages. The published visual uses records retrieved on **29 October 2026**; later runs
can differ as registrations are added, updated or corrected. Changed review cases stop export
pending reconciliation. Runtime downloads remain subject to each registry's terms.

No Drive mount or local source files are needed. Brutel fonts are optional and must be supplied
under an appropriate licence; a free font fallback is available. Only the chart, aggregate tables
and run metadata are exported by default. Private frozen inputs and record-level audits are not
published in this repository.

## Contact

Rory Preston — [rory@crunchme.org](mailto:rory@crunchme.org)
