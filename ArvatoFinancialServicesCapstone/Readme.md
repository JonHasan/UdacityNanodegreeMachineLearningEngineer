This is the repository for my development of the machine learning capstone project. My initial capstone proposal was extremely optimistic about
what could be accomplished and thus the subsequent report details how the goal has changed as a result of performing the analysis and model training. 

The arvato financial services project tasked me with trying to perform customer segmentation to see which group of people are most likely 
to become customers so that they can be targeted for a marketing campaign. The heatmaps were too large to add to the report so they are added as pdf files. 

The next part was to create an unsupervised model from the train set and to see how it performed on itself. 

Finally the supervised model was deployed on a train set with the response column being withheld to see how the model performs. These predictions were then submitted to a kaggle competition. 

There are many libraries being used for this project. 

These libraries are pandas for data preprocessing, numpy for preprocessing and data manipulation, scikit learn for metrics and models, pytorch for models, imblearn for SMOTE, seaborn for plotting, matplotlib for plotting

To install these libraries in windows simply type the following into the terminal

pip install libary_name 

Unfortunately, the project uses proprietary data given from ARVATO and as a result the data is not included with the project submission. 
