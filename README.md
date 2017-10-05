# Amazon-Rating-and-Review-Helpfullness-predictor
This project implements a latent factor and a collaborative filter model for Amazon rating and review helpfullness predictor.

## Brief
We develop a latent factor model using a dataset of 500,000 reviews scraped from Amazon. The algorithm yielded a MSE of 1.13 for rating prediction with user biases and demographic/temporal regularizer. (Kaggle Rank: #8/120)

## Data

The data is hosted at this [link](https://drive.google.com/open?id=0B_Cz1ZeaITeDQTRLZ2VqVEhZSzg). The data should be downloaded into the [Data](https://github.com/vnnsrk/Amazon-Rating-and-Review-Helpfullness-predictor/tree/master/Data) folder, and be unzipped as;

```
cd Data
$unzip Data.rar
cd ..
```

## IPYNB files

1. Helpfullness predictor - 
This is done using a latent factor model that accounts for user and item biases and the demographics

2. Rating predictor -
It is a product rating suggestion system or a predictor that can help us better understand and recommend things to new users.
