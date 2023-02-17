<b>Introduction:</b><br>
In today's fast-paced world, it can be difficult to sift through the barrage of emails, text messages, and social media posts that we receive daily. Spam messages, which are unsolicited and unwanted messages sent in large volumes, can be particularly frustrating. To address this issue, we developed a spam classifier model that uses machine learning algorithms to accurately classify messages as either spam or not.

<b>Data Collection:</b><br>
To train our model, we collected a large dataset from kaggle

<b>Data Preprocessing:</b><br>
We preprocessed the data by removing stop words, stemming, and converting all the text to lowercase. We also used techniques such as one-hot encoding and tokenization to convert the text into numerical data that can be used by the model.

<b>Model Selection:</b><br>
We experimented with several machine learning algorithms, including logistic regression, decision trees, and support vector machines. After comparing the results, we selected a Naive Bayes classifier, which gave us an impressive accuracy of 97% on our validation set.

<b>Model Evaluation:</b><br>
We evaluated the performance of our model on a test set. Our model achieved an accuracy of 96.5%, which is a strong indication that it can successfully generalize to new data and accurately classify messages as either spam or not.

<b>Conclusion:</b><br>
In conclusion, our spam classifier model achieved an accuracy of 97% using a Naive Bayes algorithm. This model has the potential to be a valuable tool for filtering out unwanted messages and improving productivity. There is still room for improvement, including incorporating additional features and data sources, as well as experimenting with more advanced machine learning techniques. However, our model represents a significant step forward in the fight against spam and the development of effective spam filters.
