# **Used Car Price Prediction**
> CSC 6740 Data Mining\
> Final Project\
> Members: Srikar Pottabathula, Monique Gaye
## **Abstract**
The project's core objective is to apply data mining techniques to a large, real-world dataset of used car listings to identify key factors that determine a vehicle's value. The benefit of this analysis is to create a practical valuation tool that can provide transparent pricing and decision support for both buyers and sellers in the complex, variable second-hand automotive market.
## **Dataset**
The dataset we will be using for this project is the “Used Cars Dataset,” publicly available on Kaggle:\
[ https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data/data ]\
The dataset contains nearly 427,000 unique Craigslist listings of used cars for sale. Each listing is described by 25 features of different data types, including our target feature `price`, `year`, `manufacturer`, `transmission`, `title_status`, `odometer`, etc. This is a valuable data mining exercise as the chosen dataset is large, high-dimensional, and "messy," reflecting real-world data imperfections.
## Project File Structure
```
used_car_price_prediction/
│
├── data/
│   ├── raw/                     # Original Kaggle dataset
│   └── processed/               # Cleaned dataset
│
├── notebooks/
│   ├── 01_data_cleaning_preprocessing.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_feature_engineering_modeling.ipynb
│   └── 04_candidate_models.ipynb
│
├── results/
│   ├── figures/
│   │   ├── eda_plots/           # EDA visualizations
│   │   └── modeling_plots/      # Model performance plots
│   └── metrics/                 # Model metric JSON/CSVs
│
├── README.md
└── .gitignore
```
