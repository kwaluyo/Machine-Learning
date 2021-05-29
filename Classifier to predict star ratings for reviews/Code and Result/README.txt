COMP30027 Machine Learning Assignment 2
University of Melbourne

The accompanying Jupyter Notebook presents code needed to generate prediction results and shows how pre-processing, 
feature selection, and hyperparameter tuning is done. To generate predictions on the test set, simply run the entire notebook.
All CSV files (except those in review_text_features_countvec) originating from COMP30027_2020_assignment2_datasets.zip given in the LMS,
must be extracted and put in the same folder as the Jupyter Notebook file, without any sub-folders.

After running the entire notebook, the predictions of the test set given by each of our (analysed) classifiers will appear as CSV files, by the names:
1. Linear_SVC_predictions.csv
2. Random_Forest_predictions.csv
3. Zero_R_predictions.csv
4. meta_clf_for_test_predictions.csv
These files will all appear in the same folder as the .ipynb file.

Please note that due to the involvement of randomness in various stages of the process (model training, hyperparameter tuning, 
split of instances into folds for cross-validation, etc.) the hyperparameters identified as the best, accuracy metrics, confusion matrices, and the distribution of predicted labels 
(and the predicted labels themselves) will vary slightly between different runs. The analysis done in our report is based on the results of our first run.
Subsequent runs may not produce exactly the same results, so the exact numbers may not be perfectly reproducible; however, the difference will not be significant.
This is also the reason behind the slight difference between the figures in our report and in the final Jupyter Notebook file, as we have run it several more times since 
the first run (which was used for the report). 