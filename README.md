## Logistic regression model used to predict who survived the Titanic sinking

The dataset in this example, as I understand it, is broadly available (e.g., on kaggle), but I downloaded it from the git repository of the 2nd Edition IPython Interactive Computing and Visualization Cookbook.

Two CSV files are curl downloaded from the aforementioned repo, a training file and a testing file. The model employed in the Notebook is a logistic regression from the sci-kit learn library, on which we also perform cross-validation when fitting to the traning set. Using the test file, and the trained logreg model, we predict which passengers will survive the Titatnic.