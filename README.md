# GoDaddy Microbusiness Density Forecasting

In this repo, i publish my two solution for Kaggle's [GoDaddy - Microbusiness Density Forecasting challange](https://www.kaggle.com/competitions/godaddy-microbusiness-density-forecasting) . After some feature engineering, I focused on following two different approaches::

* Recurrent Neural Network (GRU/LSTM with multivariate sequence-to-sequence modeling) with Tensorflow: Predicting next 4 months target
* Decision Tree (Extra/Random Forest), Boosting (Catboost and LightGBM) after doing a quick analysis with PyCaret: Predicting targets one by one

My final submission was based on [Extra-Trees](https://github.com/denizstij/GoDaddy_Microbusiness_Density_Forecasting/blob/main/extra-tree-godaddy-mbd-forecasting.ipynb) as it was faster and providing better cross validation. Deep Learning based algorithm ([GRU NN](https://github.com/denizstij/GoDaddy_Microbusiness_Density_Forecasting/blob/main/recurrent-gru-nn-godaddy-mbd-forecasting.ipynb)) , unfortonately, did not provide good result initially, hence after a while, i stopped improving it. 
