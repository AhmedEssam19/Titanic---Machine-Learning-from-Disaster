# Titanic - Machine Learning from Disaster
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew. While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.
In this challenge, I', building a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).
 
## Machine Learning Pipeline
1. Simple Imputer with most-frequent strategy for categorical data.
2. One Hot Encoder for categorical data.
3. Simple Imputer with mean strategy for numerical data.
4. Feature Scaler for numerical data.
5. Random Forest Classifier

## Further Improvements
* Grid Search is applied to the model to tune hyperparameters.

## Result
The model could take 3557<sup>th</sup> place out of 23529 with accuracy 0.78468.


* For more information about the competition [click here](https://www.kaggle.com/c/titanic/overview)
