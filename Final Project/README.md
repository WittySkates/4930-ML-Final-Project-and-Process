# Final Project

Function: trainModel(X, y)
    This function takes in training data X and its corresponding labels y and outputs a trained model based on the SVM classifier. The dependencies this model uses are in the same cell that the function is defined in, requiring no additional execution. These dependencies include numpy, skimage.color.rgb2gray, sklearn.metrics.accuracy_score, sklearn.svm.SVC, sklearn.pipeline.make_pipeline, sklearn.decomposition.TruncatedSVD, skimage.feature.hog, sklearn.model_selection.train_test_split, skimage.filters
    

Function: testModelEasy(X, y)
    This function is to be used on the easy dataset. It takes in test data X and the corresponding labels y, and prints the corresponding accuracy. It returns an array containing all of the predicted labels. Thus, one must call print() on the returned object to view these labels, i.e., print(testModelEasy(X, y)). The dependencies used are in the same cell the function is defined in, requiring no additional execution. These dependencies include numpy, skimage.color.rgb2gray, sklearn.metrics.accuracy_score, skimage.feature.hog, joblib, skimage.filters, sklearn.decomposition.TruncatedSVD. The latest version of joblib must be used. 
    
    
Function: testModelHard(X, y)
    This function is to be used on the hard dataset. It takes in test data X and the corresponding labels y, and prints the corresponding accuracy. It returns an array containing all of the predicted labels. Thus, one must call print() on the returned object to view these labels, i.e., print(testModelHard(X, y)). The dependencies used are in the same cell the function is defined in, requiring no additional execution. These dependencies include numpy, skimage.color.rgb2gray, sklearn.metrics.accuracy_score, skimage.feature.hog, joblib, skimage.filters, sklearn.decomposition.TruncatedSVD. The latest version of joblib must be used. 
    
Example:
    Example code is listed below these two functions, loading data into X and y, calling the functions, and printing the returned objects. This will display the corresponding accuracies and predicted labels. 