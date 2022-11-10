# 4032 Data Analytics & Mining - Project 2

### Setup virtual environment in project

In Windows CMD, ensure you are in the folder of your repository

1. Run `python –m venv venv`
2. Run `venv\Scripts\activate` 
3. Run `pip install -r requirements.txt`
4. Not sure if really needed: Run `ipython kernel install --user --name=cz4032-project2`

All required packages should have been installed!

`venv\Scripts\activate` is also the <b>command to enter your virtual environment</b> whenever you want to run the application on CMD

### Instruction Guide to read the files

```
project
│
│   part2.ipynb : scripts for part2
│
│   part3.ipynb : scripts for part3
│   
│   ....
│   
└───datasets
│   │   
│   │   australian.dat (Australian)
│   │   crx.data (Crx)
│   │   german.data (German)
│   │   hepatitis.data (Hepatitis)
│   │   ionosphere.data (Ionosphere)
│   │   diabetes_data.csv (Diabetes)
│   │   mushrooms.csv (Mushroom)
│   │   Pumpkin_Seeds_Dataset.xlsx (Pumpkin)
│   │
│   └───dataset descriptions
│   │   │   descriptions for datasets from UCI
│   │
│   └───dataset analysis (output folder for part2.ipynb)
│   │   │   histograms for X datasets  
│   │   │   correlation maps for X datasets  
│   │   │   distribution bar charts for y   
│   │   │   model_statistical_overview.tsv for all datasets   
│   
│   ....
│   
└───results
│   │   
│   │   model_scores.tsv: basic information of models 
│   │
│   │   confusion matrix for all the runs  
│   │
│   
│   ....

```

### Datasets

<b>From [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets.php)</b>

1. [Statlog (Australian Credit Approval) Data Set](https://archive.ics.uci.edu/ml/datasets/statlog+(australian+credit+approval)) (Australian)
2. [Credit Approval Data Set](https://archive.ics.uci.edu/ml/datasets/credit+approval) (Credit Approval Data Set)
3. [Statlog (German Credit Data) Data Set](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)) (German)
4. [Hepatitis Data Set](https://archive.ics.uci.edu/ml/datasets/hepatitis) (Hepatitis)
5. [Ionosphere Data Set](https://archive.ics.uci.edu/ml/datasets/ionosphere) (Ionosphere)

<b>From [Kaggle](https://www.kaggle.com/datasets/)</b>

6. [Early Classification of Diabetes](https://www.kaggle.com/datasets/andrewmvd/early-diabetes-classification) (Diabetes)
7. [Pumpkin Seeds Dataset](https://www.kaggle.com/datasets/muratkokludataset/pumpkin-seeds-dataset) (Pumpkin)
8. [Mushroom Classification](https://www.kaggle.com/datasets/uciml/mushroom-classification)(Muchroom)