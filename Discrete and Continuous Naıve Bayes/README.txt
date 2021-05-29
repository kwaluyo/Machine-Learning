COMP30027 Machine Learning Assignment 1
Kartika Waluyo (1000555) & Andrew Thomas Liongosari (954475)
University of Melbourne

The accompanying Jupyter Notebook presents an implementation of Naive Bayes Classifier.
To run the full process (find the accuracy of the classifier on a specific file using a specific set of parameters), run the functions in the manner specified below:

(X_train, X_test, y_train, y_test) = preprocess(filename, class_column, train_proportion, ID, discretise_numeric_dataset, n_bins)      		(to get the training and testing sets)
model = train(X_train, y_train, dataset_type, k, attr_type_array)									(to get the model)
predictions = predict(model, X_test)											(to generate predictions)
accuracy = evaluate(predictions, y_test)											(to find the accuracy)

For the data types and default values associated with these arguments, see the docstring on the code.
For the preprocess() function to run correctly, please ensure that the file specified in filename is in the same folder/directory as the Jupyter Notebook file.
This file must not have any headers, and if there are any ID columns, they must be the first column.

To generate the results discussed in our report, simply run all cells in the Jupyter Notebook, from the top to the bottom. Do not run them out of order, as this may cause errors and incorrect results.

For more information about the functions and how they should be used/called, see the documentation on the code.

Academic honesty disclaimers:
1. A small part of the code is adapted from code provided in the workshop. For more information about which parts specifically, see the documentation on the code.
2. The idea to use log probabilities and to use a nested dictionary structure is given by Kris Ehinger during COMP30027 lectures and are NOT our original ideas. All credit for these ideas go to her.
