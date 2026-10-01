# Reproducibility Summary

Many aspects of this project have allowed for maximum reproducible potential. For starters, I ensured that all packages and libraries were loaded within the first cell. The notebook will not run without this cell. When a scientist runs the code all the way through, as instructed, then the workflow should work as ordered. The package versions and expected outputs were also listed in the README file for easy comparison and fixes.

Additionally, a data validation procedure has been added within a cell of the notebook. If the uploaded data does not fit the required shape, then a warning message will appear. 

For any mathematic specific information, all variables and predictors have been related back to our specific dataset rather than leaving them as general math templates.

All visualizations and statistical tests are specific to the dataset and rely on the column names. The plots and statistical tests will not work if the dataset columns have been changed. The correlation matrix was also posted in the README. Each correlation value should be identical to the heatmap posted.

Lastly, any analysis that requires random sampling included a random_state = 11 argument to ensure all results were identical, even after running again.

Overall, I believe if a scientist were to upload the notebook and dataset to a Google Colab session, they would get identical outputs and analysis results. If they were to use another software like VS Code or Jupyter, the same results can be produced as long as the package types and versions are the same, instructions are followed, the directories are correct, and no additional dependencies have been loaded.
