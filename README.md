# Machine_Learing_Final_Project
A project for university's Final Evaluation

So the Dataset that we are going to train our model with is a kaggle's dataset that are about "The sale of BMW cars in 15 years period of time (2010-2024)"

Let's me guild you guy to my project step by step

-1 (Data processing): You will need to do the pipeline in the "DataProcessingPipeLine.ipynb" file and after u done u will have a new file called "BMW_sales_data_after_processing.csv"

**Note: You will also need to upload the "BMW sales data (2010-2024) (1).xlsx" to your colab file before running any code if you using google colab

-2 (Linear_Regression_Model_Training): We will train a model to predict car's price using this algorithm. You guy can navigate throught the file named "Linear_Regression_meodel.ipynb" and it will guild you guy through every thing we did in order to trian our model.

**Butttttt, we have faced our first obstacle. The Dataset's feature does not have linear relationship with the column [Price_USD] which is our target that lead us to trained a bad model. Our model Evaluation scrore (R2 score) only have 0.0008 for training set and -0.0012 for test set. This is not a good model at all. 

**Sooo, in order to solve this we will use another algoithm that i think is matches for the dataset we have (Random_Forest_Regressor).

-3 (Random_Forest_Regressor_Model_Training):

***I tried 3 more new algothms and still not working (i think it is the dataset problem)
