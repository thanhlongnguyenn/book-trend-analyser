# EODP Assignment 2 Group W03G4 - Finding the trends of most popular books

The code is written in Jupyter Notebook in Python 3 language. It aims to transform raw data from CSV files into meaningful information that can support the research of trends in popular books 

## Structure
```bash
.
├── Age_Analysis.ipynb
├── Author_Analysis.ipynb
├── BX-Books-Clean.csv
├── BX-Books.csv
├── BX-Ratings-Clean.csv
├── BX-Ratings.csv
├── BX-Users-Clean.csv
├── BX-Users.csv
├── Country_Analysis.ipynb
├── Feature_Selection.ipynb
├── KmeansClustering.ipynb
├── Popular-Alternative-Country-Names.json
├── Popularity_Analysis.ipynb
├── Preprocessing.ipynb
├── README.md
├── Regression.ipynb
├── World-Countries.csv
└── new_data_clean_up.ipynb
```


## Requirements

Python libraries are used in the development progress. These libraries include:
- [numpy](https://numpy.org/install/)
- [pandas](https://pandas.pydata.org/getting_started.html)
- [matplotlib](https://matplotlib.org)
- [scikit](https://scikit-learn.org/stable/)
- [nltk](https://www.nltk.org)
- [unidecode](https://pypi.org/project/Unidecode/)

These libraries must be install prior to running the Python scripts in Jupyter Notebooks.

## Usage
1. Run **Preprocessing.ipynb** in order to produce new cleaned data files that will be stored in the same directory
2. Run **new_data_clean_up.ipynb** to preprocess data for regression
3. Run either **Regression.ipynb** or **KmeansClustering.ipynb** to get the visualised data for machine learning techniques used in our report
4. The rest of .ipynb file in the directory are used for preliminary analysis, and feature selection. This can also be run to get graphs of our data exploration.

> In the case of unsuccessful installation of the required libraries, pre-processed data files including **BX-Books-Clean.csv**, **BX-Ratings-Clean.csv** and **BX-Users-Clean.csv** have been added to the same directory in order to run other scripts.

## Support

Please email to one of our group memebers if there is clarification needed when running the scripts.

### Email addresses
1. [Sarah Williams](sarwilliams@student.unimelb.edu.au)
2. [Thanh Long Nguyen](thannguyen@student.unimelb.edu.au)
3. [Jessica Do](doj1@student.unimelb.edu.au)
