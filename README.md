# Applied-Deep-Learning-and-Artificial-Intelligence-Chow-and-Signe
In this assignment, we have delve into the practical aspects of Deep Learning by constructing and evaluating a neural network using Pytoch. This assingment has been created to deepen our understanding of neural network achitectures, hyperparameter tuning, and the preprocessing steps necessary for effective model training and evaluation. The dataset choosen is the Pima-Indians-Diabetes-Dataset and is originally from the National Institute of Diabetes and Digestive and Kidney Diseases, contains information of 768 women from a population near Phoenix, Arizona, USA. The outcome tested was Diabetes, 258 tested positive and 500 tested negative

In the assignment we begin by checking the data set out and begin analyzes for feautre selection. Out of the original 8 input, we have selected 4 feature in our model and began creating preprocessing our data, by scaling and making a test-train split, where 20% of the data is the test data. This data set is transformed into tensor data for our training model and put into our neural network. As our data set output are binary outcomes, then the achtitecture of our Neural Network and our loss function has to accommodate for that. After defining the Neural Network and the Training Loop taking into consideration of the data, then 5 model has been created with different Hypermeters, and the 5th model has been saved and evaluated on the Test Data. 

# Relevant information regarding the collection of data
The constraint of the collection of data is as follows: those involved with the study is limited to female at age 21 and over, and of the Pima Indian heritage. 

# Feature
The features in the data set is limited to:
1. Number of pregnancies
2. The results of a 2 hour glucose tolerance test
3. Diatolic blood pressure measured in (mm HG)
4. Triceps skin fold thickness measured in (mm)
5. The amount of serum insulin after 2 hours measured in ( mu U/ml)
6. BMI - BodyMassIndex
7. Diabetes pedigree function
8. Age
9. Class vairable
