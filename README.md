# omicverse-data

Dataset release assets for [omicverse](https://github.com/Starlitnightly/omicverse).
Files here are downloaded on demand by `omicverse.datasets` loaders and
cached locally.

## Proteomics (`proteomics-v1` release)

Real, published proteomics datasets used by the `ov.protein` tutorials:

| Asset | Source | Description |
|---|---|---|
| `protein_pxd000022.h5ad` | ProteomeXchange PXD000022 (via Bioconductor imputeLCMD) | Label-free LC-MS/MS, 660 proteins × 6 samples, 2 groups (MB/MT) |
| `protein_pxd000438.h5ad` | ProteomeXchange PXD000438 (via imputeLCMD) | Label-free LC-MS/MS, 3709 proteins × 12 samples, 4 groups, ~41% left-censored missing |
| `protein_msstats_dda.csv.gz` | MSstats `DDARawData` | Controlled spike-in label-free DDA, feature-level (MSstats long format) |
| `protein_msstats_dia.csv.gz` | MSstats `DIARawData` | Label-free DIA, S. Pyogenes group comparison (MSstats long format) |
| `protein_olink_npx.csv.gz` | OlinkAnalyze `npx_data1` | Olink Explore NPX, long format, real bridging study |

Each dataset is redistributed from its open-source Bioconductor / CRAN
package (imputeLCMD GPL-3, MSstats Artistic-2.0, OlinkAnalyze AGPL-3);
original data are public ProteomeXchange / published study examples.
