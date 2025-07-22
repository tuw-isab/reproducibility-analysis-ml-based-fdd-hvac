In the data folder the following files can be found:
- `affil_types.json`: The manual labelled affiliation types of all the authors (used in notebook `2_scopus_api_call.ipynb`)
- `bibliometric_data.json`: A file with all biliometric data for the analyis (is generated in notebook `2_scopus_api_call.ipynb`)
- `papers_reviewed_reprod_variables_catigoric.csv`: The the categorical data of the reproducability variables (main data file)
- `reviewed_papers_unique.csv`: The papers that where investigated in this paper. (DOI, Method, Publisher, Year)

In addition the follwing files for the data analysis will be generated in the notebook `1_preprocessing.ipynb`:
- `reviewed_papers_reprod_variables_numeric.csv`: The numeric representation of the categorical data. 
- `score_class.csv`: Statistics about the classes of reproducability variables according to Table 1.
- `score_dimension.csv`: Statistics about the dimensions of reproducability according to Fig. 3. 
