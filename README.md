# ParkinsonsDisease
This project is a collaborative research project between Mayo Clinic (Dr. Rodolfo Savica, Dr. Nathan Schilaty, and Aidan Mullan) and Billings Clinic (Dr. David Hedges) to use machine learning on a dataset curated from the Rochester Epidemiology Project. Although this data contains a relatively small number of intances, it is quite broad (large number of features) and has very little missing data. Given the small sample size, the purpose of the project from conceptualization was a proof of concept that unsupervised machine learning could be used to cluster subtypes of Parkinson's disease utilizing data found only in the electronic health records.

This project is focused on discovery of complex correlations within the dataset and, in particular, with cardinal symptoms and subtypes of Parkinson's disease. The project is currently under review, and if published, a brief summary of findings will be included here.

# Dependencies
This project was done using an already curated dataset. All analytics were completed using Python 3.7.7 and the following libraries: Pandas (1.0.5), Sci-Kit Learn (0.23.1), MatplotLib (3.2.2), XGBoost (1.1.1), Imblearn (0.7.0), and Seaborn (0.11.1).

# Code
Preprocessing.ipynb. This notebook contains the pipeline used to prepare the data for machine learning.
Clustering.ipynb. This notebook contains the details for the unsupervised learning portion of the project.
Classification.ipynb. This notebook contains the final, supervised learning portion of the project.
