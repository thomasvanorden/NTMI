# NB vs CNN on IMDb dataset
This code is established for a assignment from the University of Amsterdam.

Students: Lucas Meijer, Lodewijk Loerakker, Thomas van Orden

Course:   Natural Language Modeling and Interfaces (University of Amsterdam)

## Setup
1. The dataset can be found here: http://ai.stanford.edu/~amaas/data/sentiment/
2. Create a folder
3. Unpack all the .zip files in that folder
4. Create two subfolders named 'test' and 'train'
5. These two subfolders should contain the dataset
	5a. These two subfolders should at least both contain a folder 'neg' and a folder 'pos'
	5b. These 'pos' and 'neg' folders should contain all positive and respectively negative .txt files from the dataset.

## How to install the environment?
Download the env.yaml file. Then, follow these instructions to install the environment: https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

## How to use our CNN model?
1. Open jupyter notebook
2. Run Extract_and_clean.ipynb
3. Run Training.ipynb
4. Run Testing.ipynb

## How to use our NB classifier?
1. Open jupyter notebook
2. Run nb_classifier.ipynb

## Report
The report.pdf is written by Thomas van Orden and describes our method in more detail and discusses the results we obtained.
