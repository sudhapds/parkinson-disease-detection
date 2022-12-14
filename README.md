# parkinson-disease-detection

To build a model to accurately detect the presence of Parkinson’s disease in an individual. Parkinson’s disease is a progressive neurodegenerative disorder that affects people significantly affecting their quality of life. This disease mostly affects the motor functions of the human. The main motor symptoms are collectively called “Parkinsonism” or “Parkinsonian syndrome”. The symptoms of Parkinson’s disease will occur slowly, the symptoms include shaking, rigidity slowness of movement and difficulty with walking, thinking and behavior change, depression, and anxiety are also common. In our model, a huge amount of data is collected from the normal person and also previously affected person by Parkinson’s disease. These data are trained using machine learning algorithms such as Logistic Regression, Decision Tree, Random Forest (Information Gain), Random Forest (Entropy), Support Vector Machine, K-Nearest Neighbor, Gaussian Naïve Bayes, Bernoulli Naïve Bayes, Voting Classifier and XGBoost. From the whole data, 60% is used for training and 40% is used for testing. The data of any person can be entered, to check whether the person is affected by Parkinson’s disease or not. There are 24 columns in the dataset each column will indicate the symptom values of a patient in the status column. The status column has 0’s and 1’s. 1’s indicates that the person is affected, and 0’s indicatesthe normal condition. Finally, the accuracy of each model are shown. Detection can be done by the model which gives the highest accuracy.
