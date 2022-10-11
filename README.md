# Deep Learning Application (2021 Fall)
This repository records the programming assignments and group project. Where the coding environment is on the [Colab](https://colab.research.google.com/).

## PM2.5 Prediction ([hw1](https://www.kaggle.com/t/84398e118c78461da967baf927eb663f))
### Deep Neural Network (torch)
- Goal: predict PM2.5 of data attained from Environmental Protection Agency
- Dataset: hourly (unlabeled) data with temperature and chemical compounds
- Project detail:
    - feature selection
    - input normalization
    - mini-batch
    - dropout

## PM2.5 Prediction ([hw2](https://www.kaggle.com/c/ntu-homework2-ver2))
### CNN, RNN (keras)
- Goal: predict time-series PM2.5 of two villages
- Dataset: time-series and grid data of temperature, chemical compounds, and wind directions
- Project detail:
    - feature engineering
    - layer normalization
    - two-stage training of CNN model and LSTM model

## PM2.5 Prediction ([hw3](https://www.kaggle.com/competitions/ntu-homework3/overview))
### seq2seq (keras)
- Goal: predict time-series PM2.5 from past 8 hours to future 8
- Dataset: hourly (labeled) data data of temperature, chemical compounds, and wind directions
- Project detail:
    - sequence to sequence RNN model
    - line plot with Multi-Step prediction

## Mask Identification (*Final Group Project.ipynb*)
### image classification (keras)
- Goal: identify mask wearing properties with wearing mask, not wearing them, or wearing mask improperly
- Dataset: labeled images on kaggle, including [profile pictures](https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset), [cover photos](https://www.kaggle.com/datasets/prithwirajmitra/covid-face-mask-detection-dataset), and [crowding images](https://www.kaggle.com/datasets/andrewmvd/face-mask-detection)
- Project detail:
    - image preprocessing
    - data augmentation
    - fine-tuning the pre-trained models of VGG19 and ResNet