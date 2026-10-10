# TDVelo

Analysis code and input files for the TDVelo study submitted to PLOS Computational Biology.

## Contents

- `notebooks/TDVelo_original_analysis.ipynb` — analysis workflow.
- `v_*.csv` — velocity matrices used by the notebook.
- `ChEA_attribute_set_library_crisp.gmt` and `ENCODE_attribute_set_library_crisp.gmt` — regulatory gene sets.
- `data/Organoids/organoids.h5ad` — intestinal organoid input.
- `requirements.txt` — Python package dependencies.

## Run

Install the packages listed in `requirements.txt`, then open and run the notebook in Jupyter. The notebook defaults to `intestinal_organoid`; select another dataset by changing `args.dataset_name` in the first code cell. Install Git LFS before cloning this repository to retrieve the large input files.

## Data sources

- Intestinal organoid: [GEO GSE128365](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE128365)
- Gastrulation: [Figshare file](https://ndownloader.figshare.com/files/27686871)
- Dentate gyrus: [DentateGyrus.loom](https://pklab.med.harvard.edu/velocyto/DentateGyrus/DentateGyrus.loom)
- Pancreas: [scVelo notebooks repository](https://github.com/theislab/scvelo_notebooks)

## Availability and citation

Repository: https://github.com/cellwj/TDVelo  
Version: v1.0.0 (initial submission snapshot).

Cite the associated TDVelo manuscript when using this code. The manuscript Data Availability Statement should identify the code repository and the data repositories/accessions listed above.

## License

Add the rights-holder-approved software license in `LICENSE`.
