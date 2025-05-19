# Analyzing Drug-Gene Interactions for Hypertension
This project explores drug-gene interactions relevant to hypertension by using genomic tools and public APIs such as [DGIdb](https://www.dgidb.org/) and [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/). Python was used to automate queries, process data, and visualize findings related to potential therapeutic targets.

## Objective
To investigate how drug-gene interactions can inform better treatment strategies for hypertension by using genomic databases and API-driven data analysis.

## Methodology
- **DGIdb API & GraphQL Playground**  
  Queried drug-gene interactions for hypertension-linked genes using the DGIdb API and tested queries using GraphQL.
  
- **ClinVar API via Biopython (Entrez)**  
  Retrieved gene variant data related to hypertension for deeper genomic analysis.

- **Python Libraries**  
  - `requests` for API calls  
  - `pandas` for data structuring  
  - `matplotlib` and `seaborn` for data visualization

## How to Run
1. Install & import required Python packages (see notebook cell for setup)
2. Insert path to source CSV file that includes drug categories and associated genes to be extracted from 
3. Run each cell in order

## References
- [DGIdb API Docs](https://dgidb.org/api)
- [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/)
- [NCBI Entrez Programming Utilities](https://www.ncbi.nlm.nih.gov/books/NBK25500/)
