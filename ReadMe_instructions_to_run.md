## Data Challenge
- Submitted on January 28, 2018

### Files to Run (Mandatory)

- Final_analysis.ipynb - Main for all the analysis and answers
- Predictive_model.ipynb - For Predictive model with sklearn pipeline for Question 4.
- config.json (inside config folder) - Configuration file to all the parameters used in Predictive_model.ipynb.
- geohash.py - Geohash package from pip is having some issues. So downloaded manually. Need it inorder to run the program. 

### Pickle files to Run Faster (To run faster)

All the pickle data files which generated are stored in ./generated_files folder.

- hash.pkl - Save the hash of each lat/lon location.
- model.pkl - Save the sklearn pipeline object to pickle. To run easily for future predictions.

### Packages required (Mandatory)

- requirments.txt - There are some package dependencies inorder to run the program. This has all the required package files.  

### Run the program

All the coded files are in jupyter notebook format(ipynb). So files needs to be opened using Jupyter application(Either using anaconda or direct Juypter application). If pickle files were not downloaded, it will first create the necessary files. Consecutive runs will be faster.

### Python Version 3.6.1