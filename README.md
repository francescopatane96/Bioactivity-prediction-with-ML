# Bioactivity-prediction-with-ML
Create a bioactivity prediction app using molecular descriptors (PADEL) and supervised machine learning (ML).

modules must be used consequently, in order:
- bioprediction_part1: search data for a specific target on Chembl database and make a dataframe, collect IC50 and SMILES values and calculate molecular descriptors by PADEL. Set descriptors as x and pIC50 as y. ** before closing the colab page (part1) you must save on your computer (or in google drive) dataset_with_padel_pIC50.csv file **.
- bioprediction_part2:  ** upload dataset_with_padel_pIC50.csv file **. Compare various ML models and find the best one to utilize for our project.
- bioprediction_part3: Perform linear regression with RandomForest regressor, generate the model (pkl) and predict IC50 of new molecules directly via colab worksheet.

This model is specific for a single target protein choosed by me. if you desire to create a model relative to other targets, you need to fork this project and modify it (see bioprediction_part1 module).
