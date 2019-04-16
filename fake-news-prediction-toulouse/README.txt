This directory includes one fake news dataset that contain both the news contents and social context information.

News directory :

training: this directory contains the content of the news in the training set. Each file is a news stored in the txt format and contains the title, the summary and the content of the news. The name of the txt file is @news_id.txt where @news_id is the identifier of the news.
test: this directory contains the content of the news in the test set. The news are represented in the same format than for the training directory
newsUser.txt: the news-user relationship. For example, '240 1 1' means news 240 is posted/spreaded by user 1 for 1 time.

UserUser.txt: the user-user relationship. For example, '1589 1' means user 1589 is following user 1;

labels_training.txt: indicate whether the news in the training set is fake (1) or real (0). For example '23 0' means the news 23 is real.
random_submission.txt: an example of submission. The first column is the doc id and the second column is the predicted class (0 for real news and 1 for fake news)
The use of the news id as a feature is strictly prohibited.