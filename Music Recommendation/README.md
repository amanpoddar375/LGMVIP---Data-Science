## Music Recommendation System on WSDM - KKBox's Music Recommendation Challenge Datasets

I was asked to predict the likelihood of a user listening to a song repeatedly after the first observable listening event within a time window was triggered in this task.

The LightGBM algorithm was used. LightGBM is a framework for gradient boosting that employs tree-based learning algorithms. LightGBM extends the gradient boosting algorithm by incorporating a type of automatic feature selection and concentrating on boosting examples with larger gradients. This can result in a significant increase in training speed and improved predictive performance.

Advantage of using LightGBM

Faster training speed and higher efficiency, Lower memory usage, Better accuracy,Support of parallel and GPU learning,Capable of handling large-scale data.

I have implemented LightGBM & have achieved accuracy of 77.28% on test data which was very high compared to accuracy of some random model on test data.

You can download the datasets from [here](https://www.kaggle.com/competitions/kkbox-music-recommendation-challenge/data)
