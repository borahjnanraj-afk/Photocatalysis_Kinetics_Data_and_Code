# Obtain the upstream workbooks

All three third-party XLSX files are omitted from this archive because workbook-specific redistribution terms remain unresolved. Check the exact file before restoring it to a working copy.

| Dataset | Expected file in the staged repository | SHA-256 of the study copy | Access |
| --- | --- | --- | --- |
| Original 443 | data/raw/original_data.xlsx | 6bc6420722aca8bdc23d66e74c882bb255e5f66ee57b9f163df8c41a0a8b3808 | The Solout and Ghasemi repository advertises [original_data.xlsx](https://github.com/mahyavs/GNN_photodegradation/blob/main/data/original_data.xlsx). It identifies [Jiang et al. (2020) supplementary information](https://doi.org/10.1016/j.envres.2020.109697) as the original lineage. |
| Curated 439 | data/raw/curated_data.xlsx | e2265361d04f95fc84145433d57857b810d1cacac577369ed39bb9fbd4a5bfcd | Download [curated_data.xlsx](https://github.com/mahyavs/GNN_photodegradation/blob/main/data/curated_data.xlsx) from the repository linked by [Solout and Ghasemi (2025)](https://www.nature.com/articles/s41598-025-04220-z.pdf). |
| Zhang 570 | zhang_2026_dataset.xlsx | c24c604abacf69f0c036c00f5709fded2001351e5048d912d60c2c6da24389cd | Download dataset.xlsx from the [Zhang Zenodo deposit, v1](https://zenodo.org/records/17768794), cited by [Zhang (2026)](https://doi.org/10.1016/j.jwpe.2026.109531), then use the local filename shown at left. |

The published Zenodo MD5 c97b805788925e30c39dc927d10ac635 matches the local Zhang workbook. The Original and Curated GitHub file locations were verified. The project’s local files were hashed, and a byte comparison to the current upstream GitHub downloads remains unverified. The Jiang paper reports 446 data points, while the local Original snapshot has 443. Treat the Jiang supplement as the upstream lineage and use the checksum to identify the exact study snapshot.

