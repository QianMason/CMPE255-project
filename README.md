# CMPE255-project

## Usage

The following notebooks can utilized in the following order to logically follow the project implementation design.
First, run "accident_severity_data_processing.ipynb" notebook to generate dataset characteristics and dataset reduction. 
This will generate a reduced dataset. You can then feed that into the second notebook "accidents_sklearn_model_comparison.ipynb"
to run the models and compare model performance. It will also be used to generate the dataset used for the visualization. Finally, the "map.ipynb" can be loaded with the last dataset, which houses actual vs. predicted values and generates a heatmap. 

The dataset can be located here:
https://www.kaggle.com/sobhanmoosavi/us-accidents/version/6

A random sample consisting of 20% of the whole dataset has been provided in the repository. The filename is "sample20.csv.zip".