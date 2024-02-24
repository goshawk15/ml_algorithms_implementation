Dataset Description

The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult: http://www.vinhoverde.pt/en/<br>
The features of the dataset are:<br>
   1 - fixed acidity<br>
   2 - volatile acidity<br>
   3 - citric acid<br>
   4 - residual sugar<br>
   5 - chlorides<br>
   6 - free sulfur dioxide<br>
   7 - total sulfur dioxide<br>
   8 - density<br>
   9 - pH<br>
   10 - sulphates<br>
   11 - alcohol

And the classes of the dataset are<br>
   12 - quality (score between 3 and 9)


The goal is to train models that can predict the quality of a wine based on the attributes of the sample we provide

This is a multiclass classification problem since it has values ranging from 3 to 9
We use 3000 samples to train the models and we use 100 to test them

Each of the algorithm code cell is followed by another one where we test the accuracy for both the training and the testing set
The function where we calculate the accuracy is defined in the first cell of the ipynb 
