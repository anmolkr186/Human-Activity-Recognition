# Human_Activity_recognition

## About the Project
Human posture recognition and analysis have been a widely studied topic these days because of wearable devices' innovation. Thus, activity tracking becomes an exciting use-case for healthcare and fitness tracking applications for both the elderly and adults. In this study, we present the analysis of several machine learning models to detect a human's posture by the data gathered by various accelerometers attached to the body. Support Vector Machines, Logistic Regression, Random Forest Classifier, Stochastic Gradient Descent, K-means clustering, and Gaussian Discriminant Analysis are evaluated and reported in this study.

## Results
After conducting the above experiments, it can be concluded by looking at the observations that the technique which yields the most accurate results is the random forests technique (max_depth = 16), then the neural networks, followed by the Gaussian discriminant analysis. Approximately 99% accurate results from the Random Forest model, 98.5% accurate from the neural network with the rectified linear activation and learning rate equal to 0.05, and almost 92% accurate results from GDA are obtained. 
This is because the random forest is based on the principle of bagging. Thus a lot of training samples can be generated, and in turn, numerous low learning trees are generated, and their weighted mean results in a highly learned tree. SVM, Logistic regression, K-means clustering, and SGD have shown comparatively less accurate scores, and thus it can be concluded that Random forest is the best predictor.

## Co-contributors
*Anmol Kumar(2018382)
*Rishabh Chauhan (2018256)
