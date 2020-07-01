# Handwritten digit recognition - Kaggle

In this project, I try to predict hand-written digits. The dataset that I used is from [Kaggle](https://www.kaggle.com/c/digit-recognizer/data), but you can also use the MNIST dataset.


## Procedures:
1. Data preparation
2. Modeling
    1. Feature Extraction
    2. Classification
3. Evaluation
4. Submission
5. Visualization of results
    1. Accuracy plot
    2. Loss plot


#### Here is my accuracy plot;

![Accuracy plot](https://user-images.githubusercontent.com/32341138/75608588-f159fe80-5b11-11ea-96e5-6a0559fbfb1d.png)

We see that accuracy is gradual increases. An increase in accuracy means that our model is learning our model better.

#### Here is my loss plot;

![Loss plot](https://user-images.githubusercontent.com/32341138/75608606-18b0cb80-5b12-11ea-8a64-c3c84e077d3d.png)

Also, we see that the loss is decreasing. I did not use more than 4 epochs to prevent overfitting.
While I trained my model, I used train data and validation data. Therefore, we can also plot the validation accuracy and validation loss values.

To learn about more about [MNIST](https://www.tensorflow.org/datasets/catalog/mnist)
