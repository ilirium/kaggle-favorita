# My solution for Favorita's Kaggle Competition

[Competition desription and dataset](https://www.kaggle.com/c/favorita-grocery-sales-forecasting). It's a time series prediction.

I use the [fastai](http://www.fast.ai/2018/10/02/fastai-ai/) framework which stands on top of [PyTorch](https://pytorch.org/) deep learning platform.

**Stage 1: preparing and discovering files from the dataset**
* [convert-csv-to-better-format.ipynb](convert-csv-to-better-format.ipynb) for converting input dataset from csv to the feather file format
* [favorita-01-look-at-files-01-base-from-csv.ipynb](favorita-01-look-at-files-01-base-from-csv.ipynb) for discovering files from the dataset
* [favorita-01-look-at-files-02-additional.ipynb](favorita-01-look-at-files-02-additional.ipynb) additional for the previous notebook: using Feather and showing more information for some files

**Stage 2: data cleaning, dealing with missing values, feature engineering, checking & visualazing input data before passing to the neural net**
* [favorita-02.ipynb](favorita-02.ipynb)

**Stage 3, neural net training**
* _coming soon_

**Stage X, optimizing**
* [pandas-big-data.ipynb](pandas-big-data.ipynb) example based on train.csv how to optimize memory consumption during processing in Pandas