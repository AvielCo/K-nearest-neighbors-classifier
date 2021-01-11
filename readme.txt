## KNN Classifier ##

## Installation
	python version 3.7
	libraries needed:
		opencv
		numpy
		os
		argparse
		pandas
		scikit-learn
		scikit-image
		datetime
		random

## How to use?
	1. open terminal/CMD
	2. pre process TRAIN and TEST folders -> python preprocess.py [--train TRAIN_PATH] [--test TEST_PATH]
		2.1. it will be output to "processed_train" or "processed_test"
	3. start the classifier -> python knn_classifier.py <path to train set> <path to test set>
		3.1. output -> csv file that will hold both knn distance results
	
## Credits
	Aviel Cohen - 313127664
	Vitaly Nechayuk - 324359926

SCE © [AviVit]()