I worked on Google Colab with all the dataset. 
The codes are not in the order that will run on test or train.
We should run the correct parts with correct order if we want a spesific result.

Functions:
	- class CNN(module)
		- __init__: Contains the architecture of the model.
		- forward: Contains the correct order of the architecture.
	- train: The train function.
	- test: The test function.
	- report: Gives the accuracy of the preds.
	- confusion_matrix: Gives the confusion_matrix.
	- plot_confusion_matrix: Plots the given confusion_matrix.
	- graph_loss_accuracy: Plots the accuracies and loss points of validation and train.