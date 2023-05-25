# The-Project-Stroke-Prediction
This project utilizes real-world and synthetic datasets to predict stroke events by analyzing clinical features. The aim is to determine the most key risk factors for strokes by investigating parameters like gender, age, hypertension, heart disease, and lifestyle choices.

## Requirements

To install requirements:

```setup
install healthcare-dataset-stroke-data.csv
```

> The healthcare-dataset-stroke-data.csv data from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset) is used.

## Training

To train the model(s) in the paper, run this command:

```train
log_reg.fit(X_train, y_train)
```

> The given command is used to train logistic regression among the models used in the project. It has been applied to other models in similar ways.

## Evaluation

To evaluate my model on ImageNet, run:

```eval
python eval.py --model-file mymodel.pth --benchmark imagenet
```

>📋  Describe how to evaluate the trained models on benchmarks reported in the paper, give commands that produce the results (section below).

## Pre-trained Models

You can download pretrained models here:

- [My awesome model](https://drive.google.com/mymodel.pth) trained on ImageNet using parameters x,y,z. 

>📋  Give a link to where/how the pretrained models can be downloaded and how they were trained (if applicable).  Alternatively you can have an additional column in your results table with a link to the models.

## Results

Our model achieves the following performance on :

### [Image Classification on ImageNet](https://paperswithcode.com/sota/image-classification-on-imagenet)

| Model name         | Top 1 Accuracy  | Top 5 Accuracy |
| ------------------ |---------------- | -------------- |
| LogisticRegression |  79.47%     |    99.32%   |



<img
  src="![output](https://github.com/AleynaBeyzaKaan/The-Project-Stroke-Prediction/assets/83243392/6f8253eb-115b-4c33-8bdc-6786b29958d6)
"
  alt="C:\Users\DELL\Desktop\0a2efefd-05e2-412b-9a26-411175474ba8.png"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

>📋  Include a table of results from your paper, and link back to the leaderboard for clarity and context. If your main result is a figure, include that figure and link to the command or notebook to reproduce it. 


## Contributing

>📋  Pick a licence and describe how to contribute to your code repository. 
