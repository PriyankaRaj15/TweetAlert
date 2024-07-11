**TweetAlert: Real-time Disaster Detection from Twitter**

**Project Overview**

TweetAlert is a machine learning-based system designed to detect and classify tweets that indicate disasters in real-time. Leveraging the widespread use of Twitter during emergencies, TweetAlert aims to assist disaster relief agencies, news outlets, and the general public by providing timely and accurate information about ongoing crises.

**Features**

Real-time Disaster Detection: Monitors Twitter for potential disaster-related tweets.
Machine Learning: Utilizes a Naive Bayes classifier trained on labeled tweet data to distinguish between disaster and non-disaster tweets.
Text Preprocessing: Cleans and processes tweet text to improve model accuracy.
Visualization: Includes graphical representations of model performance and predictions.

**How It Works**
Data Collection: Gathers tweets from Twitter (provided as datasets for this project).
Text Preprocessing: Cleans the tweet text by converting to lowercase, removing URLs, mentions, hashtags, digits, and punctuation.
Feature Extraction: Converts text data into numerical features using TF-IDF vectorization.
Model Training: Trains a Naive Bayes classifier on the preprocessed and vectorized tweet data.
Prediction: Classifies new tweets as either disaster or non-disaster based on the trained model.
Evaluation: Evaluates the model's performance using accuracy, classification reports, and confusion matrices.

**Installation**
To run this project locally, you will need to install the required Python libraries. You can install them using the following command:
pip install pandas numpy scikit-learn matplotlib seaborn

**Usage**
clone the repository
git clone https://github.com/PriyankaRaj15/TweetAlert.git
cd TweetAlert
Prepare Your Data:
Ensure you have train.csv and test.csv files in the project directory. The train dataset should contain columns: id, keyword, place, tweet, disaster. The test dataset should contain columns: id, keyword, place, tweet.
Run the Script:
python tweetalert.py

**Project Structure**
train.csv: Training dataset with labeled tweets.
test.csv: Test dataset with tweets to classify.
tweetalert.py: Main script containing the data preprocessing, model training, prediction, and evaluation code.

**Visualization**
The project includes visualizations to help understand model performance and data distribution:

Confusion Matrix: Visualizes the true vs. predicted classifications.
Label Distribution: Shows the distribution of labels in the training set and the predictions in the test set.

**Contributions**
Contributions are welcome! If you have any suggestions, enhancements, or bug fixes, please feel free to create a pull request or open an issue.

**Acknowledgments**
Special thanks to the contributors and the open-source community.
The dataset used for this project is sourced from Kaggle.

