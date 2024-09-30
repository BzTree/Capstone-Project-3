# Capstone-Project-3

## Edit on 30/9/2024:
Added a Version 2 of the .ipynb file, which has the following changes:

- No code was changed. Only markdowns were edited.
- Removed the 'remove two-year subscription' recommendation to the business, but kept the other recommendation related to this subscription length, given the high importance of the feature in the evaluation stage of this model.
- Modified the second and third recommendations to the business to better tie it to the monetary calculations of the ML model made just before this segment.
- Duplicated a copy of the model's limitations to the summary for reader's convenience.
- Added a very brief explanation of the recall score at the beginning of the file which is relevant to the context of the project.
- Added the reason why we used Machine Learning for making the model at the beginning of the .ipynb notebook.
- Added the limitation of the 'Contract' column to the list of limitations.

The previous file is not deleted, hence both files can be accessed.

-------------------------------------------------------------------------------------------------------------------------------

This repository is built for the purpose of containing the files needed for Capstone Project 3 of JCDSOL15.
The following files are available in this repository:

- .ipynb notebook containing the whole process of processing the data and training the model to predict churn, from analyzing effect of different data cleaning mechanisms to comparing different hyperparameters on the best models and rebalancers as determined through experiment.
- The presentation to better visually assess the effectiveness of the Machine Learning (ML) model vs the rule-based model.
- The 'pickle' file containing the final model as determined in both the presentation and the notebook.
- This README, containing the summary of this repository.

In building the ML model, the processing of the dataset can be summarized as follows:

- The dataset has info on the churn of customers as well as various data that can be used to predict future churn.
- The dataset contains two attempts: the one that assumes outliers according to the IQR and DBSCAN method (combined, because neither has detected outliers) and the Isolation Forest method.
- For each attempt, the notebook describes the data preparation, tests for the best resampler, feature selector and model + hyperparameters for each attempt.
- The models per attempt are compared, and the best model is explained, its limitations put down and its benefits visualized.
- There are recommendations on future iterations of the model as well as the business if they used the current model as is.

Note: the .ipynb was first built in Google Colab and then only the markdowns were edited in VSCode, though it has also been tested in the latter.

This project also has a video presentation found in the link below.

The file (in Google Colab) and presentation (both the file and video presentation) is also available in this Google Drive: https://drive.google.com/drive/folders/1WWJopsnzgc1w2hw821fv60TyqFBB6ViD?usp=sharing
