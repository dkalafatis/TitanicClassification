# Titanic Dataset Classification (Decision Tree)

Dataset: The Titanic dataset is available in samples/data.

Pre-processing the data: Majority of travelers were in third class. Columns like Age, Name, and Passenger Class removed due to their correlation with the Survived column. Replaced missing values in the Age column with the average value. The data is divided into 80% training and 20% testing.

Classification: The classification tree is created using the Decision Tree operator, which uses training data from the Split Data operator. The Apply Model operator applies the model, using the tree's output and testing data. The Performance operator evaluates the model and creates a Confusion Matrix. 

The tree parameters include a maximum depth of 3, a minimum leaf size of 5, and a minimum split size of 10.


### Dependencies

* RapidMiner Studio 10.3
