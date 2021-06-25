#### 1. What’s the trade-off between bias and variance?

**Bias** is **error** due to erroneous or overly **simplistic assumptions** in the learning algorithm you’re using.  This can lead to the model **underfit** your data, making it **hard for it to have high predictive accuracy** and for you to generalize your knowledge from the training set to the test set.

**Variance** is error due to **too much complexity** in the learning algorithm you’re using. This leads to the algorithm being **highly sensitive** to high degrees of variation in your training data, which can lead your model to **overfit** the data

##### avoid overfitting
  * a. Simplifying The Model
  * b. Early Stopping
  * c. Increasing size of the data.
  * d. Regularization. reduce the complexity of the model by adding a **penalty term** to the loss function. (increase lamda ) 
  * e. Dropouts, modify the network itself

#### 2. ROC curve(Receiver operating characteristic)
The ROC curve is a graphical representation of the contrast between **true positive rates** and the **false positive rate** at various **thresholds**.
<img src="https://github.com/taixingbi/interview-question/blob/master/images/2.png" width="250" height="250">

#### 3. Define precision and recall, F1 score
<img src="https://github.com/taixingbi/interview-question/blob/master/images/3.png" width="300" height="500">
<img src="https://github.com/taixingbi/interview-question/blob/master/images/4.png" width="300" height="100">


##### Recall 
true positive rate: the amount of positives your model claims compared to the actual number of positives there are throughout the data.     
##### Precision
positive predictive value: measure of the amount of accurate positives your model claims compared to the number of positives

#### 4. Bayes’ Theorem
Bayes’ Theorem gives you the **posterior probability** of an **event given what is known as prior knowledge**.
Mathematically, it’s expressed as the **true positive rate of a condition sample divided by the sum of the false positive rate of the population and the true positive rate of a condition**

#### 5. Explain the difference between L1 and L2 regularization.
L1 is more binary/sparse, with many variables either being assigned a **1 or 0** in weighting. L1 corresponds to setting a **Laplacean** prior on the terms, 
L2 regularization tends to spread error among all the terms, while L2 corresponds to a **Gaussian** prior.




