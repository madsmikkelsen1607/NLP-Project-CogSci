# NLP-Project-CogSci
The project in which this readme is in, is a project about predicting genre-labels of song lyrics using TF-IDF and linear regression models.

The code for the project was ran in uCloud, a cloud computing service. To run the code yourself, you will need to open the notebook file in the src folder called project.ipynb 


Repository structure:
src/
  contains the main jupiter notebook running all code, project.ipynb
artifacts/
  contains saved outputs of code run through the notebook, including:
  validation and test evaluation tables
  per-genre performance metrics
  a serialized final model pipeline (includes TF-IDF and LinearSVC saved using joblib)
plots/
  contains saved plots from the notebook, including:
  genre distribution
  model comparison on validation data
  model performance on a per-genre basis on test set
  confusion matrix of final model on test set

To run the code yourself locally:
  Create a virtual environment using the requirements.txt
  open src/project.ipynb
  run through code chunks sequentially
      Note that this is quite computationally expensive, and some steps such as creating the plots and saving code outputs can be skipped if it is deemed irrelevant. If need be the saved model pipeline, which includes the TF-IDF and LinearSVC can be loaded.

For reproducability the dataset split was done using a fixed random seed
  
