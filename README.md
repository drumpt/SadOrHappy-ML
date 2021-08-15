# 희노애락(Sad or Happy) Machine Learning Part

## Description
- Facial expression classification model for facial expressions rhythm game developed by `tensorflow keras`.
- This project was done in the third week of [KAIST Immersion Camp](https://www.madcamp.io) in 2019 winter semester.

## Requirements
```txt
python>=3.7
numpy
keras
matplotlib
```

## Usage
- run all cells in `SadOrHappy_facial_expression_classifier.ipynb` sequentially.

## Model Architecture
`3 conv2d -> max pooling -> 2 conv2d -> max pooling -> flatten -> dense -> ReLU -> dense -> softmax`
<img src="https://github.com/drumpt/SadOrHappy_ML_Madcamp_Week3/blob/master/img/model_architecture.png" width="50%">

## Training Results
<img src="https://github.com/drumpt/SadOrHappy_ML_Madcamp_Week3/blob/master/img/training_result.png" width="50%">
