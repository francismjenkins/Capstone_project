# Capstone_project
# Frank Jenkins - Springboard, Intermediate Python

Differential gene expression analysis of TCGA dataset containing expression data for normal and kidney cancer cells

This project will seek to elucidate on differential gene expression between cancer and normal cells. The dataset used was taken from The Cancer Genome Atlas (TCGA). The cancer type under investigation is clear cell renal carcinoma.

The first step was to set the working directory to the folder containing the dataset. Next, the dataset was read into a Jupyter 
Notebook and assigned to an object. The dataset was imported as a csv file using the python module pandas. 

Because the dataset contains gene expression values for both normal and cancer cells, the dataset was broken up into two parts. 
The last two digits in the column headers tells us whether a column contains expression values from cancer or normal cells.
Regular expressions were used to filter the data (and separate cancer from normal cells).  

The original dataset has been log2 transformed and normalized, which reduces the number of steps needed to preprocess the data. 
The analytics will be done using only pythonic techniques.

