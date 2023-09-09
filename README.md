# automatic-feature-extraction-for-battery-SOH-and-EOL-prediction

This code repository provides a valuable resource for researchers and practitioners interested in battery cycle life prediction. It covers data preprocessing, feature engineering starting from data provided with the paper "Data driven prediction of battery cycle life before capacity degradation" by K.A. Severson, P.M. Attia, et al.

The repository contains two Jupyter notebook files. The first notebook, named "STEP1_Authomated_features_extraction", focuses on processing the raw data to generate relevant features. This files involves a novel algorithm to extract meaningful features automatically from the raw data. The starting point for the extraction of features are the files batch1, batch2, and batch3, retrieved from the BuildPkl_Batch-jupyter-notebook files contained in the GitHub repository associated with the work of K.A. Severson et al. The second notebook, named "STEP2_Data_cleaning&collection", focuses on feature cleaning and collection. It prepares the extracted features from step 1 to be used as input for machine learning models.

To ensure reproducibility, the code includes a requirements.txt file that specifies the package settings used in their work. This file can be used to recreate the necessary environment and install the required packages for running the code successfully.
