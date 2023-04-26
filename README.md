# Click-Through-Rate-Prediction
Name: Pranay Tej Thirutopu
700#: 700747894

Group Members:
Pranay Tej Thirutopu
Astha Diamond Cheemala
Bhaskar Adari

Abstract:
Digital advertising industry made revenue of 31.7 billion dollars in the fiscal year of 2016. Main challenges in this industry or suggesting or recommending the right advertisement to the right people by predicting the click through rate of the advertisement.Data to predict the click through rate contains diverse data: few columns are categorical, few columns are identifiers which throws a challenge while classifying the data. Dataset is complex to use normal classification algorithms like SVM, logistic regression. The dataset file size is 1.28 GB which is considered to be the huge dataset to process. To process the complex dataset and to produce the results we are using the LightGBM classifier which uses high grade boosting methods and multiple decision trees in the learning stage. Main advantage of this algorithm is it also supports the GPU training.In addition to LightGBM classifier XGBoost algorithm also implemented to compare the performance on the dataset.To conduct the experimental analysis we collected the Avazu datset from kaggle. Both the algorithms achieved 82 percent accuracy but the training time of LightGBM is less compared to Gradient boosting algorithm.

Implementation:
This project implementation is divided into following steps:
• Data collection: data is collected from Kaggle.
• Data preprocessing: In this step we have removed the null values in the dataset and duplicates also.In the Exploratory data analysis we analyzed the underlying
structure of the data.
• Data preparation : In the data preparation step label
encoded the categorical values in the data and the data is
split into training and testing
• Since the dataset contains 4 million records, training
time is so long so we used the subset of dataset i.e. 10000 samples to train the data.In the last step we have implemented the 2 algorithms LightGBM and XGBoost algorithm.
• In the implementation step of machine learning algo- rithms XGBoost is implemented using scikit-learn library and LightGBM is lightgbm library. Both the algorithms achieved reasonable accuracy of 82 percent on test data

Please find the train data in the following link:
https://drive.google.com/file/d/1xaOqWTD15K6pOOzOaZYz1kRvUfx_mlKp/view?usp=sharing

Please find the reduced data in the following link:
https://drive.google.com/file/d/19oMtcVmNlVP14KTCpRMdk2uOF4hReHSF/view?usp=sharing
