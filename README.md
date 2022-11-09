# 4045NLP

### Setup virtual environment in project

In Windows CMD, ensure you are in the folder of your repository

1. Run `python –m venv venv`
2. Run `venv\Scripts\activate` 
3. Run `pip install -r requirements.txt`
4. Not sure if really needed: Run `ipython kernel install --user --name=cz4032-project2` package: `ipykernel==6.17.0`

All required packages should have been installed!

`venv\Scripts\activate` is also the <b>command to enter your virtual environment</b> whenever you want to run the application on CMD


### Instruction Guide to read the files

```
project
│
│   part3.ipynb : scripts for part3
│   
│   german.data : data from german dataset
│   
│   ....
│   
└───datasets
│   │   german.data.txt
│   │   file2
│   │
│   └───subfolder1
│   │   │   file1
│   │   │   file2
│   │
│   └───subfolder2
│   │   │   file1  