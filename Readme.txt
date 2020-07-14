Python: 3.7.3

Libraries:
numpy version:  1.16.2
pandas version:  0.25.3
tqdm version:  4.38.0
scipy version:  1.2.1
sklearn version:  0.21.2

Step for creating submission
1) Run all covid_africa_cc.ipynb (this script make prediction confirmed cases)
2) Run all covid_africa_fatal.ipynb (this script make a file with prediction "predict_0.4.csv")

My solution its blending of 2 models: fitting of the logistic curve and linear model, where
every day adds some constant value. 

Data: i use datasets from https://github.com/CSSEGISandData