# DATA205
The main data source is available on dataMontgomery website as a JSON. The file contains information for each towed vehicle over a 12-month period. This project has 3 separate files for the python coding. Part 1 is the Data Ingestion and Wrangling, and Part 2 is the EDA, Visualizations, Statistical Analysis
and Final Product coding. The supplemental is a file also coded in Python but processed by attaching the csv "lr_df" into Google Colab in order to rebalance the
test/train dataset for logistical regression. Anaconda would not recognize the imblearn package in order to use SMOTE, but Google Colab allowed me to process this
part of the analysis. The final product is 3 maps that are saved to interactive html files.
I put the html files in index.md of this repository on the final run. The links are stored there and bring up my github webpage for this repository.
There is a powerpoint presentation explaining the data and analysis, as well as a word document report of the same.
There are places in part 1 and part 2 of the python coding where I read out a csv or read in a csv to my laptop. Those lines will need to be edited/updated to run using your computer pathways. This is true of part 1 where I use the census API and the FCC API; For part 2, I saved the cleaned csv output from part 1 in this repository, so it can be read in with a minor code change at the start of part 2. Also lr_df is the csv saved for the Colab supplemental code needed to rebalance the data for logistical regression.
