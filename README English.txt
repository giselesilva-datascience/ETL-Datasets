This project used ETL (Extract, Transform, Load) to process the datasets:
- Indice_Demografico_1900_a_2023.csv
- Natalidade_1900_a_2023.csv

These steps are essential to ensure data quality, reliability, and usability, ensuring consistency for exploratory 
analysis, visualizations, predictive models, and machine learning.

- The ETL was performed entirely in Python, using Visual Studio and Jupter Notebook;
- The Pandas library, Numpy, and the OS module were used;
- Duplicate and unnecessary rows and columns were removed;
- Columns were renamed;
- Inconsistent data was removed or transformed;
- Data was organized into numeric variables;
- Non-numeric data, empty cells, cells with special characters, and nulls were converted to NaN;
 
The dataset is saved in a new file 
- ETL_Indice_Demografico_1900_a_2023.csv 
- ETL_Natalidade_1900_a_2023.csv

This work is a portfolio for general study purposes only. The dataset was retrieved from the public repository, 
via the website https://dados.gov.pt/pt/