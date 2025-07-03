# pubmedGEO_datasets

A prototype for a recruitment task involving mapping scientific publications (PMIDs) to associated datasets in the GEO database (GSE IDs), using the NCBI E-Utils API.

## What the notebook does:
- Retrieves datasets ids from GEO database from PubMed ids.
- Creates a dictionary gds_dict storing datasets metadata: associated PubMed papers ids, title, summary, organism, type of experiment, cluster_id (after clustering). gds_ids are the keys.
- Encoding the datasets descriptions using tf-idf
- Clustering
- Simple visualisation (interactive visualisation not yet added

## How to run
1. Place `PMIDs_list.txt` in the root directory
2. Open and run the `Prototype.ipynb` notebook step by step

## Status
The notebook covers the initial data retrieval part, metadata extraction, TF-IDF vectorization, clustering and visualization. Interactive elements and a web service are not yet implemented.
