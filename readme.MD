### Deep Belief Networks Project in Deep Learning Course


Tested in Python 3.9.2

Dataset is NSL-KDD.zip

create data dir:
```bash
mkdir -p data/raw/{val,test,train}
mkdir -p data/processed_nslkdd
mkdir -p models
```

### How to run

1. extract the zip file into data/raw
2. run the notebook: nslkdd_feature_engineering.ipynb.
Then, there should be the following csv's
3. run the notebook: nslkdd_model_runner.ipynb in order to train and fit the model


Project Layout


![layout](images/layout.png "layout")


This Project is based on the work of: albertbup

A Python implementation of Deep Belief Networks built upon NumPy and TensorFlow with scikit-learn compatibility

https://github.com/albertbup/deep-belief-network
