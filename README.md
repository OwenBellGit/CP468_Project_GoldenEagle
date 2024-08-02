# CP468_Project_GoldenEagle

The data is provided in this link to a google drive which has our training, validation and test set
https://drive.google.com/drive/folders/1UJAJyGPIWJSN1vQfiw59wiYDyQHQp2Y5

For our given problem of identifying golden eagles there are two classes "GoldenEagle", any bird that is a golden eagle and "NotGoldenEagle" which is any bird that is not a golden eagle. Our original Kaggle dataset over 80,000 images but due to space and computational time of training on so many images we shortened the amount of images used to 1629 images total. 1247 belonging to training (372 GoldenEagle, 875 NotGoldenEagle) , 100 for validation (44 GoldenEagle, 66 NotGoldenEagle) and 282 (20 GoldenEagle, 262 NotGoldenEagle) for testing. 

To solve the classification problem, we use three pre trained models: ResNet50, InceptionV3 and MobileNet. All three models are fine tuned on our dataset in to adapt their pre trained features to our problme of classifying between "GoldenEagle" versus "NotGoldenEagle". We wanted to take advantage of these models well-established architectures to enchace classification performance and accuracy for the problem by retraininh them on our carefully selected dataset. 
